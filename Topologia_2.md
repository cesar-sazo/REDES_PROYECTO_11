# CONFIGURACION TOPOLOGIA 2   

* CONFIGURACION DE LOS "VTP"
En esta configuracion se modifica el dominio que trae por defecto
y se coloca una contrasena. Adicioanalmente se configura
si el switch sera cliente o servidor.
```
conf t
vtp domain [identificador del grupo]
vtp password [contrasena para el grupo]
vtp mode [modo server/client]
end
```
### MODO SERVER ESW4
![This is a alt text.](/img/VTPS/ModoserverESW4.png "This is a sample image.")
### MODO CLIENTE ESW1
![This is a alt text.](/img/VTPS/ModoclienteESW1.png "This is a sample image.")
### MODO CLIENTE ESW2
![This is a alt text.](/img/VTPS/ModoclienteESW2.png "This is a sample image.")
### MODO CLIENTE ESW3
![This is a alt text.](/img/VTPS/ModoclienteESW3.png "This is a sample image.")


* CONFIGURACION DE LOS "TRUNK"
Hay conexiones que deben ser troncales, en este caso vemos 
la configuracion necesaria para poder colocarlas como
troncales. Indicando el modo y las vlans permitidas
```
conf t 
int [identificador del puerto]
switchport mode trunk
switchport trunk allowed vlan 1,10,20,30,1002-1005
exit
```
### ESW1
![This is a alt text.](/img/PuertosModoTronkal/ESW1/ESW1-Switch1.png "This is a sample image.")

### ESW2
![This is a alt text.](/img/PuertosModoTronkal/ESW2/ESW2-Switch3.png "This is a sample image.")

### ESW3
![This is a alt text.](/img/PuertosModoTronkal/ESW3/ESW3-Switch2.png "This is a sample image.")


* CONFIGURACION DE LOS "SWITCH"

### ACCESS VLAN SWITCH 1
![This is a alt text.](/img/Switch/accessvlanSwitch1.png "This is a sample image.")

### ACCESS VLAN SWITCH 2
![This is a alt text.](/img/Switch/accessvlanSwitch2.png "This is a sample image.")

### ACCESS VLAN SWITCH 3
![This is a alt text.](/img/Switch/accessvlanSwitch3.png "This is a sample image.")

### TRONCAL SWITCH 1
![This is a alt text.](/img/Switch/TroncalSwitch1.png "This is a sample image.")

### TRONCAL SWITCH 2
![This is a alt text.](/img/Switch/TroncalSwitch2.png "This is a sample image.")

### TRONCAL SWITCH 3
![This is a alt text.](/img/Switch/TroncalSwitch3.png "This is a sample image.")

### TRONCAL SWITCH 4 NUVES Y ROUTER
![This is a alt text.](/img/Switch/TroncalSwitch4nuvesyrouter.png "This is a sample image.")


* SHOW PORT Y SUMMARY

### ESW1
![This is a alt text.](/img/ShowPortySummary/ESW1.png "This is a sample image.")
### ESW2
![This is a alt text.](/img/ShowPortySummary/ESW2.png "This is a sample image.")
### ESW3
![This is a alt text.](/img/ShowPortySummary/ESW3.png "This is a sample image.")
### ESW4
![This is a alt text.](/img/ShowPortySummary/ESW4.png "This is a sample image.")


* ROUTER

### ACTIVAR PUERTOS TRUNK R1
![This is a alt text.](/img/Router/ActivarpuertostrunkR1.png "This is a sample image.")
### DHCP 1
![This is a alt text.](/img/Router/DHCP1.png "This is a sample image.")
### DHCP 2
![This is a alt text.](/img/Router/DHCP2.png "This is a sample image.")

* CONFIGURACIONES DEL ESW1

### MODO TRUNCAL Y VLANS
| Po2 | Po3 | Po5 |
| ------------ | ------------- | ------------- |
| ![Screenshot](/img/ESW1/Modotroncalyvlans/Po2.png) | ![Screenshot](img/ESW1/Modotroncalyvlans/Po3.png) | ![Screenshot](img/ESW1/Modotroncalyvlans/Po5.png) |
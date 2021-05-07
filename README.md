# PRACTICA 2 REDES DE COMPUTADORAS
# UNIVERSIDAD SAN CARLOS DE GUATEMALA
# CESAR ALEJANDRO SAZO QUISQUINAY 201513858
# HEIDY LISSETH MENDOZA CARDONA   201503811
# JONATHAN BAUDILIO HIDALGO PEREZ 201602440 
# JOSUE EDUARDO ABELARDE PEREZ    201602890 




### CONFIGURACION VPN   
* Red Vpn
![This is a alt text.](/Imagenes/vpn_.png "This is a sample image.")

* Configuracion de la VPN

Primero abrimos la consola de la MV y luego colocamos el siguiente comando.

* wget https://cubaelectronica.com/OpenVPN/openvpn-install.sh && sudo bash openvpn-install.sh

* VPN
#
![This is a alt text.](/Imagenes/vpn.PNG "This is a sample image.")

Luego Colocamos el ip externo de la mv.

Colocamos el protocolo UDP.

Hacemos que la vpn escuche el puerto 1194.

![This is a alt text.](/Imagenes/vpn1.png "This is a sample image.")


Colocamos que queremos utilizar la VPN de Google.

![This is a alt text.](/Imagenes/vpn2.png "This is a sample image.")

Luego esperamos que cree el cliente  escribiendo una llave.

![This is a alt text.](/Imagenes/vpn3.png "This is a sample image.")


Si queremos crear otro cliente basta con colocar 

* sudo bash openvpn-install.sh



### CONFIGURACION TOPOLOGIA 1
#
![This is a alt text.](/Imagenes/1.PNG "This is a sample image.")
* VISTA GENERAL
#


* CONFIGURACION ROUTER 6
#
![This is a alt text.](/Imagenes/2.PNG "This is a sample image.")
* CONFIGURANDO LAS IP DE LOS ROUTER CON SUS RESPECTIVAS FastEthernet Como podemos ver anteriormente se realizo
el subneteo para saber las redes al igual se configuro el Protocolo VRRP TANTO COMO ACTIVO Y PASIVO
#

#
![This is a alt text.](/Imagenes/3.PNG "This is a sample image.")
* SE REALIZO EL ENRUTAMIENTO DINAMICO CON SUS RESPECTIVAS DIRECCIONES DE RED 
#

* CONFIGURACION ROUTER 3
#
![This is a alt text.](/Imagenes/4.PNG "This is a sample image.")
* CONFIGURANDO LAS IP DE LOS ROUTER CON SUS RESPECTIVAS FastEthernet Como podemos ver anteriormente se realizo
el subneteo para saber las redes al igual se configuro el Protocolo VRRP TANTO COMO ACTIVO Y PASIVO
#

#
![This is a alt text.](/Imagenes/5.PNG "This is a sample image.")
* SE REALIZO EL ENRUTAMIENTO DINAMICO VERSION 2 CON SUS RESPECTIVAS DIRECCIONES DE RED 
#

* CONFIGURACION ROUTER 4
#
![This is a alt text.](/Imagenes/6.PNG "This is a sample image.")
* CONFIGURANDO LAS IP DE LOS ROUTER CON SUS RESPECTIVAS FastEthernet Como podemos ver anteriormente se realizo
el subneteo para saber las redes 
#

#
![This is a alt text.](/Imagenes/7.PNG "This is a sample image.")
* SE REALIZO EL ENRUTAMIENTO DINAMICO VERSION 2 CON SUS RESPECTIVAS DIRECCIONES DE RED 
#

* CONFIGURACION ROUTER 5
#
![This is a alt text.](/Imagenes/8.PNG "This is a sample image.")
* CONFIGURANDO LAS IP DE LOS ROUTER CON SUS RESPECTIVAS FastEthernet Como podemos ver anteriormente se realizo
el subneteo para saber las redes al igual se realizo el protocolo HSRP tanto como activo como Pasivo 
#

* CONFIGURACION ROUTER 7
#
![This is a alt text.](/Imagenes/9.PNG "This is a sample image.")
* CONFIGURANDO LAS IP DE LOS ROUTER CON SUS RESPECTIVAS FastEthernet Como podemos ver anteriormente se realizo
el subneteo para saber las redes al igual se realizo el protocolo HSRP tanto como activo como Pasivo 
#

#
![This is a alt text.](/Imagenes/Captura.PNG "This is a sample image.")
* SE REALIZO EL ENRUTAMIENTO DINAMICO VERSION 2 CON SUS RESPECTIVAS DIRECCIONES DE RED 
#








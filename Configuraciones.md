# Configuraciones

## Topología 1  
![Imagen](img\TOPO1_TOPOLOGIA.PNG)

##  Configuración de IP 
VLAN   | NUMERO  |  IP | GATEWAY
------------- | -------------|------------------|----
RED1     | 13 | 192.168.10.10/24| 192.168.10.254
RED2     | 23 | 192.168.20.10/24| 192.168.20.254  
RED3     | 33 | 192.168.30.10/24| 192.168.30.254
RED4     | 43 | 192.168.40.10/24| 192.168.40.254

## Topología 2  
![Imagen](img\topologia2.PNG)

##  Configuración de IP 
VLAN   | NUMERO  |  IP 
------------- | -------------|------------------
RED5     | 53 | 70.0.50.10/16
RED5     | 53 | 70.0.50.20/16
RED6     | 63 | 70.0.60.10/16  



## Configuracion VPN
![Imagen](img\TOPO1_NUBE.PNG)

## Configuracion Topologia 1  
###  DIST1
HSRP
![Imagen](img\TOPO1_DIST1_HSRP_ACTIVO.PNG)
 PORTCHANNEL 
![Imagen](img\TOPO1_DIST1_PORTCHANNEL.PNG)
 VLANS
![Imagen](img\TOPO1_DIST1_VLANS.PNG)
 VTP
![Imagen](img\TOPO1_DIST1_VTP.PNG)

###  DIST2
HSRP
![Imagen](img\TOPO1_DIST2_HSRP_PASIVO.PNG)
 PORTCHANNEL
![Imagen](img\TOPO1_DIST2_PORTCHANNEL.PNG)
 VLANS
![Imagen](img\TOPO1_DIST2_VLANS.PNG)
 VTP
![Imagen](img\TOPO1_DIST2_VTP.PNG)

###  Nucleo 1
Ruteo
![Imagen](img\TOPO1_NUCLEO1_RUTEO.PNG)

###  Nucleo 2
Ruteo
![Imagen](img\TOPO1_NUCLEO2_RUTEO.PNG)
###  R1
Ruteo
![Imagen](img\TOPO1_R1_RUTEO.PNG)

## Configuracion Topología 2
### ESW1
EIGRP
![Imagen](img\ESW1_topo2_gateway_eigrp.PNG)
RUTEO
![Imagen](img\topo2_ruteo_ESW1.PNG)

### ESW2
EIGRP
![Imagen](img\ESW2_topo2_gateway_eigrp.PNG)
RUTEO
![Imagen](img\topo2_ruteo_ESW2.PNG)

### ESW3
EIGRP
![Imagen](img\ESW3_topo2_gateway_eigrp.PNG)
RUTEO
![Imagen](img\topo2_ruteo_ESW3.PNG)

### R1
OSPF
![Imagen](img\r1_int_ospf_static_topo2.PNG)
RUTEO
![Imagen](img\topo2_ruteo_r1.PNG)

### PING

![Imagen](img\ping_topo2_vpc_topo1.PNG)

![Imagen](img\ping_vpc_gateway_virtual_topo2.PNG)

### Captura de Paquetes
![Imagen](img\pkg_topo1.png)

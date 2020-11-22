# Manual de Comandos  
### Configuracione de las interfaces  
  
```
#conf t
#int f#/#
#ip address [ip] [mask]
#speed 100
#full-duplex
#no shutdown
```
### DIST 1 RIP
```
#configure terminal
#router rip
#version 2
#network 13.0.0.0
#network 23.0.0.0
#network 192.168.0.0
#network 192.168.10.0
#network 192.168.20.0
#network 192.168.30.0
#network 192.168.40.0
```

 ### DIST 2 RIP

 ```
#configure terminal
#router rip
#version 2
#network 33.0.0.0
#network 43.0.0.0
#network 192.168.0.0
#network 192.168.10.0
#network 192.168.20.0
#network 192.168.30.0
#network 192.168.40.0
```
### VLAN
```
#conf t
#vlan 23
#name Red2
#end
```
### Puertos en modo troncal
```
#conf t
#int range f#/# - #
#switchport mode trunk
#switchport trunk allowed vlan 1,#,1002-1005
#end
```
### EIGRP 
```
#conf t
#router eigrp 10
#network 10.10.0.0 0.0.0.255
#end
```

### VTP
```
#conf t
#router eigrp 10
#network 10.10.0.0 0.0.0.255
#end
```

### PORTCHANNEL 
```
#conf t
#innterface range f#/# - #
# channel-group # mode on
#end
```




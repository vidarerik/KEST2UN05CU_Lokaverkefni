# Listi yfir IP/Adressing og Permissions

# Ljosleiðaribox:
## interface FastEthernet7/0
## IP address 145.1.2.2 255.255.255.252

# wRouter0: (Meira um Wireless Router 0 fyrir neðan líka)
## User: admin // Password: Mario
## IP: 145.1.2.1/30
## gw: 145.1.2.2

# WRouter1: (Wireless ADSL Router)
## User: admin // Password: Mario
## IP: 192.168.0.1
## Sub: 255.255.255.0

# tskoli.is_server:
## IP: 2.2.2.4
## Sub: 255.255.255.0
## Default: 2.2.2.2
## DNS: 2.2.2.3

# ISP_Router / Current Config

# interface FastEthernet6/0
## ip address 2.2.2.2 255.255.255.0 

# interface GigabitEthernet7/0
## ip address 147.2.2.2 255.255.255.0

# interface GigabitEthernet8/0
## ip address 192.168.99.1 255.255.255.0

# ip classless
## ip route 145.1.2.0 255.255.255.252 192.168.99.2

# ISP/TCHP Server:
## IP: 147.2.2.1
## Subnet: 255.255.2550
## Default: 147.2.2.2
## DNS 2.2.2.3

# Heimili 1 server:
## IP: 192.168.0.108
## Subnet: 255.255.255.0
## Default: 192.168.0.1
## DNS: 2.2.2.3

# Heimili 2 server:
## IP: 192.168.0.4

****************************
# Aðgangsorð/Auka Addressing
## Ljósleiðari-router: zelda123
## ADSL_Router: legend123
## DNS: darksouls
## ISP_Router Secret: cisco
## enable permission: ccna
# Ljósleiparabox:
## Virtual line pass: ccna
## Fiber_switch pass: cisco og eða ccna
-
# Wireless Router0
## User: admin // Password: Mario
## IP: 145.1.2.1
## Sub: 255.255.255.252
## Default: 145.1.2.2
-
# Ljósleidarabox
## IP: 145.1.2.2
## Sub: 255.255.255.252

# Upplýsingar um SSH
## SSH: ssh -l erik 192.168.0.99
## PW: cisco
-
## SSH: ssh -l ges 192.168.0.168 (Því að siggi ssh user vildi ekki taka við password svo að við gerðum nýtt með Geir kennara.)
## PW: ges

# END
sys.exit([arg])

1. Switch Basics (Layer 2)
```
enable
configure terminal
hostname SW1
no ip domain-lookup
```
Check status:
```
show interfaces status
show running-config
```

⸻

2. VLANs
```
configure terminal
vlan 10
 name USERS
vlan 20
 name SERVERS
exit
```
Verify:
```
show vlan brief
```

⸻

3. Access Ports
```
configure terminal
interface f0/1
 switchport mode access
 switchport access vlan 10
 no shutdown
exit
```
Multiple ports:
```
interface range f0/1 - 10
 switchport mode access
 switchport access vlan 10
```

⸻

4. Trunk Ports
```
configure terminal
interface g0/1
 switchport mode trunk
 switchport trunk allowed vlan 10,20
 no shutdown
exit
```
Verify:
```
show interfaces trunk
```

⸻

5. Switch Management IP (SVI)
```
configure terminal
interface vlan 10
 ip address 192.168.10.2 255.255.255.0
 no shutdown
exit
ip default-gateway 192.168.10.1
```

⸻

6. Router Basics
```
enable
configure terminal
hostname R1
no ip domain-lookup
```
Interface:
```
interface g0/0
 ip address 192.168.1.1 255.255.255.0
 no shutdown
exit
```
Verify:
```
show ip interface brief
```

⸻

7. Router-on-a-Stick (Inter-VLAN Routing)
```
configure terminal
interface g0/0
 no shutdown
exit
```
VLAN subinterfaces:
```
interface g0/0.10
 encapsulation dot1Q 10
 ip address 192.168.10.1 255.255.255.0
exit

interface g0/0.20
 encapsulation dot1Q 20
 ip address 192.168.20.1 255.255.255.0
exit
```

⸻

8. DHCP on Router

Exclude gateways:
```
ip dhcp excluded-address 192.168.10.1 192.168.10.10
ip dhcp excluded-address 192.168.20.1 192.168.20.10
```
Pools:
```
ip dhcp pool VLAN10
 network 192.168.10.0 255.255.255.0
 default-router 192.168.10.1
 dns-server 8.8.8.8
exit
```
```
ip dhcp pool VLAN20
 network 192.168.20.0 255.255.255.0
 default-router 192.168.20.1
 dns-server 8.8.8.8
exit
```
Verify:
```
show ip dhcp binding
show ip dhcp pool
```

⸻

9. Static Routing

Default route:
```
ip route 0.0.0.0 0.0.0.0 192.168.1.254
```
Specific route:
```
ip route 10.0.0.0 255.255.255.0 192.168.1.2
```
Verify:
```
show ip route
```

⸻

10. PC Side (Packet Tracer)

DHCP

Desktop → IP Configuration → DHCP

Static
```
IP Address: 192.168.10.50
Subnet Mask: 255.255.255.0
Default Gateway: 192.168.10.1
DNS: 8.8.8.8
```

⸻

11. Verification Commands (Spam These)
```
ping 192.168.10.1
ping 192.168.20.1
ping 8.8.8.8

show vlan brief
show interfaces trunk
show ip interface brief
show running-config
```

⸻

12. Emergency Fix Checklist (aka “why isn’t it working”)
```
show interfaces status
show vlan brief
show ip route
show ip dhcp binding
```
Check for:
	•	Missing no shutdown
	•	Wrong VLAN
	•	Trunk not trunking
	•	Gateway mismatch
	•	DHCP network mismatch

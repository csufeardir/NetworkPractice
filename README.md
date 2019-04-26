# NetworkPractice
Practices on network configurations and topology schemas on Cisco's Packettracer software.

A network topology, calculated, set and configured as practice.
IPv4 and IPv6 addressings are included in both Packettracer modelling and tasks report.
Static Routing settings are manually configured.
Cisco's Packettracer software is used for modelling and network simulation.

Segment	Network Address	Network Mask	Range of IP Addresses	Broadcast Address	Default Gateway
VLAN B
(Private)	192.168.189.64	255.255.255.224	192.168.189.65
192.168.189.94	192.168.189.95	192.168.189.65
S1	85.121.128.0	255.255.255.248	85.121.128.1 
85.121.129.254	85.121.129.255	85.121.128.1
VLAN A	85.121.130.0	255.255.255.252	85.121.130.1
85.121.130.62	85.121.130.63	85.121.130.1
NAT	85.121.130.64	255.255.255.252	85.121.130.65
85.121.130.94	85.121.130.95	85.121.130.65
R1-R3	85.121.130.96	255.255.255.252	85.121.130.97
85.121.130.98	85.121.130.99	85.121.130.97
R1-R2	85.121.130.100	255.255.255.252	85.121.130.101
85.121.130.102	85.121.130.103	85.121.130.101
R1-ISP	10.0.0.0	255.255.255.252	10.0.0.1
10.0.0.2	10.0.0.3	10.0.0.1
IPv4 Addressing Scheme:


IPv6	Addressing	Scheme:
SEGMENT	Network address/mask	Range of IP address
Segment S1	2002:94e8:96ba:e000::0/64	2002:94e8:96ba:e000::0::1-2002:94e8:96ba:e000::0::FFFF
VLAN A	2002:94e8:96ba:e000::1/64	2002:94e8:96ba:e000::1::1-2002:94e8:96ba:e000::1::FFFF
VLAN B	2002:94e8:96ba:e000::2/64	2002:94e8:96ba:e000::2::1-2002:94e8:96ba:e000::2::FFFF
R1-R3	2002:94e8:96ba:e000::3/64	2002:94e8:96ba:e000::3::1-2002:94e8:96ba:e000::3::FFFF
R1-R2	2002:94e8:96ba:e000::4/64	2002:94e8:96ba:e000::4::1-2002:94e8:96ba:e000::4::FFFF
R1-ISP	2002:94e8:96ba:e000::5/64	2002:94e8:96ba:e000::5::1-2002:94e8:96ba:e000::5::FFFF

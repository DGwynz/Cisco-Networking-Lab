# Cisco-Networking-Lab

Hands-on Cisco networking labs built with Cisco Packet Tracer, covering VLANs, routing, DHCP, NAT/PAT, ACLs, OSPF, and network troubleshooting.



\# Cisco Networking Labs



A collection of hands-on networking labs built with \*\*Cisco Packet Tracer\*\*, focusing on fundamental networking, routing, network services, and security concepts.



These labs were created as part of my practical learning journey toward a career in \*\*Networking and Cybersecurity\*\*.



\---



\## About This Repository



This repository documents my hands-on practice with Cisco networking technologies and common network troubleshooting concepts.



The labs cover:



\- Network fundamentals

\- VLAN and Layer 2 switching

\- Inter-VLAN routing

\- Static and dynamic routing

\- DHCP and DNS

\- NAT/PAT

\- Access Control Lists (ACL)

\- Network troubleshooting

\- Basic packet analysis with Wireshark



Each lab includes the topology, configuration, verification steps, and key concepts where applicable.



\---



\## Labs



| # | Lab | Main Topics | Status |

|---|---|---|---|

| 01 | \[Inter-VLAN Routing - Router-on-a-Stick](./02-inter-vlan-router-on-a-stick/) | VLAN, Trunk, 802.1Q, Inter-VLAN Routing | Completed |

| 02 | \[Static Routing](./03-static-routing/) | Static Route, Routing Table, Next Hop | Completed |

| 03 | \[DHCP](./04-dhcp/) | DHCP Server, Address Pool, Default Gateway | Completed |

| 04 | \[NAT/PAT](./05-nat-pat/) | NAT, PAT, ACL, Address Translation | Completed |

| 05 | \[ACL](./06-acl/) | Standard ACL, Extended ACL, Traffic Filtering | Completed |

| 06 | \[OSPF](./07-ospf/) | Dynamic Routing, OSPF, Area 0, Neighbor Adjacency | Completed |



\---



\## Networking Skills Practiced



\### Network Fundamentals



\- OSI Model

\- TCP/IP Model

\- TCP and UDP

\- IPv4 Addressing

\- Subnetting

\- VLSM

\- ARP

\- MAC Addressing

\- Default Gateway



\### Switching



\- VLAN

\- Access Ports

\- Trunk Ports

\- IEEE 802.1Q

\- Broadcast Domains

\- Inter-VLAN Communication



\### Routing



\- Routing Tables

\- Static Routing

\- Dynamic Routing

\- OSPF

\- Next-Hop Routing

\- Longest Prefix Match



\### Network Services



\- DHCP

\- DNS fundamentals

\- NAT

\- PAT



\### Network Security



\- Standard ACL

\- Extended ACL

\- Source/Destination Traffic Filtering

\- Basic Network Security Concepts



\### Troubleshooting \& Analysis



\- `ping`

\- `tracert`

\- `ipconfig`

\- `nslookup`

\- `arp`

\- Cisco IOS `show` commands

\- Wireshark fundamentals

\- TCP/DNS/ARP packet analysis



\---



\## Tools



\- \*\*Cisco Packet Tracer\*\*

\- \*\*Cisco IOS\*\*

\- \*\*Wireshark\*\*

\- \*\*Windows Networking Tools\*\*

\- \*\*Git \& GitHub\*\*



\---



\## Verification Approach



For each lab, I use Cisco IOS verification commands and connectivity tests to confirm that the configuration works as expected.



Common commands include:



```cisco

show ip interface brief

show ip route

show vlan brief

show interfaces trunk

show access-lists

show ip ospf neighbor

ping


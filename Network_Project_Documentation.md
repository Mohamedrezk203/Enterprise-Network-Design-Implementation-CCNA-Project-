# Enterprise Network Design Project

This project demonstrates the design and implementation of a simulated enterprise network using Cisco Packet Tracer.

The goal of this project is to apply core CCNA networking concepts in a practical scenario including network segmentation, routing, security, and network services.

This project helped me strengthen my practical understanding of enterprise network design and prepare for real-world network engineering environments.

## Project Overview

The network simulates a small enterprise environment with multiple routers, multilayer switches, access switches, PCs, and servers.

The network infrastructure was designed to provide:

- Efficient traffic segmentation
- Secure communication
- Redundant paths
- Centralized network services
- Scalable routing architecture

## Network Topology

The network topology includes:

- 3 Routers
- 2 Multilayer Switches
- Multiple Access Switches
- PCs and Servers

The topology supports multiple VLANs and inter-network communication.

## Technologies Implemented

The following networking technologies were implemented in the project:

- VLAN Segmentation
- Trunking (802.1Q)
- Inter-VLAN Routing
- Dynamic Routing
- Spanning Tree Protocol (STP)
- EtherChannel
- NAT (Network Address Translation)
- DHCP (Dynamic Host Configuration Protocol)
- SSH Remote Access
- Access Control Lists (ACL)
- Port Security
- DHCP Snooping
- Dynamic ARP Inspection (DAI)

## VLAN Structure

The network was divided into several VLANs to simulate department separation.

Example VLANs:

VLAN 100 – Users  
VLAN 200 – Administration  
VLAN 300 – Servers  
VLAN 400 – Security  
VLAN 500 – IT Department  
VLAN 600 – Management

## Network Services

### DHCP
DHCP was configured to automatically assign IP addresses to client devices.

### NAT
NAT overload was configured on the edge router to allow internal devices to access external networks using a single public IP address.

### SSH
SSH was implemented to provide secure remote access to network devices.

## Network Security

Several security mechanisms were implemented including:

- Access Control Lists (ACLs)
- Port Security
- DHCP Snooping
- Dynamic ARP Inspection
- Secure device management using SSH

## Testing & Verification

Connectivity between devices was verified using:

- ping
- traceroute
- show commands

Example commands used for troubleshooting:

show ip route  
show vlan brief  
show interfaces trunk  
show spanning-tree  
show ip nat translations

## Tools Used

Cisco Packet Tracer

## Author

Mohamed Rezk  
Faculty of Engineering – Fayoum University  
Department of Communications & Electronics

# packet-tracer-labs
Cisco Packet Tracer labs covering network configuration, IP addressing, switching, and troubleshooting. CCNA study practice.
Cisco Network Infrastructure Lab: Basic Inter-VLAN Routing
Project Overview
This project demonstrates a fundamental network topology designed in Cisco Packet Tracer, focusing on routing between two distinct subnets using an ISR 4321 router and 3650 Layer 3 switches. The design showcases efficient IP address management and gateway configurations for small-to-medium enterprise environments.

Topology Diagram
Below is the polished logical representation of the network:

Network Configuration Details
1. Left Wing Subnet (VLAN 1)
Host (PC1):

IP Address: 192.168.1.1/24

Default Gateway: 192.168.1.126

Switch (S1 - 3650-24PS):

Management IP (VLAN1): 192.168.1.124/24

Gateway: 192.168.1.126

Router Interface (R1 - Gi0/0/0):

IP Address: 192.168.1.126/24

2. Right Wing Subnet (VLAN 1)
Host (PC2):

IP Address: 192.168.2.1/24

Default Gateway: 192.168.2.254

Switch (S2 - 3650-24PS):

Management IP (VLAN1): 192.168.2.122/24

Gateway: 192.168.2.254

Router Interface (R1 - Gi0/0/1):

IP Address: 192.168.2.254/24

Technical Features
Segmented Subnetting: Utilization of the 192.168.1.0/24 and 192.168.2.0/24 address spaces.

Layer 3 Switching: Implementation of Cisco 3650 series switches for robust local connectivity.

Centralized Routing: An ISR 4321 router (R1) serves as the primary gateway for cross-network communication.

Management Access: Configured Management IPs for all intermediate devices to facilitate remote administration.

Tools Used
Cisco Packet Tracer

Kali Linux (Host Environment)

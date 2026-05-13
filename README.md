# packet-tracer-labs

Cisco Packet Tracer labs covering network configuration, IP addressing, switching, and troubleshooting. CCNA study practice.

## Topology Diagram
![Network Topology](network_topology.png)

## Configuration Details
### Left Subnet (VLAN 1)
* **PC1 IP:** 192.168.1.1/24
* **PC1 Gateway:** 192.168.1.126
* **S1 Management IP:** 192.168.1.124/24

### Right Subnet (VLAN 1)
* **PC2 IP:** 192.168.2.1/24
* **PC2 Gateway:** 192.168.2.254
* **S2 Management IP:** 192.168.2.122/24

### Router (R1 - ISR4321)
* **Interface Gi0/0/0:** 192.168.1.126/24
* **Interface Gi0/0/1:** 192.168.2.254/24

## Environment
* **Platform:** Cisco Packet Tracer
* **OS:** Kali Linux

Small Computer Network Setup

This README outlines the basic steps to configure a small network consisting of switches, PCs, and a router. Below are the key configurations performed.

Network Setup Overview
Devices:
Switches: S1, S2, S3, S4
PCs: PC1, PC2, PC3, PC4
Router
IP Address Scheme:
Switches:
S1 (VLAN 1): 192.168.1.201/24
S2 (VLAN 1): 192.168.1.202/24
S3 (VLAN 1): 192.168.2.203/24
S4 (VLAN 1): 192.168.3.204/24
PCs:
PC1: 192.168.1.1/24
PC2: 192.168.1.2/24
PC3: 192.168.2.3/24
PC4: 192.168.3.4/24

Step-by-Step Configuration

1. Change Hostnames for Switches:
Rename switches to S1, S2, S3, and S4 using the hostname command.

3. VLAN 1 IP Address Configuration on Switches:
Configure the following IP addresses on VLAN 1 interfaces:
S1: 192.168.1.201/24
S2: 192.168.1.202/24
S3: 192.168.2.203/24
S4: 192.168.3.204/24

4. PC IP Address Assignment:
Assign IP addresses to the PCs:
PC1: 192.168.1.1/24
PC2: 192.168.1.2/24
PC3: 192.168.2.3/24
PC4: 192.168.3.4/24

# Basic-Switch-Configuration
This project features a simple network setup involving two Cisco switches and two hosts, It demonstrates how to configure essential switch settings such as hostname assignment, VLAN creation and allocation for traffic segmentation, access port setup for host connectivity, and establishing a link between the two switches for communication and security features 

## Overview

Simple Cisco switch configuration for a small lab network with two switches and two hosts. The setup demonstrates how to configure basic Layer 2 features, including VLAN creation

## Resources
  - 2 Switches
  - 2 End devices
  - Console cables
  - Ethernet cables
    
## Topology

- **Host A** and **Host B** are connected to **Switch 1** and **Switch 2**, respectively
- Both hosts are assigned to the same VLAN to enable communication.
- A trunk or access link connects the two switches

## Features

- Hostname configuration for each switch
- VLAN creation 
- Access ports configured for each host
- Basic inter-switch connection
- console line configuration
- Assigining password encryption services for the 2 switches
- Securing the console line 0 and vty interface 0 15 with a password (cisco) for each switch


## Configuration Summary

- **Switch 1**
  - VLAN 1 created and active (192.168.1.11/24, 255.255.255.0)
  - Port connecting to Host A is set as access and assigned to FastEthernet 1 with ip 192.168.1.1/24 (255.255.255.0)


- **Switch 2**
  - VLAN 1 created and active (192.168.1.12/24, 255.255.255.0)
  - Port connecting to Host B is set as access and assigned to FastEthernet 1 with ip 192.168.1.2/24 (255.255.255.0)
 

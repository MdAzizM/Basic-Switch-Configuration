# Basic-Switch-Configuration
This repository contains a basic configuration for a small network setup with two Cisco switches and two hosts. The configuration includes setting hostnames, creating and assigning a VLAN for proper segmentation, configuring access ports for each host, and ensuring inter-switch connectivity

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
 

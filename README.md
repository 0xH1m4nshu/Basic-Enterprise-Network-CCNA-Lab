# Basic Enterprise Network (CCNA Project)

## Overview

This project simulates a small enterprise network using VLAN segmentation, inter-VLAN routing, and access control lists (ACLs).

## Network Design

* VLAN 10 – HR (192.168.10.0/24)
* VLAN 20 – IT (192.168.20.0/24)
* VLAN 30 – Guest (192.168.30.0/24)

## Technologies Used

* VLANs (802.1Q)
* Inter-VLAN Routing (Router-on-a-Stick)
* Trunking
* ACL (Access Control List)

## Key Features

* Devices in different VLANs communicate via router
* Guest network is restricted from accessing HR network
* Successful segmentation and traffic control implemented

## Testing

* Verified inter-VLAN communication using ping
* Confirmed ACL blocks Guest → HR traffic

## Tools

* Cisco Packet Tracer

For Strick

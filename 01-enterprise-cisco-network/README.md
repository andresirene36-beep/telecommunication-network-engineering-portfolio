# ENTERPRISE CISCO NETWORK INFRASTRUCTURE

## Project Overview

This project involved the design, configuration, implementation, and troubleshooting of an enterprise-style network using physical Cisco routers and switches.

The network was structured into multiple VLANs to provide logical network segmentation for different departments and services. Routing, switching, network security, device management, and connectivity services were configured and tested across the infrastructure.

## Network Objectives

The main objectives of the implementation were to:

* Segment the network using VLANs.
* Provide communication between different VLANs through inter-VLAN routing.
* Configure trunk links between network devices.
* Provide IP addressing and DHCP services.
* Implement dynamic routing using OSPF.
* Provide Internet connectivity using NAT/PAT.
* Secure network access using ACLs and Layer 2 security features.
* Enable secure remote management using SSH.
* Implement STP protection mechanisms.
* Test and troubleshoot network connectivity and device operation.

## Network Architecture

The network uses a Cisco router and Cisco switches to provide routing, switching, VLAN segmentation, network security, and connectivity services.

The main network segments include:

| VLAN     | Department / Function |
| -------- | --------------------- |
| VLAN 10  | COICT         |
| VLAN 20  | COET                  |
| VLAN 30  | SALES                 |
| VLAN 40  | IT /ADMIN                   |
| VLAN 50  | SERVERS               |
| VLAN 89  | MANAGEMENT            |
| VLAN 100 | GUESTS                |

Each VLAN uses a dedicated IP subnet and default gateway.

## Technologies Implemented

### Switching

* VLAN configuration
* Access ports
* 802.1Q trunking
* Inter-switch connectivity
* STP/RPVST+
* PortFast
* BPDU Guard
* Port security
* DHCP Snooping

### Routing

* Inter-VLAN routing
* Router-on-a-Stick
* OSPF
* Static/default routing where required

### Network Services

* DHCP
* NAT/PAT
* SSH
* Network management
* SNMP

### Security

* Access Control Lists (ACLs)
* VLAN segmentation
* Management VLAN
* Port security
* DHCP Snooping
* STP protection
* Secure remote device management

## Implementation

The network was implemented using physical Cisco networking equipment.

VLANs were created to separate users, departments, management traffic, servers, and guest traffic. Trunk links were configured to carry multiple VLANs between the switching and routing infrastructure.

Inter-VLAN communication was implemented using Router-on-a-Stick, with separate router subinterfaces serving as default gateways for the VLANs.

DHCP services were configured to provide IP addressing information to end devices. OSPF was implemented for dynamic route exchange where required, while NAT/PAT was configured to provide Internet access for internal networks.

SSH was configured for secure remote management of network devices.

Layer 2 security mechanisms including STP/RPVST+, PortFast, BPDU Guard, Port Security, and DHCP Snooping were implemented to improve network protection and reduce common switching-related risks.

## Testing & Troubleshooting

Network connectivity and configuration were tested using Cisco IOS diagnostic and verification commands.

Testing included:

* VLAN membership verification
* Trunk status verification
* Inter-VLAN connectivity testing
* DHCP address assignment
* Routing table verification
* OSPF neighbor and route verification
* NAT translation testing
* ACL verification
* SSH connectivity testing
* STP and Layer 2 protection verification
* End-to-end connectivity testing

Troubleshooting was performed by analyzing device configuration, interface status, VLAN and trunk information, routing information, and connectivity test results.

## Engineering Skills Demonstrated

* Enterprise network design
* Cisco routing and switching
* VLAN segmentation
* Network troubleshooting
* Network security
* Routing protocol configuration
* Network services configuration
* Physical network device configuration
* Network testing and verification
* Secure network management

## Project Evidence

The following evidence will be added to this project:

* Network topology diagram
* VLAN design
* Cisco device configuration screenshots
* Routing and OSPF verification
* Trunk and VLAN verification
* NAT and ACL verification
* STP security configuration
* Connectivity testing
* Physical Cisco equipment photographs


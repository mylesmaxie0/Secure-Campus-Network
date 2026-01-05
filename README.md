# Three-Tier Enterprise Network Architecture

## Overview
This project showcases the design and deployment of a virtualized enterprise network using a three-tier hierarchical architecture. The network is built to demonstrate scalability, high availability, and security through industry-standard routing, redundancy, and firewall technologies commonly used in enterprise environments.

#

#### Architecture Overview

##### The network follows a traditional Core–Distribution–Access model to ensure modularity, fault isolation, and scalability.
- Access Layer
  - VLAN-based Layer 2 segmentation
  - Port security and access control enforcement
- Distribution Layer
  - Layer 3 inter-VLAN routing
  - Policy enforcement and route aggregation
- Core Layer
  - High-speed routing and backbone connectivity
  - Optimized for low latency and fast convergence

#

#### Routing and High Availability
- Dynamic Routing: OSPF implemented for scalable and efficient route propagation
- Gateway Redundancy: HSRP deployed to provide highly available default gateways
- Failover Design: Redundant paths ensure minimal disruption during device or link failures

#

#### Security Implementation
- Perimeter Security
  - Cisco ASA firewall with security zoning
  - Site-to-site IPsec VPN connecting headquarters and branch locations
- Layer 2 Security
  - Port security to mitigate unauthorized access
  - Access control policies for traffic filtering and segmentation

#

#### Network Services and Wireless
- Centralized DHCP and DNS services for efficient address and name resolution management
- Wireless LAN Controller (WLC) deployed to centrally manage wireless access points
- Secure and scalable wireless access integrated into the enterprise network


#### Network Topology
<img width="1728" height="1057" alt="Screenshot 2026-01-05 at 4 38 51 AM" src="https://github.com/user-attachments/assets/9ab6f067-bde4-4338-bca8-8b56633009a0" />


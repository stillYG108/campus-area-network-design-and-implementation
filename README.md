# Campus Area Network (CAN) Project

Welcome to the Campus Area Network simulation project. This document provides an overview of the project structure and how to navigate its contents.

## Project Overview

This project simulates a comprehensive campus area network (CAN) infrastructure for Martin Luther King University, spanning two campuses 100 miles apart with approximately 30,000 users across four faculties: Health & Sciences, Business, Engineering/Computing, and Art/Design. The network is designed to support anticipated growth with expected user doubling by 2025.

**Key Infrastructure Components:**
- **Dual Campuses** - Main campus (IT operations, server farm/DMZ) and branch campus
- **Security** - Cisco ASA 5500-X firewalls with security zones and IPsec VPN tunnel between campuses
- **Switching** - Catalyst 3850 core switches per campus, Catalyst 2960 faculty-level switches
- **Wireless** - Centralized WLC (main campus) managing lightweight access points across all departments
- **Servers** - Virtualized server farm (DHCP, DNS, FTP, Web, Email, SMTP) with redundancy
- **Connectivity** - Airtel ISP integration with Google Cloud platform access
- **VLANs** - Segmented networks (Management-10, LAN-20, WLAN-50, Blackhole-199)
- **Routing** - OSPF protocol with HSRP for high availability and redundancy

## Files & Structure

### Main Simulation File
- **campus area network.pkt** - Cisco Packet Tracer network simulation file containing the complete CAN topology and device configurations

## How to Use This Project

### Prerequisites
- Cisco Packet Tracer (version 8.0 or later recommended)
- Basic understanding of networking concepts (subnetting, routing, switching)

### Getting Started
1. Open Cisco Packet Tracer
2. Load the `campus area network.pkt` file
3. Review the network topology and device configurations
4. Use the simulation tools to test connectivity and network functionality

## Network Components

### Typical Campus Area Network Includes:
- **Core Switches** - Central switching infrastructure
- **Access Switches** - Building/floor level network access
- **Routers** - Inter-building and external connectivity
- **End Devices** - Computers, printers, and other network hosts
- **Wireless Access Points** - WiFi network coverage
- **Security Devices** - Firewalls and network security appliances

## Navigation Tips

- **Physical View** - Switch to Physical Workspace tab to see device locations
- **Logical View** - Switch to Logical Workspace tab to see network connections
- **Device Configuration** - Double-click devices to view and edit configurations
- **CLI Access** - Use the CLI tab on devices to enter commands
- **Simulation Mode** - Use the Simulation button to test network traffic and connectivity

## Testing & Validation

To verify network functionality:
1. Use the **Simulation Mode** to send test packets
2. Check device connectivity using **ping** and **tracert** commands
3. Review **routing tables** and **switching information**
4. Validate **VLAN** configurations and assignments

## Troubleshooting

- Ensure all devices are powered on
- Verify cable connections are properly made
- Check IP addressing and subnet masks
- Review routing configurations on routers
- Validate access lists and firewall rules if implemented

## Documentation Standards

When modifying this network:
- Document all IP addressing schemes used
- Maintain clear naming conventions for devices
- Record configuration changes made
- Keep track of VLAN assignments

## Support Resources

- Cisco Packet Tracer Help Documentation
- Cisco Learning Network
- Official Cisco Documentation

---

**Last Updated:** 2026-06-17  
**Project Status:** In Development

# LAB 01 — Basic LAN Deployment

## Project Overview

**Company:** NovaTech (Fictional Company)  
**Project Type:** Local Area Network (LAN) Deployment  
**Environment:** Cisco Packet Tracer  
**Difficulty:** Beginner  
**Role:** Junior Network Technician

### 1. Business Context

NovaTech is a small IT services company that has recently moved into new office premises. The company is organized into three departments: Administration, Technical Support, and Management.

As part of the relocation, NovaTech needs to establish its first internal network infrastructure to enable reliable communication between employees and support future business operations.

Currently, the office has no operational network infrastructure. The IT department has therefore assigned a junior network technician to design, deploy, configure, and validate a basic Local Area Network (LAN).

The proposed infrastructure must be simple, functional, documented, and capable of supporting future network improvements.

### 2. Project Objectives

The primary objective of this laboratory is to deploy a functional IPv4-based local area network using Cisco networking equipment.

The implementation must meet the following requirements:

- Establish physical connectivity between all network devices.
- Configure a Cisco router and switch within the network topology.
- Assign static IPv4 addresses to the three workstations.
- Configure the router as the default gateway for the local network.
- Ensure successful communication between all workstations.
- Verify network connectivity using ICMP echo requests (`ping`).
- Observe packet exchanges using Cisco Packet Tracer's Simulation Mode.
- Document the network architecture, configurations, and test results.

### 3. Technical Specifications

The network must be implemented using the following equipment:

| Device | Model | Quantity |
|---|---|---|
| Router | Cisco 2911 | 1 |
| Switch | Cisco 2960 | 1 |
| Workstation | PC-PT | 3 |
| Ethernet Cable | Copper Straight-Through | 4 |

**Network addressing requirements:**

| Device | IPv4 Address |
|---|---|
| Router (LAN Interface) | 192.168.10.1 |
| PC-ADMIN | 192.168.10.10 |
| PC-TECH | 192.168.10.20 |
| PC-DIR | 192.168.10.30 |

- **Network:** `192.168.10.0/24`
- **Subnet Mask:** `255.255.255.0`
- **Default Gateway:** `192.168.10.1`
- **Address Assignment:** Static IPv4
- **Network Scope:** Single Local Area Network
- **Internet Connectivity:** Not required

### 4. Project Constraints

The implementation must comply with the following constraints:

- All workstations must belong to the same IPv4 subnet.
- IP addressing must be configured manually without using DHCP.
- The router's LAN interface must be configured and enabled through the Cisco CLI.
- Workstations must communicate over the local network.
- The network must operate without an external Internet connection.
- Network configurations and connectivity tests must be documented.

### 5. Expected Deliverables

At the end of this laboratory, the following deliverables are expected:

1. A fully functional Cisco Packet Tracer topology (`.pkt`).
2. A network diagram showing device connections and addressing.
3. A complete IPv4 addressing table.
4. The Cisco router configuration.
5. Connectivity test results demonstrating successful communication.
6. Technical documentation explaining the implementation and validation process.

### 6. Learning Outcomes

By completing this laboratory, the following technical skills are practiced:

- Basic LAN design and network topology implementation.
- Cisco Packet Tracer device configuration.
- IPv4 addressing and subnet fundamentals.
- Cisco IOS command-line interface navigation.
- Router and switch fundamentals.
- Ethernet connectivity and network troubleshooting.
- ICMP connectivity testing and packet analysis.
- Technical documentation and network project organization.

---

**Project Note:** This laboratory is part of a personal networking homelab portfolio. NovaTech is a fictional company, and the scenario is designed to simulate a real-world entry-level network deployment assignment.

## Note sur l'IA // AI Disclosure
L'IA à veiller à la création du scénario et des contraintes de l'exercice.

AI was used to develop the exercise scenario and define its technical constraints.

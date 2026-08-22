# OSPF Failover & Redundant Enterprise Network

## Overview

This project demonstrates the design and implementation of a redundant enterprise network using Cisco Packet Tracer and the OSPF (Open Shortest Path First) dynamic routing protocol.

The network is designed with multiple routing paths to provide redundancy and maintain connectivity during a network link failure. OSPF dynamically detects the topology change, recalculates the available route, and redirects traffic through the alternate path.

The objective of this project is to strengthen practical networking skills through hands-on OSPF configuration, redundant network design, failover testing, routing verification, and end-to-end connectivity testing.

---

## 📸 Project Screenshots

### 1. Network Topology

![Network Topology](screenshots/01-topology.png)

---

### 2. OSPF Neighbor Relationship

![OSPF Neighbor Relationship](screenshots/02-ospf-neighbors.png)

---

### 3. Routing Table Before Failure

![Routing Table Before Failure](screenshots/03-routing-before-failure.png)

---

### 4. Link Failure Simulation

![Link Failure](screenshots/04-link-failure.png)

---

### 5. OSPF Failover Routing

![OSPF Failover Routing](screenshots/05-failover-routing.png)

---

### 6. End-to-End Connectivity Testing

![Connectivity Testing](screenshots/06-connectivity-testing.png)
---

## Network Topology

- 4 Cisco Routers
- 2 Cisco 2960 Switches
- 2 PCs
- Multiple IPv4 Networks
- Redundant Routing Paths
- OSPF Area 0
- Point-to-Point /30 Networks
- LAN /24 Networks

---

## Technologies Used

- Cisco Packet Tracer
- OSPF (Open Shortest Path First)
- IPv4 Addressing
- Subnetting
- Wildcard Masks
- Dynamic Routing
- Routing Redundancy
- Network Failover
- Cisco IOS
- Routing & Switching

---

## Features

- Redundant enterprise network topology
- IPv4 addressing configuration
- OSPF Area 0 implementation
- OSPF neighbor establishment
- Dynamic route learning
- Redundant routing paths
- Primary link failure simulation
- Automatic OSPF failover
- Alternate path selection
- Routing table verification
- End-to-end connectivity testing
- Network recovery and troubleshooting
- Cisco IOS configuration

---

## Verification Commands

show ip interface brief

show ip ospf neighbor

show ip route

show ip protocols

show ip ospf interface brief

show running-config

ping

tracert

---

## Failover Testing

The primary routing path was intentionally interrupted to simulate a network link failure.

After the failure, OSPF detected the topology change and recalculated the available routes. Traffic was automatically redirected through the alternate routing path.

The network was then restored and OSPF neighbor relationships were verified again.

This demonstrates how dynamic routing and redundant paths can maintain network connectivity during link failures.

---

## Project Outcome

Successfully designed and configured a redundant enterprise network using OSPF dynamic routing.

The project demonstrated OSPF neighbor establishment, dynamic route learning, routing redundancy, primary link failure simulation, automatic failover, alternate path selection, and end-to-end connectivity verification.

Network behavior was verified using OSPF neighbor states, routing tables, ping, and traceroute.

---

## Learning Outcomes

- Enterprise Network Design
- IPv4 Addressing
- Subnetting and Wildcard Masks
- OSPF Configuration
- OSPF Neighbor Adjacency
- Dynamic Routing
- Routing Redundancy
- Network Failover
- Cisco IOS CLI
- Routing Table Verification
- Network Troubleshooting
- Ping and Traceroute Analysis
- CCNA Practical Skills

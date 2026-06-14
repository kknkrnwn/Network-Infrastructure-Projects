# JNA Network Topology Design

A network topology simulation project developed as part of the **Junior Network Administrator (JNA)** practical assignment. This project demonstrates the implementation of IP addressing, subnetting, router-to-router connectivity, wireless configuration, and basic network validation using Cisco Packet Tracer.

## 📌 Project Overview

The network consists of three interconnected buildings (Building A, Building B, and Building C) with dedicated servers, routers, client devices, and wireless access points. The objective is to establish reliable communication between all network segments while maintaining proper IP addressing and routing configuration.

## ✨ Features

* Multi-building network topology
* IPv4 addressing and subnetting
* Router-to-router connectivity
* Static routing configuration
* Wireless Access Point configuration
* WPA2-PSK wireless security
* End-to-end network connectivity testing

## 🛠️ Technologies Used

* Cisco Packet Tracer
* IPv4 Addressing
* Subnetting
* Static Routing
* Wireless Networking
* Network Troubleshooting

## 📂 Project Structure

```text
jna-network-topology/
│── README.md
│
├── docs/
│   └── project-documentation.pdf
│
├── packet-tracer/
│   └── network-topology.pkt
│
├── topology/
│   └── topology.png
│
└──  configs/
    ├── router-a.txt
    ├── router-b.txt
    ├── router-c.txt
    └── access-point.txt

```

## 🌐 Network Architecture

The simulated network consists of:

* Building A

  * Data Server
  * Email Server

* Building B

  * PCs
  * Laptop
  * Mobile Device
  * Wireless Access Point

* Building C

  * PCs
  * Laptop
  * Mobile Device
  * Wireless Access Point

The buildings are interconnected through routers with dedicated point-to-point links.

## 🔒 Wireless Security

* Security Mode: WPA2-PSK
* Authentication: Pre-Shared Key (PSK)

## ✅ Validation

Network validation includes:

* Router connectivity verification
* End-to-end ping testing
* IP addressing verification
* Wireless connectivity testing
* Routing validation

## 📖 Learning Outcomes

Through this project, I gained practical experience in:

* Network topology design
* IPv4 addressing and subnetting
* Router configuration
* Static routing
* Wireless network deployment
* Network troubleshooting
* Connectivity validation

## 🚀 Future Improvements

* Dynamic Routing (OSPF/RIP)
* VLAN implementation
* DHCP Server
* DNS Server
* Network monitoring
* Firewall configuration
* Access Control Lists (ACL)

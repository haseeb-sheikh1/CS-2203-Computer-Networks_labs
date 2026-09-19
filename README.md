# 🌐 CS-2203: Computer Networks Lab Portfolio

**Course Details**
* **Course:** Computer Networks (CS-2203)
* **University:** The University of Azad Jammu & Kashmir, Muzaffarabad
* **Department:** Department of Software Engineering
* **Instructor:** Engr. Dr. Asma Javed
* **Student:** Haseeb Sheikh (Roll Number: 2024-SE-31)

This repository contains documentation, hardware topology designs, and execution logs for the Computer Networks laboratory course. The portfolio encompasses network simulation using Cisco Packet Tracer 9.0.0, physical OSI layer cabling techniques, and Cisco IOS Command Line Interface (CLI) configuration for routing and switching infrastructure.

---

## 📂 Laboratory Index & Core Concepts

| Lab | Title & Primary Objective | Key Technologies & Concepts |
| :--- | :--- | :--- |
| **Lab 01** | **Packet Tracer Installation** <br> Successfully install Cisco Packet Tracer 9.0.0 (64-bit) on a Windows operating system and verify the workspace. | Cisco Packet Tracer 9.0.0 Setup, EULA, Workspace Verification. |
| **Lab 02** | **Exploring Packet Tracer Interface** <br> Familiarize with workspace views, the device selection library, and operational testing modes. | Logical vs. Physical Workspace, Realtime vs. Simulation Modes, Device Library. |
| **Lab 03** | **Creation of Network Topology** <br> Create a simple LAN using a switch, assign static IP addresses, and verify connectivity. | LAN, Static IPv4, `ping`, `tracert`, `arp -a`, `netstat`. |
| **Lab 04** | **Physical Layer of the OSI Model** <br> Manually terminate an Ethernet cable and verify physical connectivity using a network tester. | UTP Cable (Cat 5/6), RJ45 Connectors, T568B Wiring Protocol, Cable Crimping. |
| **Lab 05** | **Simulating a Star Topology Network** <br> Construct a star topology using a central Cisco 2960 switch and six PCs to observe packet forwarding. | Star Topology, Cisco 2960 Switch, MAC Address Table Lookup, ICMP Simulation. |
| **Lab 06** | **Switch Communication Between Two LANs** <br> Establish communication between two separate subnets using a central router to route traffic. | Subnetting (192.168.1.0 & 192.168.2.0), Default Gateways, Router Interfaces. |
| **Lab 07** | **Basic Switch CLI Commands** <br> Establish a local console connection to navigate operational modes and apply initial device configurations. | Rollover Cable, User EXEC, Privileged EXEC, Global Configuration, `show version`, `hostname`. |
| **Lab 08** | **Router Access and CLI Configuration** <br> Access the router CLI to apply basic security settings and manage configuration files. | `enable secret`, `service password-encryption`, NVRAM (`copy running-config startup-config`). |
| **Lab 09** | **Switching and ARP** <br> Observe dynamic MAC address table behavior during data transmission and manage switch memory. | Address Resolution Protocol (ARP), Dynamic MAC Learning, `clear mac address-table`. |
| **Lab 10** | **Inter-VLAN Routing** <br> Separate network traffic into Development (VLAN 10) and HR (VLAN 20) and configure Router-on-a-Stick. | VLAN Creation, 802.1Q Trunk Ports, Router Subinterfaces, Inter-VLAN Routing. |

---

## 🚀 Execution Instructions
1. Ensure **Cisco Packet Tracer 9.0.0 (64-bit)** is installed locally with at least 715.0 MB of free disk space. 
2. Open the respective `.pkt` (Packet Tracer) files provided for Labs 03 through 10 to interact with the designed topologies.
3. For CLI verification, click on the networking devices (Routers/Switches), navigate to the **CLI** tab, and enter Privileged EXEC mode (`enable`) to execute configuration and verification commands (`show running-config`, `show mac address-table`).
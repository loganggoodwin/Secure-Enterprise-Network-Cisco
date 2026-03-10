# Secure Enterprise Campus Network 🛡️
**Architecting a Resilient, Multi-Layered Infrastructure in Cisco Packet Tracer**

## 📌 Project Overview
Developed as part of my **MS in Cybersecurity** curriculum at SNHU, this project demonstrates the design and implementation of a secure, scalable campus network. It utilizes a **Collapsed Core Architecture** to balance performance with redundancy, ensuring high availability and robust security at every layer.

## 🏗️ Technical Architecture
* **Topology:** Collapsed Core (Distribution and Core functions merged).
* **Segmentation:** VLAN-based isolation for Users, Servers, Printers, Guest, DMZ, and Management.
* **Routing:** Inter-VLAN routing with redundant links.
* **Hardware:** Cisco Catalyst Switches, ISR Routers, and Cisco ASA 5505 Firewall.

## 🔒 Security Implementations (Defense in Depth)
This project moves beyond simple connectivity by enforcing strict security protocols:

* **ASA Firewall DMZ:** Isolated public-facing services from the internal trusted network using specific security levels.
* **Access Control Lists (ACLs):** Extended ACLs implemented to ensure Guest network isolation and restrict administrative access (SSH/VTY).
* **Layer 2 Hardening:** * **Port Security:** Sticky MAC address filtering to prevent unauthorized hardware access.
    * **DHCP Snooping:** Mitigating rogue DHCP server attacks.
    * **STP Security:** BPDU Guard enabled on access ports to maintain loop-free topology integrity.
* **Secure Management:** Disabling telnet in favor of SSH and encrypted console access.

## 🛠️ Tools & Technologies
* **Cisco Packet Tracer** (Simulation & Validation)
* **Cisco IOS** (Configuration & Hardening)
* **Subnetting:** VLSM for optimized IP address allocation.

## 📂 Repository Contents
* `/Lab-Files`: The `.pkt` source file for the network.
* `/Documentation`: Technical design documents and the Security Policy rubric.
* `/Screenshots`: Topology diagrams and verification ping/trace tests.

---
### 👨‍💻 About Me
**Logan Garth Goodwin** *MS Cybersecurity Student | CompTIA A+ & Network+ Certified* [LinkedIn Profile](INSERT_YOUR_LINKEDIN_URL_HERE) | [Portfolio Site](https://loganggoodwin.github.io)

# Network-Design-of-Bank

# 🏦 Bank Network Design – 4 Floors (VLAN-Based Architecture)

## 📘 Project Overview

This project presents a secure and scalable network infrastructure for a multi-floor bank, based on the **Three-Layer Hierarchical Model** (Access – Distribution – Core). Each floor is segmented using VLANs to enhance traffic isolation and security.

- **VLAN 10** – Public Services (Floor 1)  
- **VLAN 20** – Employees (Floor 2)  
- **VLAN 30** – Server Room (Floor 3)  
- **VLAN 40** – Management & Vault (Floor 4)

---

## 🧱 Network Architecture

- **Access Layer**: End-device connectivity via access switches  
- **Distribution Layer**: Two multilayer switches to ensure **redundancy** and dynamic routing  
- **Core Layer**: Includes:
  - **ASA Firewall** for network protection  
  - **ISP Router** for internet access  
  - **Cloud connectivity** for data backup and scalability  

---

## 🔐 Technologies & Protocols

- **OSPF** – For dynamic Layer 3 routing  
- **HSRP** – High availability between distribution switches  
- **EtherChannel** – Link aggregation for performance and fault tolerance  
- **ASA Firewall** – Securing core access  
- **Cloud Integration** – Remote data storage and backup  

---

## ✅ Key Features

- Scalable and modular design  
- VLAN-based segmentation per floor  
- Redundant links to prevent failure  
- Firewall-secured core network  
- Cloud-ready for data resilience  

---

## 📂 Included Files

- Network topology (.gns3 )  
- Device configurations  
- Network diagrams  
- Documentation (README)

---
 

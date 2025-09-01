# Enterprise-Network-Security-GNS3

## 📌 Project Overview
This repository contains the design and implementation of a **secure enterprise network** using **GNS3** and **FortiGate firewalls**, completed during a **2-month internship at 3S (Standard Sharing Software)**.  
The goal of this project was to simulate a realistic corporate infrastructure with secure connectivity, segmentation, and high availability features.

---

## 🏢 Network Architecture
The simulated enterprise network includes:

- **Headquarters (HQ):**
  - Multiple VLANs for HR, IT, and Finance
  - FortiGate firewall as the central security gateway
  - DMZ hosting Web and FTP servers
  - Load balancer distributing traffic across DMZ web servers

- **Branches:**
  - **Branch 1:** FortiGate firewall with IPsec site-to-site VPN tunnel to HQ
  - **Branch 2:** FortiGate firewall with dual WAN links configured for SD-WAN

- **Backbone & Internet Simulation:**
  - Cisco routers with OSPF providing dynamic routing
  - NAT for external Internet connectivity

---

## 🔐 Security Features Implemented
- **Firewall Policies:** Controlled access between VLANs, DMZ, and external networks  
- **Site-to-Site VPN (IPsec):** Secure communication between HQ and Branch 1  
- **SD-WAN:** Intelligent traffic steering across dual WAN links at Branch 2  
- **SNAT & DNAT:** Address translation for internal and external services  
- **Load Balancing:** High availability for DMZ web servers  
- **Segmentation:** VLANs isolating HR, IT, and Finance departments  

---

## 📸 Screenshots
| Component            | Screenshot |
|----------------------|------------|
| Full Network Topology | ![Topology](infra.png) |
| HQ Interfaces (VLANs & DMZ) | ![HQ](HQ.png) |
| VPN Tunnel Status | ![VPN](vpn.png) |
| SD-WAN Dashboard | ![SD-WAN](sdwan.png) |

---

## 🛠️ Tools & Technologies
- **GNS3** (network simulation)  
- **FortiGate (FortiOS 7.0.5)**  
- **Cisco IOS Routers (OSPF backbone)**  
- **Web & FTP Servers (DMZ services)**  

---

## 🚀 Key Outcomes
- Successfully designed and implemented a **secure enterprise network** in a simulated environment  
- Gained hands-on experience with **FortiGate firewalls, VPNs, SD-WAN, and load balancing**  
- Strengthened knowledge of **network security, routing, and enterprise IT infrastructure**  

---

## 📂 Repository Contents
- `infra.png` → Network topology diagram  
- `HQ.png` → FortiGate HQ interfaces and VLANs  
- `vpn.png` → VPN tunnel status  
- `sdwan.png` → SD-WAN monitoring dashboard  

---

## 🙌 Acknowledgment
This project was completed during my internship at **3S (Standard Sharing Software)**.  
Special thanks to my mentors and the team for their guidance throughout this journey.  

---

## 🔖 License
This project is for **educational purposes** and lab simulations only.  
Not intended for production use.

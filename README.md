# 🏢 Company Network Design and Simulation using Cisco Packet Tracer

**Author:** Aarti Sakpal (Roll No: 23102A0007)  
**Department:** Computer Engineering, Vidyalankar Institute of Technology  
**Subject:** Computer Networks – Mini Project  

---

## 📖 Project Overview
This project demonstrates the **design and simulation of a company-wide network** using **Cisco Packet Tracer**.  
The network is divided into multiple departments (floors) with VLANs, secure firewalls, DMZ servers, and remote access for international users.

---

## 🎯 Objectives
- Divide the network into departments using VLANs  
- Enable safe inter-department communication  
- Host internal Web, FTP, and Email servers  
- Protect internal resources using ASA firewalls  
- Provide controlled external access through DMZ  
- Enable remote access from countries like the USA and China  
- Test full network functionality through simulation  

---

## 🧰 Tools & Technologies Used
- **Simulator:** Cisco Packet Tracer  
- **Languages:** HTML (for company website)  
- **Protocols:**  
  - HTTP – for web communication  
  - FTP – for internal file sharing  
  - DNS – for domain name resolution  
  - TCP/IP – for communication  
  - DHCP – for automatic IP assignment  

---

## 🏗️ Network Design Overview
### 🏬 Floor Layout
- **1st Floor:** Sales & Marketing, HR & Logistics  
- **2nd Floor:** Finance & Admin  
- **3rd Floor:** Technical Department & Wireless Area  

### 🔐 Security Zones
- **DMZ Servers:** Web, FTP, Email, DNS, DHCP  
- **Internal LAN:** Company departments with VLAN segmentation  
- **Firewalls:** Dual ASA firewalls to protect internal network  

### 🌍 Remote Access
- Remote users from **USA** and **China** can securely access web and email servers.  
- Internet access is simulated via an ISP router.  

---

## 🧾 IP Addressing Scheme

| Network Area          | IP Address/Subnet     |
|-----------------------|-----------------------|
| Internal LAN          | 192.168.10.0/24       |
| DMZ Servers           | 10.11.11.0/27         |
| Remote Users          | 8.0.0.0/8             |
| ISP / Firewall Links  | 20.0.0.0/30 and others |
| VLAN Interfaces       | 172.16.x.x/16 (per VLAN) |

---

## ✅ Results
- Successful inter-VLAN communication  
- Working Web, FTP, and Email servers  
- Wireless connectivity on 3rd floor  
- Firewall blocking of unauthorized access  
- Remote users successfully connected via ISP  

---

## 🧩 Files Included
| File | Description |
|------|--------------|
| `company NETWORK.pkt` | Main Cisco Packet Tracer topology file |
| `CN_Mini_Project_Report.pdf` | Detailed project documentation |

---

## 🎥 Reference Video
This project was created with the help of the following video tutorial:  
🔗 [Design a Company Network in Cisco Packet Tracer](https://www.youtube.com/watch?v=Cbv95OxT1FM&t=8988s)

---

## 🎬 Project Demo

Watch the full demo of the network simulation here:  
[![Project Demo](https://github.com/AARTI756/company-network/blob/main/company%20network.mp4)]


<img width="1698" height="706" alt="Screenshot 2025-12-10 232213" src="https://github.com/user-attachments/assets/3089c5d0-e6d7-40c3-8652-8f9e05320379" />
<img width="1917" height="712" alt="image" src="https://github.com/user-attachments/assets/ea0bfbfb-3384-43fc-85cf-7a117138635d" />
<img width="1852" height="704" alt="image" src="https://github.com/user-attachments/assets/5dd57601-2f71-4806-ba29-dceb2fc2ad11" />

----

## 📚 References
- Cisco Packet Tracer Documentation  
- Cisco Networking Academy Materials  
- Cisco VLAN & Firewall Configuration Guides  

---

> 💡 **How to Open**
> 1. Open `company NETWORK.pkt` using **Cisco Packet Tracer v8.2 or later**.  
> 2. Explore VLANs, servers, and firewalls.  
> 3. Use simulation mode to test pings and connections.

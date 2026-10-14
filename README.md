<div align="center">

  <!-- Professional Datacenter & Enterprise Network Header -->
  <img src="https://images.unsplash.com/photo-1558494949-ef010cbdcc31?auto=format&fit=crop&w=1400&q=80" alt="Enterprise Network Infrastructure" width="100%" style="border-radius: 12px; box-shadow: 0px 6px 24px rgba(0,0,0,0.5); margin-bottom: 20px;" />

  # ⚡ AHMED KHALID SAMIR ⚡
  ### **NETWORK ENGINEER // ENTERPRISE INFRASTRUCTURE & SECURITY**
  
  <p><i>Designing, Configuring & Troubleshooting Reliable Network Infrastructure</i></p>

  <p align="center">
    <a href="#about">About</a> • 
    <a href="#skills">Skills</a> • 
    <a href="#topology">Topology</a> • 
    <a href="#labs">Labs</a> • 
    <a href="#certifications">Certifications</a> • 
    <a href="#tools">Tools</a> • 
    <a href="#contact">Contact</a>
  </p>

  <p align="center">
    <a href="mailto:ahmedkhalid301967@gmail.com"><img src="https://img.shields.io/badge/Email-ahmedkhalid301967%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
    <a href="tel:01026764586"><img src="https://img.shields.io/badge/Phone-+20_1026764586-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" /></a>
    <a href="https://linkedin.com/in/AhmedKhaledSamir" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
    <img src="https://img.shields.io/badge/Status-Available_for_Enterprise_Roles-00C853?style=for-the-badge&logo=cisco&logoColor=white" />
  </p>

</div>

---

<div id="about"></div>

## 📌 `whoami` // Background & Engineering Focus

I am a dedicated **Network Engineer** specialized in enterprise network architecture design, enterprise routing & switching, network optimization, and zero-trust infrastructure security. My engineering mindset is built on first-principles protocol understanding and hands-on lab validation.

I design and manage reliable campus, enterprise WAN, and datacenter networks. My background encompasses configuring high-availability Cisco hardware, optimizing dynamic routing protocols (OSPF, BGP), isolating Layer 2 and Layer 3 bottlenecks, and enforcing infrastructure security through ACLs, NAT, and Firewalls.

* 🏗️ **Architecture:** Hierarchical & Modular Enterprise Campus Design
* 🔍 **Troubleshooting:** Deep Packet Analysis using Wireshark & Cisco Packet Tracer
* 🛡️ **Security:** Network Hardening, Standard/Extended ACLs, NAT/PAT, and Zero-Trust Edge Policies

---

## 📊 GitHub Performance & Metrics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=AhmedKhaledSamir&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Ahmed's GitHub Stats" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AhmedKhaledSamir&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="48%" />
</p>

---

<div id="skills"></div>

## 🛠️ Technical Competencies & Protocol Matrix

<div align="center">

| Engineering Domain | Core Technologies & Protocols |
| :--- | :--- |
| **Network Fundamentals** | OSI 7-Layer Model, TCP/IP Suite, LAN / WAN, Leased Lines, DSL, Architecture |
| **IP Addressing** | IPv4, IPv6, Subnetting (FLSM / VLSM), CIDR, MAC Addressing |
| **Cisco IOS & Admin** | CLI Navigation, Password Recovery, Software Recovery, IOS Backup/Upgrade, Hardware Arch |
| **Switching (L2/L3)** | VLANs, 802.1Q Trunking, Inter-VLAN Routing, Router-on-a-Stick, STP / RSTP, EtherChannel (LACP) |
| **Routing Protocols** | IPv4/IPv6 Static Routing, OSPF (Single-Area), Basic BGP, HSRP / VRRP Redundancy |
| **Enterprise & WAN** | Enterprise Architecture, WLAN Wireless, SD-WAN Concepts, QoS, Network Virtualization |
| **Network Services** | DHCP Server & Relay (IP Helper), Static/Dynamic NAT, PAT (Overload), DNS, NTP |
| **Security & Hardening** | Standard & Extended ACLs, Named ACLs, Port Security, Enterprise Network Hardening |
| **Automation & Tools** | Python Scripts, REST APIs, JSON / YAML Data Formats, Device Automation |
| **Troubleshooting & Ops** | Wireshark Packet Analysis, Cisco Packet Tracer, GNS3, Protocol Analyzers |

</div>

### 🌐 Technology Stack Badges
<p align="center">
  <img src="https://img.shields.io/badge/Cisco-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white" />
  <img src="https://img.shields.io/badge/Routing_%26_Switching-2E8B57?style=for-the-badge&logo=letsencrypt&logoColor=white" />
  <img src="https://img.shields.io/badge/Wireshark-165181?style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/GNS3-2E2E2E?style=for-the-badge&logo=gns3&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

---

<div id="topology"></div>

## 📐 Enterprise Network Topology Flow

<div align="center">

```text
  +-----------------------------------------------------------------------+
  |                          WAN / Internet (eBGP)                        |
  +-----------------------------------------------------------------------+
                                      |
                           [ Edge Router / NAT / PAT ]
                                      |
                     +---------------------------------+
                     |   Core Layer (HSRP / OSPF)      |
                     |   [L3 Switch 1] <---> [L3 Switch 2]|
                     +---------------------------------+
                                      |
            +-------------------------+-------------------------+
            | (802.1Q Trunk / LACP)                             | (802.1Q Trunk / LACP)
  +-------------------+                               +-------------------+
  | Access Switch A   |                               | Access Switch B   |
  +-------------------+                               +-------------------+
    |               |                                   |               |
[VLAN 10]       [VLAN 20]                           [VLAN 30]       [VLAN 99]
 (Admin)         (Staff)                             (Servers)       (MGMT)

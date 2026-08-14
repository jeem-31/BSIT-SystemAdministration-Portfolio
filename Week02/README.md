# Enterprise Infrastructure Planning for a Startup Company
**Course:** ITEP 414 – System Administration and Maintenance  
**Institution:** Laguna State Polytechnic University (LSPU)  
**Instructor:** John Randolf M. Penaredondo, MIT  
**Student Name:** [Your Full Name Here]  
**Program:** Bachelor of Science in Information Technology (BSIT)  

---

## 📋 Table of Contents
- [Project Overview](#-project-overview)
- [Learning Objectives](#-learning-objectives)
- [Company Scenario](#-company-scenario)
- [Hardware Inventory Summary](#-hardware-inventory-summary)
- [Software Inventory Summary](#-software-inventory-summary)
- [Enterprise Network Diagram](#-enterprise-network-diagram)
- [Technologies Used](#-technologies-used)
- [Challenges Encountered](#-challenges-encountered)
- [Reflection](#-reflection)
- [References](#-references)

---

## 📌 Project Overview
This portfolio project focuses on planning and designing the complete IT infrastructure for a newly established software development startup, **ABC Startup Solutions**. As a Junior System Administrator, the goal is to evaluate business needs, select appropriate hardware and software, build network security policies, design a network topology, and document everything professionally prior to procurement.

---

## 🎯 Learning Objectives
- **Analyze** organizational IT requirements based on departmental headcount and roles.
- **Prepare** professional hardware, software, and network equipment inventories.
- **Design** a secure enterprise network topology using standard networking principles.
- **Create** professional technical documentation formatted in Markdown.
- **Understand** the core roles, tools, and collaboration within an IT Operations team.

---

## 🏢 Company Scenario
**Company Name:** ABC Startup Solutions  
**Nature of Business:** Software Development & Custom Tech Solutions  
**Office Location:** 5th Floor, Tech Innovation Tower, Laguna Technopark, Biñan, Laguna, Philippines  

### Vision
To become a leading provider of innovative, reliable, and scalable software solutions for businesses in Southeast Asia.

### Mission
To empower organizations through custom-built software applications while maintaining high standards of system availability, data security, and operational efficiency.

### Employee Distribution
| Department | Headcount | Key Functions |
| :--- | :---: | :--- |
| **Information Technology** | 5 | Infrastructure management, software development, system maintenance, tech support |
| **Human Resources** | 4 | Recruitment, employee relations, payroll support, onboarding |
| **Finance** | 5 | Financial planning, accounting, billing, payroll processing |
| **Sales** | 6 | Client acquisition, business development, account management |
| **TOTAL** | **20** | **Full Office Workforce** |

---

## 💻 Hardware Inventory Summary

| Asset ID | Hardware Description | Qty | Department | Purpose / Justification |
| :--- | :--- | :---: | :--- | :--- |
| **HW-DESK-01** | High-Performance Workstation (Intel i7, 32GB RAM, 1TB SSD) | 5 | IT | Heavy software development, virtualization, and testing |
| **HW-LAP-01** | Business Laptop (Intel i5, 16GB RAM, 512GB SSD) | 15 | HR (4), Finance (5), Sales (6) | Mobility for meetings, office productivity, and remote work readiness |
| **HW-MON-01** | 27" IPS FHD Dual Monitor Setup | 10 | IT | Dual-screen setup for coding and debugging efficiency |
| **HW-MON-02** | 24" FHD Single Monitor | 15 | HR, Finance, Sales | Extended desktop display for administrative office tasks |
| **HW-SRV-01** | Rack Server (Dell PowerEdge R450 - Xeon 16-Core, 64GB RAM, 4TB RAID) | 1 | Server Room (IT) | Local domain controller, file hosting, internal application staging |
| **HW-RTR-01** | Enterprise Router (MikroTik Cloud Core Router) | 1 | Server Room (IT) | Core network routing and inter-VLAN management |
| **HW-SW-01** | 48-Port Managed Gigabit PoE+ Switch | 1 | Server Room (IT) | Central network connectivity for all wired devices and access points |
| **HW-AP-01** | Wi-Fi 6 Access Point (Ubiquiti Unifi AP) | 2 | Office Floor | Seamless wireless coverage across all department work areas |
| **HW-PRN-01** | Heavy-Duty Network Laser Multifunction Printer | 1 | Shared Area | High-volume printing, scanning, and copying for all departments |
| **HW-UPS-01** | 3000VA Smart UPS System | 1 | Server Room (IT) | Power backup to prevent server and network device downtime during outages |
| **HW-NAS-01** | 4-Bay Network Attached Storage (16TB Total RAID 5) | 1 | Server Room (IT) | Centralized local backup storage for company assets and archives |
| **HW-EXT-01** | 4TB Rugged External Hard Drive | 2 | IT / Security | Cold offsite physical backup rotation |

---

## 💾 Software Inventory Summary

| Software | Version | License Type | Purpose / Justification |
| :--- | :--- | :--- | :--- |
| **Windows 11 Pro** | 22H2 / 23H2 | Commercial OEM/Volume | OS for end-user workstations with BitLocker and Domain Join support |
| **Ubuntu Server** | 22.04 LTS | Open-Source / Free | OS for the central server running local web applications and services |
| **Microsoft 365** | Business Standard | Enterprise Subscription | Standard office productivity tools (Word, Excel, Outlook, Teams) |
| **VS Code** | Latest Stable | Open-Source / Free | Primary IDE used by the IT development team |
| **Git** | Latest Stable | Open-Source / Free | Source code version control for software development workflows |
| **GitHub Desktop** | Latest Stable | Open-Source / Free | GUI client to streamline Git operations for developers |
| **VirtualBox** | 7.x | Open-Source / Free | Local environment isolation and sandbox testing for IT staff |
| **Google Chrome** | Latest | Enterprise Freeware | Standard corporate web browser |
| **Microsoft Defender** | Integrated Enterprise | Included with OS | Endpoint security, malware protection, and threat response |
| **AnyDesk** | Enterprise | Commercial License | Secure remote desktop support tool for internal IT assistance |
| **7-Zip** | 23.x | Open-Source / Free | Secure file compression and archive handling |

---

## 🌐 Enterprise Network Diagram

Below is the logical network topology designed for ABC Startup Solutions, showing network traffic flowing from the Internet down through perimeter security, core switching, servers, and department workstations.

![Enterprise Network Diagram](./diagrams/network_diagram.png)

*(Note: Ensure you place your exported PNG diagram in the `diagrams/` folder named `network_diagram.png`)*

---

## 🛠️ Technologies Used
- **Network Diagramming:** [Draw.io](https://app.diagrams.net/)
- **Documentation & Version Control:** Markdown, Git, [GitHub](https://github.com)
- **Networking Standards:** VLAN Segmentation, TCP/IP Routing, Wi-Fi 6 (802.11ax), 3-2-1 Backup Strategy

---

## ⚡ Challenges Encountered
1. **Network Topology Mapping:** Structuring logical connections between routers, firewalls, servers, and workstations while ensuring VLAN isolation for different departments required multiple revisions in Draw.io.
2. **Accurate Hardware Sizing:** Estimating the exact switch port counts and server hardware specifications needed for a 20-person team without overspending on unnecessary infrastructure.
3. **Markdown Table Formatting:** Cleaning up tabular data from raw text into clean, valid Markdown syntax for GitHub preview rendering.

---

## 💭 Reflection
Completing this project taught me a lot about what it actually takes to set up an entire IT infrastructure for a startup. Before this, I thought starting a company’s tech setup was just about buying a bunch of computers and connecting them to Wi-Fi. Building the hardware, software, and network inventories showed me how much thought goes into picking the right specs, licenses, and tools for each department so nobody runs out of storage or processing power.

The most challenging task for me was designing the network topology diagram in Draw.io and setting up the inventories. Figuring out how devices connect logically—from the internet connection and firewall down to the switches, servers, and department workstations—took a lot of trial and error. I had to make sure the VLANs, wireless access points, and server connections all made sense together so the network stays secure and fast.

Planning before deployment is super important because buying equipment without a plan leads to wasted money, security risks, and broken connections. If you don't calculate how many switch ports or IP addresses you need beforehand, you might end up with missing cables, overloaded routers, or unsecure devices. Proper planning makes sure the network can handle growth and stays safe from day one.

This project will help me become a better System Administrator because it gave me hands-on experience thinking like a real IT professional. I learned how to analyze business needs, document every piece of hardware and software, and explain technical choices clearly. It showed me that being a good SysAdmin isn't just about fixing broken computers, but also about building a solid, organized foundation that keeps the whole company running smoothly.

---

## 📚 References
- Cisco Systems. (2023). *Small Business Network Design Guide*. [Cisco Documentation](https://www.cisco.com)
- Microsoft Learn. (2024). *Windows 11 Enterprise Deployment Overview*. [Microsoft Docs](https://learn.microsoft.com)
- Canonical. (2024). *Ubuntu Server Documentation*. [Ubuntu Docs](https://ubuntu.com/server/docs)
- Fortinet. (2023). *Next-Generation Firewall Deployment Best Practices*. [Fortinet Docs](https://docs.fortinet.com)

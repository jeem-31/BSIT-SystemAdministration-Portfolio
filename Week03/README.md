# Enterprise Infrastructure Planning for a Startup Company

**Course:** ITEP 414 – System Administration and Maintenance  
**Institution:** Laguna State Polytechnic University (LSPU)  
**Instructor:** John Randolf M. Penaredondo, MIT  
**Student Name:** [Your Full Name Here]  
**Program:** Bachelor of Science in Information Technology (BSIT)  
**Week:** 2 Individual Portfolio Project  

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Learning Objectives](#-learning-objectives)
- [Part 1: Company Profile](#-part-1-company-profile)
- [Part 2: Enterprise Hardware Inventory](#-part-2-enterprise-hardware-inventory)
- [Part 3: Enterprise Software Inventory](#-part-3-enterprise-software-inventory)
- [Part 4: Enterprise Network Inventory](#-part-4-enterprise-network-inventory)
- [Part 5: Enterprise Network Diagram](#-part-5-enterprise-network-diagram)
- [Part 6: System Administration Roles & Analysis](#-part-6-system-administration-roles--analysis)
- [Part 7: Infrastructure Recommendations](#-part-7-infrastructure-recommendations)
- [Part 8: Personal Reflection](#-part-8-personal-reflection)
- [Technologies Used](#-technologies-used)
- [Challenges Encountered](#-challenges-encountered)
- [References](#-references)

---

## 📌 Project Overview

Every successful IT infrastructure begins with proper planning. Before purchasing computers, installing servers, configuring networks, or deploying cloud services, a System Administrator must first understand the organization's business requirements and design an infrastructure that supports business operations.

In this project, I assumed the role of a **Junior System Administrator** assigned to prepare the initial IT Infrastructure Plan for **ABC Startup Solutions**, a newly established software development company with 20 employees. Starting with no existing computers, servers, network, internet infrastructure, or security policies, this portfolio document presents the complete technical foundation designed from scratch.

---

## 🎯 Learning Objectives

* **Knowledge:**
  * Explain the roles, responsibilities, and collaborative ecosystem of System Administrators.
  * Identify the hardware, software, and networking requirements of a small startup business.
  * Describe the core purpose of IT documentation and infrastructure planning.
* **Skills:**
  * Analyze organizational IT requirements across diverse departmental functions.
  * Prepare professional IT inventories with accurate technical specifications and justifications.
  * Design an enterprise network topology diagram using standard networking principles and symbols.
  * Create technical documentation formatted cleanly using Markdown.
  * Present infrastructure planning professionally for management review.

---

## 🏢 Part 1: Company Profile

* **Company Name:** ABC Startup Solutions
* **Nature of Business:** Software Development & Custom Tech Solutions
* **Company Vision:** To become a leading provider of innovative, reliable, and scalable software solutions for businesses in Southeast Asia.
* **Company Mission:** To empower organizations through custom-built software applications while maintaining high standards of system availability, data security, and operational efficiency.
* **Office Location:** 5th Floor, Tech Innovation Tower, Laguna Technopark, Biñan, Laguna, Philippines

### Organizational Structure & Employee Distribution

The startup operates across a single office floor with 20 employees distributed among four core departments:

| Department | Headcount | Key Functions |
| :--- | :---: | :--- |
| **Information Technology** | 5 | Infrastructure management, software development, system maintenance, and tech support |
| **Human Resources** | 4 | Recruitment, employee relations, payroll support, and onboarding |
| **Finance** | 5 | Financial planning, accounting, billing, and payroll processing |
| **Sales** | 6 | Client acquisition, business development, and account management |
| **TOTAL** | **20** | **Complete Company Workforce** |

---

## 💻 Part 2: Enterprise Hardware Inventory

| Asset ID | Hardware Description | Quantity | Department | Purpose / Justification |
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

## 💾 Part 3: Enterprise Software Inventory

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

## 🌐 Part 4: Enterprise Network Inventory

| Equipment Name | Brand / Model | Quantity | Specifications / Details | Purpose |
| :--- | :--- | :---: | :--- | :--- |
| **ISP Modem** | Fiber Modem (ISP Provided) | 1 | Dual Band, Fiber Optic Gateway (500 Mbps) | Fiber internet termination point |
| **Router** | MikroTik CCR1009 | 1 | 8x GbE, 1x SFP+, Hardware Encryption | Gateway routing and Bandwidth management |
| **Firewall** | Fortinet FortiGate 60F | 1 | Next-Gen Firewall (NGFW), SSL VPN | Perimeter network defense, intrusion prevention, deep inspection |
| **Managed Switch** | Cisco Catalyst 2960X | 1 | 48-Port GbE PoE+, Layer 2/3 Managed | Central switch managing isolated VLANs per department |
| **Wireless AP** | UniFi 6 Long-Range | 2 | Wi-Fi 6, Dual-Band, PoE Powered | High-speed wireless access for laptops and mobile devices |
| **Patch Panel** | 48-Port Cat6 Patch Panel | 1 | 1U Rackmount RJ45 Keystone | Structured cabling management in server rack |
| **Cat6 Ethernet Cables** | Solid Copper Cat6 (305m Roll) | 2 Box | 1000Mbps / 10Gbps rated | Structured horizontal cabling through floor/walls |
| **RJ45 Connectors** | Pass-Through Cat6 Connectors | 200 Pcs | Gold-plated contacts | Cable terminations for network drops |

---

## 🗺️ Part 5: Enterprise Network Diagram

### Network Topology Architecture

The network topology routes incoming traffic from the external ISP connection through a high-throughput router and Next-Gen Firewall, leading to a central Layer 2/3 managed switch. The switch distributes traffic across isolated departmental subnets (VLANs), local servers, storage arrays, shared printers, and Wi-Fi 6 access points.



### Rendered Network Topology Diagram

![Enterprise Network Topology](diagrams/network_diagram.png)



---

## 👥 Part 6: System Administration Roles & Analysis

### 1. Helpdesk Technician
* **Responsibilities:** Serves as the first point of contact (Tier 1) for technical support. Manages IT helpdesk tickets, troubleshoots hardware/software issues for end-users, sets up new employee workstations, and maintains device inventory.
* **Skills:** Operating system troubleshooting (Windows/macOS), basic networking, active listening, customer service, hardware maintenance.
* **Common Tools:** Zendesk/Jira Service Desk, AnyDesk, Sysinternals, Active Directory Users & Computers.
* **Certifications:** CompTIA A+, Microsoft Certified: Modern Desktop Administrator Associate.

### 2. Network Administrator
* **Responsibilities:** Configures, maintains, and monitors local network infrastructure (switches, routers, firewalls, Wi-Fi APs). Ensures network uptime, manages VLAN segmentation, monitors bandwidth usage, and enforces network security policies.
* **Skills:** TCP/IP routing, subnetting, firewall configuration, VLAN segmentation, Wi-Fi optimization, network packet analysis.
* **Common Tools:** Wireshark, Cisco Packet Tracer, PuTTY, SolarWinds Network Performance Monitor.
* **Certifications:** Cisco Certified Network Associate (CCNA), CompTIA Network+.

### 3. Linux System Administrator
* **Responsibilities:** Installs, configures, and maintains Linux-based servers (e.g., Ubuntu Server, RHEL). Manages user permissions, automates routine tasks via shell scripts, monitors server performance, handles system updates, and ensures continuous service uptime.
* **Skills:** Bash scripting, user/group permission management, SSH security, systemd service administration, web/database server hosting.
* **Common Tools:** Bash CLI, SSH, Ansible, Cron, htop/top, Webmin.
* **Certifications:** CompTIA Linux+, Red Hat Certified System Administrator (RHCSA), LPIC-1.

### 4. Cloud Administrator
* **Responsibilities:** Provisions, configures, and monitors cloud-based infrastructure (AWS, Azure, or GCP). Manages cloud storage, user access policies (IAM), controls cloud resource deployment costs, and supports hybrid-cloud integrations.
* **Skills:** Cloud service management, Infrastructure as Code (Terraform), IAM security policies, virtual networking in the cloud, cloud cost management.
* **Common Tools:** AWS Management Console, Azure Portal, Terraform, AWS CLI, CloudWatch.
* **Certifications:** AWS Certified Solutions Architect – Associate, Microsoft Certified: Azure Administrator Associate.

### Cross-Functional Collaboration Analysis

In an enterprise environment, these four roles form a unified IT operations ecosystem. The Helpdesk Technician resolves immediate end-user requests and routes network/server-level bugs to Tier 2/3 specialists. The Network Administrator maintains stable connectivity and secure pathways so that the Linux System Administrator can host and optimize local services securely. Meanwhile, the Cloud Administrator extends local capabilities to offsite cloud platforms. Together, they build a cohesive network environment ensuring continuous system availability and end-user productivity.

---

## 🛡️ Part 7: Infrastructure Recommendations

* **Internet Provider (ISP):** Enterprise Fiber Internet Plan (500 Mbps symmetrical upload/download) with a static IP address to guarantee high application availability and stable remote access.
* **Server Specifications:** Dell PowerEdge Rack Server with dual power supplies, 64GB DDR4 RAM, and 4TB RAID 5 storage array to safeguard against hardware drive failures.
* **Backup Strategy:** Implement a strict **3-2-1 Backup Strategy**:
  * **3** copies of critical company data.
  * **2** different storage media types (Local Server RAID + Local Synology NAS).
  * **1** offsite/cloud backup location (Encrypted Cloud Storage + Offsite External Drives).
* **Security & Antivirus:** Centralized deployment of Microsoft Defender Enterprise across all endpoints with real-time scanning, network isolation features, and automated threat updates.
* **Password Policy:** Enforce enterprise domain policies requiring a minimum 12-character passphrase length (combining uppercase, lowercase, numbers, and symbols), mandatory Multi-Factor Authentication (MFA), and a quarterly password rotation requirement.
* **Expansion Plan:** The network is architected with scalability in mind. The 48-port switch currently utilizes only 25 ports, allowing seamless growth for up to 23 additional wired devices without requiring hardware upgrades.

---

## 💭 Part 8: Personal Reflection

Completing this project taught me a lot about what it actually takes to set up an entire IT infrastructure for a startup. Before this, I thought starting a company’s tech setup was just about buying a bunch of computers and connecting them to Wi-Fi. Building the hardware, software, and network inventories showed me how much thought goes into picking the right specs, licenses, and tools for each department so nobody runs out of storage or processing power.

The most challenging task for me was designing the network topology diagram in Draw.io and setting up the inventories. Figuring out how devices connect logically—from the internet connection and firewall down to the switches, servers, and department workstations—took a lot of trial and error. I had to make sure the VLANs, wireless access points, and server connections all made sense together so the network stays secure and fast. Ensuring that each department had proper bandwidth allocation and isolated network domains required deep thinking about how data flows across an enterprise.

Planning before deployment is super important because buying equipment without a plan leads to wasted money, security risks, and broken connections. If you don't calculate how many switch ports or IP addresses you need beforehand, you might end up with missing cables, overloaded routers, or unsecure devices. Proper planning makes sure the network can handle growth and stays safe from day one. It prevents unexpected downtime and guarantees that the company budget is spent effectively on scalable hardware.

This project will help me become a better System Administrator because it gave me hands-on experience thinking like a real IT professional. I learned how to analyze business needs, document every piece of hardware and software, and explain technical choices clearly. It showed me that being a good SysAdmin isn't just about fixing broken computers, but also about building a solid, organized foundation that keeps the whole company running smoothly. Developing these technical inventories and topological blueprints prepared me for real-world enterprise infrastructure challenges.

---

## 🛠️ Technologies Used

* **Network Diagramming:** Draw.io, Mermaid.js
* **Operating Systems:** Ubuntu Server 22.04 LTS, Windows 11 Pro
* **Documentation & Version Control:** Markdown, Git, GitHub
* **Networking Standards:** VLAN Isolation, Cat6 Cabling, TCP/IP, Wi-Fi 6 (802.11ax), 3-2-1 Backup Strategy

---

## ⚡ Challenges Encountered

* **Network Topology Mapping:** Structuring logical connections between routers, firewalls, servers, and workstations while ensuring VLAN isolation for different departments required multiple revisions in Draw.io.
* **Accurate Hardware Sizing:** Estimating the exact switch port counts and server hardware specifications needed for a 20-person team without overspending on unnecessary infrastructure.
* **Markdown Syntax Structuring:** Formatting large inventories and technical datasets into clean, validated Markdown tables for responsive GitHub rendering.

---

## 📚 References

* Cisco Systems. (2023). *Small Business Network Design Guide*. [https://www.cisco.com](https://www.cisco.com)
* Canonical Ltd. (2024). *Ubuntu Server Documentation*. [https://ubuntu.com/server/docs](https://ubuntu.com/server/docs)
* Microsoft Learn. (2024). *Windows 11 Enterprise Deployment Overview*. [https://learn.microsoft.com](https://learn.microsoft.com)
* Fortinet. (2023). *Next-Generation Firewall Deployment Best Practices*. [https://docs.fortinet.com](https://docs.fortinet.com)

# Techopoly Inc. Network Design Project

## Overview
This project presents a complete physical and logical network design for Techopoly Inc.’s new 50,000 sq. ft. headquarters. The design emphasizes **security**, **scalability**, **performance**, and **structured organization**—similar to a clean VR system architecture where every layer has purpose and flow.

The deliverables in this repository include:

- Physical network diagram  
- Active Directory (AD) organizational tree  
- Human-readable network tree  
- Parts list + cost summary  
- Written project summary  

---

## 🏛️ Network Architecture Summary

The network is built using a three-layer model: **Edge**, **Core**, and **Access**.

### **1. Internet & Security Edge**
- Dedicated T3 connection  
- Provider demarcation point  
- SMB-grade firewall  
- Stateful packet inspection  
- VPN capability  
- Policy-based traffic control  

### **2. Core Switching & Server Infrastructure**
Housed in the **Server & Network Room**:

- 48-Port Gigabit Core Switch (copper distribution)  
- 4-Port Fiber Switch (SFP+ backbone)  
- **Three enterprise servers:**
  - **SRV-DC01** — Domain Controller / DNS  
  - **SRV-APP01** — Application/File Server  
  - **SRV-DB01** — Database Server  
- **Five UPS units** for full power redundancy  
- Structured CAT7 copper cabling  
- Multimode OM3 fiber for high-speed connectivity  

### **3. Access Layer — Office Work Area**
Thirty Windows 11 Pro desktops allocated across:

- Executive Suite  
- Marketing  
- Sales  
- IT  
- Accounting  
- Shipping/Receiving  

Five networked printers support each department.  
All end-user devices are wired using **CAT7 horizontal cabling** routed back to the Server Room.

---

## 📂 Active Directory (AD) Structure

The AD domain mirrors the corporate org structure for clean management and permission control.


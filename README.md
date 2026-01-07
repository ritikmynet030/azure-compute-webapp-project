# Cross-Platform Web Service Deployment using Azure Compute (Linux & Windows Virtual Machines) 

## 🔹 Project Overview
This project demonstrates the deployment of a **web service hosted on both Linux and Windows Virtual Machines in Microsoft Azure.** It focuses on real-world compute operations such as VM provisioning, secure access, networking, and cost optimization.

The goal is to showcase hands-on Azure Compute skills by hosting web applications on **Apache (Linux VM) and IIS (Windows VM)**.

---

## 🔹 Key Features
- Deployment of Linux & Windows Virtual Machines
- Web server setup: (Apache on linux) & (IIS on Windows VM) 
- Secure access using SSH & RDP
- Public IP-based web access
- Network Security Group (NSG) inbound rules
- VM start, stop, resize operations
- Auto-shutdown enabled for cost optimization

---

## 🔹 Technologies Used
- Azure Virtual Machine
- Linux (Ubuntu) & Windows Server
- Apache & IIS Web Server
- Azure Networking (Vnet, NSG, Public IP, SSH, HTTP, RDP)
- ARM Templates (Infrastructure as Code)

---

## 🔹 Real-World Scenario
This lab project a realworld enterprise scenario where an organization hosts:
- A linux-based application for open-source workloads.
- A windows-based application for legacy or.NET workloads.

---

## 🔹 Architecture Diagram
- User ------HTTP(port 80)-------Linux VM (Apache)Public IP----NSG Rules ---- Port: HTTP 80, SSH 22
- User ------HTTP(port 80)-------Windows VM (IIS)Public IP----NSG Rules ---- Port: HTTP 80, RDP 3389 

---

## 🔹 Skills Demonstrated
- Azure VM provisioning (Linux & Windows)
- Secure remote access (SSH & RDP)
- Web server installation and configuration
- Azure Networking & NSG configuration
- VM lifecycle management
- Cost optimization using auto-shutdown

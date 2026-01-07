🌐 Azure Compute Web Service on Linux & Windows VMs
🔹 Project Name

Cross-Platform Web Service Deployment using Azure Compute (Linux & Windows Virtual Machines)

🔹 Project Overview

This project demonstrates the deployment of a web service hosted on both Linux and Windows Virtual Machines in Microsoft Azure. It focuses on real-world compute operations such as VM provisioning, secure access, networking, and cost optimization.

The goal is to showcase hands-on Azure Compute skills by hosting web applications on Apache (Linux VM) and IIS (Windows VM), making the project suitable for AZ-104 certification preparation and resume showcasing.

🔹 Key Features

✅ Deployment of Linux & Windows Virtual Machines

✅ Web server setup:

Apache on Linux VM

IIS on Windows VM

✅ Secure access using SSH & RDP

✅ Public IP-based web access

✅ Network Security Group (NSG) inbound rules

✅ VM start, stop, resize operations

✅ Auto-shutdown enabled for cost optimization

🔹 Technologies Used

Microsoft Azure

Azure Virtual Machines

Linux (Ubuntu)

Windows Server

Apache Web Server

IIS Web Server

Azure Networking (VNet, NSG, Public IP)

ARM Templates (Infrastructure as Code)

🔹 Real-World Scenario

This project simulates a real-world enterprise scenario where an organization hosts:

A Linux-based application for open-source workloads

A Windows-based application for legacy or .NET workloads

Both systems are deployed on Azure VMs with security controls and cost-saving mechanisms, reflecting how companies manage hybrid workloads in the cloud.

🔹 Architecture Diagram
User
  │
  ├── HTTP (Port 80)
  │
┌───────────────┐       ┌────────────────┐
│ Linux VM      │       │ Windows VM     │
│ (Apache)      │       │ (IIS)          │
│ Public IP     │       │ Public IP      │
└───────────────┘       └────────────────┘
  │                       │
  └──── NSG Rules (80,22 / 80,3389) ──────┘
🔹 Skills Demonstrated

Azure VM provisioning (Linux & Windows)

Secure remote access (SSH & RDP)

Web server installation and configuration

Azure Networking & NSG configuration

VM lifecycle management

Cost optimization using auto-shutdown

Infrastructure documentation using GitHub

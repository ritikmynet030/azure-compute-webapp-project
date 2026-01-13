# Cross-Platform Web Service Deployment using Azure Compute and Load Balancer (Linux & Windows Virtual Machines) 

## 🔹 Project Overview
This project demonstrates the deployment of a **web service hosted on both Linux and Windows Virtual Machines in Microsoft Azure.** It focuses on real-world compute operations such as VM provisioning, secure access, networking, cost optimization, VM using ARM Templates and Azure Load Balancer.

- The goal is to showcase hands-on Azure Compute skills by hosting web applications on **Apache (Linux VM) and IIS (Windows VM)**.
- This lab Show How to deploying web applications using ARM templates, following DevOps and automation best practices.
- This lab demonstrates how to build a highly available web application using Azure Load Balancer with two Linux Virtual Machines.

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
- Azure Load Balancer (Public)
- Health probe on HTTP port 80
- Backend pool with multiple VMs
- Load balancing rule for HTTP traffic

---

## 🔹 Real-World Scenario
This project represents a real-world enterprise cloud scenario where an organization hosts **multiple application workloads** using modern Azure practices:
- A **Linux-based application** for open-source, microservices, or lightweight web workloads (e.g., Apache-hosted services)
- A **Windows-based application** for legacy systems or .NET-based enterprise applications hosted on IIS

To ensure **consistency, automation, and scalability,** the infrastructure is provisioned using **ARM Templates (Infrastructure as Code)**, allowing repeatable deployments across environments such as Dev, Test, and Production.

For customer-facing workloads, the organization implements **Azure Load Balancer** to distribute incoming HTTP traffic across **multiple Linux web servers**, ensuring:
- High Availability
- Fault Tolerance
- Improved performance during traffic spikes

---

## 🔹 Architecture Diagra
1. Linux and Windows VM 
   - User ------HTTP(port 80)-------Linux VM (Apache)Public IP----NSG Rules ---- Port: HTTP 80, SSH 22
   - User ------HTTP(port 80)-------Windows VM (IIS)Public IP----NSG Rules ---- Port: HTTP 80, RDP 3389

2. Azure Load Balancer – Highly Available Web App
   - User ------HTTP(port 80)------Azure Load Balancer(Public IP)-----Linux VM01 & Linux VM02

---

## 🔹 Skills Demonstrated
- Azure VM provisioning (Linux & Windows)
- Secure remote access (SSH & RDP)
- Web server installation and configuration (Apache & IIS)
- Azure Networking & NSG configuration
- ARM template authoring and deployment
- Azure Load Balancer configuration
- High availability architecture design
- Cost optimization and VM lifecycle management

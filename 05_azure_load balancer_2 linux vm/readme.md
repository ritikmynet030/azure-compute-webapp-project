# Highly Available Web Application Using Azure Load Balancer

## 🔹 Project Overview
This project demonstrates how to deploy a highly available web application on Microsoft Azure using:
- 2 Linux Virtual Machines (Apache Web Server)
- Azure Load Balancer (Public, Standard SKU)
- Health Probes for traffic routing
The Load Balancer distributes incoming HTTP traffic across multiple backend VMs, ensuring fault tolerance and high availability.

---

## 🔹 Key Features
- Two Linux VMs running Apache Web Server
- Azure Public Load Balancer
- Backend pool with multiple VMs
- HTTP Health Probe (Port 80)
- Load balancing rule for web traffic
- High availability and fault tolerance

---

## 🔹 Technologies Used
- Microsoft Azure
- Azure Virtual Machines (Linux – Ubuntu)
- Azure Load Balancer (Standard)
- Apache Web Server
- Azure Networking (VNet, Subnet, NSG, Public IP)

---

## 🔹 Real-World Scenario
In production environments, web applications must remain available even if one server fails. This architecture ensures:
- Continuous service availability
- Automatic traffic redirection to healthy servers
- Scalable and reliable infrastructure

---

## 🔹 Architecture Diagram
                                                      
User Browser >>>> Azure Load Balancer (Public IP) >>>> >>> Linux VM01 (Apache) & Linux VM02 (Apache)
                                                      
---

## 🔹 Skills Demonstrated
- Azure Load Balancer configuration
- High Availability design
- Linux VM administration
- Apache Web Server setup
- Health probe configuration
- Azure networking concepts

#Home-Based NAS System (Real-Life Simulation using Cisco Packet Tracer)

## Overview
This project demonstrates a home-based Network Attached Storage (NAS) system built using Cisco Packet Tracer. It simulates a centralized file storage environment where multiple devices can upload, download, and access files over a local network using FTP.

The system represents a small home or office setup where a server acts as a NAS and provides shared storage to connected devices.

---

## Objectives
- Design a home network using Cisco Packet Tracer  
- Configure a server as a NAS system  
- Enable file sharing using FTP protocol  
- Allow multi-device access to centralized storage  
- Understand client-server communication  

---

## Network Topology

The network includes the following components:

- Wireless Router (WRT300N)  
- Server (Configured as NAS)  
- One wired PC  
- Multiple wireless devices (laptops and smartphones)  

All devices are connected through the router, which assigns IP addresses using DHCP.

![Network Topology]
<img width="601" height="315" alt="Topology" src="https://github.com/user-attachments/assets/3714381d-e554-44f8-9cfa-9db860e5aa4e" />


---

## IP Addressing Scheme

| Device       | IP Address      |
|--------------|-----------------|
| Router       | 192.168.1.1     |
| NAS Server   | 192.168.1.10    |
| PC           | DHCP Assigned   |
| Other Devices| DHCP Assigned   |

---

## NAS Server Configuration

The server is configured as a NAS using FTP services.

Steps:
1. Enable FTP service from the Services tab  
2. Create user credentials  
3. Verify service availability  

![FTP Configuration](images/ftp-login.png)

---

## Client Configuration

Clients obtain IP addresses automatically using DHCP.

Steps:
1. Connect devices to the network  
2. Verify IP configuration  
3. Test connectivity using ping  

![IP Configuration](images/ip-config.png)  
![Ping Test](images/ping-test.png)

---

## FTP File Transfer

### Connect to NAS

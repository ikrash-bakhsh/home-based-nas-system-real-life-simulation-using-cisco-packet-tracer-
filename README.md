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

![FTP Configuration]

<img width="521" height="502" alt="image" src="https://github.com/user-attachments/assets/7453e60e-3889-4b42-bb25-34a8378d89c8" />



---

## Client Configuration

Clients obtain IP addresses automatically using DHCP.

Steps:
1. Connect devices to the network  
2. Verify IP configuration  
3. Test connectivity using ping  

![IP Configuration]

<img width="500" height="236" alt="image" src="https://github.com/user-attachments/assets/4ab4e9f7-1ed1-4592-8429-365e1b7ed32e" />

![Ping Test]

<img width="498" height="173" alt="image" src="https://github.com/user-attachments/assets/ccd27867-b317-4cf6-9156-aa97bdaa4ecb" />



---

## FTP File Transfer
To connect to the NAS server, the client device uses the FTP protocol through the command prompt.

Command used:

```bash
ftp 192.168.1.10
```

The user then enters the configured username and password to establish a successful connection with the NAS server.

![FTP Login]

<img width="488" height="56" alt="image" src="https://github.com/user-attachments/assets/284cad27-cda0-421f-8976-15e3b1f29ae5" />

### Directory Listing

After successful authentication, the client can view all files and directories stored on the NAS server using the following command:

```bash
dir
```

This command displays the available folders and stored files inside the FTP directory.


### File Upload Process

Files can be uploaded from the client PC to the NAS server using the following command:

```bash
put filename.txt
```

This process allows centralized storage of files on the NAS server, making them accessible to other connected devices on the network.

### File Download Process

Files stored on the NAS server can also be downloaded to client devices using the following command:

get filename.txt

This allows users to retrieve files from the centralized storage whenever required.

## NAS Directory Structure

To improve file organization and management, separate directories can be created on the NAS server for different devices and purposes.

The following folders can be used:

- Public  
- PC_Files  
- Laptop_Files  
- Phone_Files  
- Media  

This directory structure helps organize uploaded files and simulates a real-world NAS storage environment.

## Working Flow of the System

The system operates according to the following workflow:

1. The router connects all devices within the home network  
2. The NAS server provides centralized storage services  
3. The PC uploads files to the NAS using FTP  
4. Wireless devices such as laptops and smartphones access stored data through the network  
5. Files can be downloaded, shared, and managed from multiple devices

## Key Features

- Centralized storage system  
- Multi-device file access  
- FTP-based file transfer  
- Wired and wireless connectivity  
- DHCP-based automatic IP assignment  
- Structured directory management  
- Real-life home network simulation

## Technologies Used

- Cisco Packet Tracer  
- FTP Protocol  
- DHCP  
- Client-Server Architecture  
- Home Networking Concepts


## Learning Outcomes

This project helped in understanding:

- Network topology design  
- NAS architecture and functionality  
- FTP communication and file transfer  
- IP addressing and DHCP configuration  
- Client-server communication model  
- Practical implementation of centralized storage systems  

## Future Improvements

The following features can be added in future versions of the project:

- Secure remote access to NAS  
- User-based access permissions  
- Automatic backup system  
- Web-based file management  
- Advanced network security configurations
- Secure remote access through VPN or port forwarding

## Conclusion

The Home-Based NAS System successfully demonstrates a centralized storage solution in a simulated home network environment. Multiple devices are able to communicate with the NAS server, upload files, and access shared data through FTP.

This project provides a practical understanding of how NAS systems operate in real-world home and small office networks while also strengthening networking and server configuration skills.

## Author

Muhammad Ikrash Bakhsh

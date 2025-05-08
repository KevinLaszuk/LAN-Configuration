# LAN-Configuration

## Overview
In this lab, we configured a **Local Area Network (LAN)** using Cisco Packet Tracer, which consists of 5 devices: 3 PCs, a switch, and a router. The goal was to understand and implement **Layer 2 (Ethernet) and Layer 3 (IP Addressing)** within a hierarchical network model. This lab also introduced **router configuration** to manage IP addresses and route traffic between different subnets.

## Objectives
- **Model a LAN** using Cisco Packet Tracer.
- **Configure basic switch settings** and **router configurations** for IP management.
- **Assign IP addresses** to the PCs and router interfaces.
- **Verify connectivity** within the LAN using ping and other network diagnostics.

## Tools Used
- **Cisco Packet Tracer** for network simulation.
- **Windows PCs** for host devices.
- **Cisco Router and Switch** for network management.
- **IP Addressing** for Layer 3 routing and subnetting.

## Network Topology
The network consists of:
- **3 PCs**: Each configured with a static IP address.
- **1 Switch**: Used for Layer 2 connectivity.
- **1 Router**: Configured to route traffic between different subnets.
  
The devices are connected as follows:
1. **PCs to Switch**: Each PC is connected to one of the switch’s ports.
2. **Switch to Router**: The router's interface is connected to the switch to manage traffic between PCs.

### IP Addressing Table

| Device      | IP Address   | Subnet Mask     | Gateway        |
|-------------|--------------|-----------------|----------------|
| **PC1**     | 192.168.1.2  | 255.255.255.0   | 192.168.1.1    |
| **PC2**     | 192.168.1.3  | 255.255.255.0   | 192.168.1.1    |
| **PC3**     | 192.168.1.4  | 255.255.255.0   | 192.168.1.1    |
| **Router**  | 192.168.1.1  | 255.255.255.0   | -              |


## Screenshots
<p align="center">
Network Topology: <br/>
<img src="https://github.com/user-attachments/assets/8038ffb8-1b25-44e9-959e-140ac8df0943" height="80%" width="80%" 
</br>

<p align="center">
Ping from PC-to-PC: <br/>
<img src="https://github.com/user-attachments/assets/9bbd5c77-4db3-4b7e-b54e-e507d2460afb" height="80%" width="80%" 
</br>

<p align="center">
Ping from Router: <br/>
<img src="https://github.com/user-attachments/assets/a09ad989-9098-4d30-ae4b-983a159bfb70" height="80%" width="80%" 
</br>

<p align="center">
Show version/run command: <br/>
<img src= "https://github.com/user-attachments/assets/773a0866-b378-42f5-9f5e-51a9bdb25425" height="80%" width="80%" 
</br>

<p align="center">
Show ip int brief command: <br/>
<img src= "https://github.com/user-attachments/assets/abefe9af-6269-4f3f-b430-ad8b22f9d969"
 height="80%" width="80%" 
</br>













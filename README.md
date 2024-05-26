# Gulf Spare Parts (GSP) Network Project

## Overview
This project involves planning, designing, implementing, and troubleshooting a computer network for Gulf Spare Parts (GSP), a Qatari automotive parts provider operating across the Gulf countries. The goal is to centralize GSP's IT infrastructure and integrate public cloud services for improved productivity and accessibility. The network design includes both IPv4 and IPv6 protocols, routing protocols, application layer services, DHCP implementation, secure remote access, and backup routing strategies.

## Key Project Components
1. **IP Addressing and Subnetting Scheme**
   - Use of IPv4 addresses 10.10.0.0/11 and 211.168.0.0/22, and IPv6 address 2003:0DB8:C21A::/64.
   - Classless addressing scheme with subnet masks tailored to required devices in each network.

2. **Routing Protocols**
   - Implementation of RIP V2 for IPv4 and RIPng for IPv6 routing.

3. **Network Design**
   - Cloud network directly connected to Qatar Headquarters with redundant high-speed links.
   - Centralized edge/core router (Gulf-ISP) for all GSP buildings with no direct links between buildings and Qatar HQ.

4. **Application Layer Services**
   - DNS, Web Server, FTP, TFTP, Email services using IPv4 on Cloud network.
   - DHCP implementation for IPv4 and IPv6 in Kuwait and Bahrain branches.

5. **Security and Remote Access**
   - Secure remote access (SSH) setup for switches and routers.
   - Backup static routes for network resilience.

6. **Device Configuration**
   - Proper host naming and interface description for routers, switches, and PCs based on location.

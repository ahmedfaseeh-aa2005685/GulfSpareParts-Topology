# Gulf Spare Parts (GSP) Network Project

Overview
This project involves planning, designing, implementing, and troubleshooting a computer network for Gulf Spare Parts (GSP), a Qatari automotive parts provider operating across the Gulf countries. The goal is to centralize GSP's IT infrastructure and integrate public cloud services for improved productivity and accessibility. The network design includes both IPv4 and IPv6 protocols, routing protocols, application layer services, DHCP implementation, secure remote access, and backup routing strategies.

Project Deliverables
Part 1: Network Plan and Design Report
Detailed report outlining the IP addressing scheme (IPv4 and IPv6) for GSP.
Subnetting using VLSM strategy, listing used and unused subnets.
Implementation of RIP V2 for IPv4 and RIPng for IPv6 routing protocols.
Network diagram illustrating the proposed network design.
Part 2: Implementation and Troubleshooting (Packet Tracer)
Implementation of application layer services (DNS, Web Server, FTP, TFTP, Email) using IPv4 on Cloud network.
Implementation of DHCP for IPv4 and IPv6 in Kuwait and Bahrain branches.
SSH setup for secure remote access to switches and routers.
Backup static routes setup for each location in case of dynamic routing failure.
Proper naming and description of devices (PCs, switches, routers) based on location.
Key Project Components
IP Addressing and Subnetting Scheme

Use of IPv4 addresses 10.10.0.0/11 and 211.168.0.0/22, and IPv6 address 2003:0DB8:C21A::/64.
Classless addressing scheme with subnet masks tailored to required devices in each network.
Routing Protocols

Implementation of RIP V2 for IPv4 and RIPng for IPv6 routing.
Network Design

Cloud network directly connected to Qatar Headquarters with redundant high-speed links.
Centralized edge/core router (Gulf-ISP) for all GSP buildings with no direct links between buildings and Qatar HQ.
Application Layer Services

DNS, Web Server, FTP, TFTP, Email services using IPv4 on Cloud network.
DHCP implementation for IPv4 and IPv6 in Kuwait and Bahrain branches.
Security and Remote Access

Secure remote access (SSH) setup for switches and routers.
Backup static routes for network resilience.
Device Configuration

Proper host naming and interface description for routers, switches, and PCs based on location.

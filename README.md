# Enterprise-Network-Security-Design

Project Overview:
Designed a secure enterprise network architecture for a corporate environment focusing on segmentation, threat prevention, and high availability.

Objectives:
- Secure internal network while maintaining public web access
- Prevent lateral movement using VLAN segmentation
- Implement layered defense (DMZ, firewalls, IDS/IPS)
- Enable secure remote access


Architecture:

Network Segmentation
- VLAN separation for:

  - Accounting

  - Sales

  - Servers

- Layer 3 switch used for inter-VLAN routing

DMZ Implementation

- Public web server isolated in DMZ

- Dual-firewall architecture:

  - External firewall (Internet → DMZ)

  - Internal firewall (DMZ → Internal)

Security Controls

- Palo Alto NGFW (deep packet inspection)

- IDS/IPS for threat detection

- Host-based firewalls:

  - Windows Defender

  - Firewalld (Linux)

# Enterprise Network Security Architecture

Secure multi-branch enterprise network deployment implementing layered security controls, centralized authentication, encrypted site-to-site communication, and infrastructure hardening using Cisco technologies.

---

## Project Overview

This project simulates the secure expansion of an enterprise network infrastructure by integrating a new operational branch into an existing corporate environment.

The architecture focuses on:
- Secure inter-branch communication
- Centralized authentication and logging
- Infrastructure hardening
- Dynamic routing
- Layered defense mechanisms
- Enterprise-grade network segmentation

The deployment was implemented and validated using Cisco Packet Tracer and Cisco IOS configurations.

---

## Security Features

### Network Security
- OSPF Dynamic Routing
- Site-to-Site IPsec VPN
- SSH v2 Secure Remote Management
- ACL-Based Traffic Control
- Multi-Branch Secure Connectivity

### Authentication & Access Control
- TACACS+ AAA Authentication
- Centralized User Authentication
- Privileged Access Management
- Login Brute-Force Protection

### Infrastructure Hardening
- Switch Port Security
- Sticky MAC Addressing
- Violation Restriction & Shutdown Policies
- Secure Enable Secret Hashing
- Password Encryption

### Monitoring & Logging
- Centralized SYSLOG Server
- Security Event Monitoring
- Network Activity Logging
- Configuration Verification

---

## Technologies Used

- Cisco IOS
- Cisco Packet Tracer
- OSPF
- IPsec VPN
- TACACS+
- SYSLOG
- SSH
- ACLs
- Port Security

---

## Implemented Components

### Routing & Connectivity
- OSPF Area 0 Configuration
- Dynamic Route Propagation
- WAN Serial Connectivity
- Branch-to-Branch Communication

### VPN Deployment
- AES Encryption
- SHA Hashing
- ISAKMP Policies
- IPsec Transform Sets
- Secure Tunnel Establishment

### AAA Security
- TACACS+ Server Integration
- Centralized Authentication
- Authorization Policies
- SSH Login Validation

### Switch Security
- Port Security Enforcement
- Sticky MAC Learning
- Restrict & Shutdown Violation Modes
- Secure Access Layer Design

---

## Network Architecture

The environment includes:
- Edge Routers
- Core Switches
- Department Access Switches
- AAA Server
- SYSLOG Server
- Multi-Department Endpoints
- WAN Serial Links
- Inter-Branch VPN Connectivity

---

## Verification & Validation

The project includes operational verification using:
- `show ip route`
- `show ip ospf neighbor`
- `show crypto ipsec sa`
- `show aaa sessions`
- `show port-security`
- SYSLOG monitoring validation

---

## My Contribution

Contributed to the implementation and verification of:
- OSPF Routing
- Site-to-Site VPN Security
- TACACS+ AAA Authentication
- SYSLOG Centralized Logging
- SSH Hardening
- Port Security Policies
- Infrastructure Security Validation

---

## Key Learning Outcomes

- Enterprise Network Architecture
- Layered Security Design
- Infrastructure Hardening
- Secure Remote Administration
- VPN Technologies
- Centralized Authentication
- Network Monitoring & Logging
- Cisco Security Best Practices

---

## Team Members

- Abdelmonem Sayed
- Eyad Ahmed
- Ebram Hany
- Yassin Azab
- Ali Abdallah

---

## Academic Context

Course: Network Security  
Faculty: Informatics and Computer Science  
Major: IT Security  
Instructor: Dr. Marwa Zamzam

---

## Repository Structure

```bash
/screenshots
/configurations
/topology
/report

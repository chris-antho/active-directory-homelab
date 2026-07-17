# Active Directory Homelab

## Project Overview

This project documents the deployment of a Microsoft Active Directory environment 
in my Proxmox homelab

The environment includes a Windows Server Domain Controller and a Windows 11 client. 
The project is designed to provide hands-on experience with Windows Server, Active Directory, 
Domain Services, DNS, user administration, domain authentication, and Group Policy.

## Project Goals
- Deploy a Windows Server virtual machine
- Configure a static IP address
- Install Active Directory
- Promote the server to to a Domain Controller
- Configure a new Active Directory forest and domain
- Configure DNS
- Deploy a Windows 11 client
- Join the Windows 11 computer to the domain
- Create Organizational Units
- Create users and security groups
- Test domain user authentication
- Configure and test Group Policy
- Practice common Active Directory troubleshooting tasks

## Lab Environment

### Physical Host

- Dell Optiplex 7070 Micro
- Intel Core i5-9500T
- 16 GB RAM
- Proxmox VE

### Architecture

```text
Dell OptiPlex 7070 Micro
└── Proxmox VE
    ├── Windows Server
    │   ├── Active Directory Domain Services
    │   ├── Domain Controller
    │   └── DNS Server
    └── Windows 11
        └── Domain-Joined Client

```


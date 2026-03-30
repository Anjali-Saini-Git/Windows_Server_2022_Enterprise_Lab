# Windows Server 2022 Enterprise Deployment Project
**By Anjali Saini**

## Project Overview
This project demonstrates the installation, configuration, and management of a Windows Server 2022 environment in a virtualized lab. 

## Network Configuration
- **Server Name:** SERVER1
- **Static IP:** 192.168.29.100
- **Domain:** anjali.local

## Key Milestones & Evidence

### 1. Active Directory & DNS Setup
Configured a New Forest and Root Domain. Verified name resolution using `nslookup`.
[DNS Verification]

### 2. User & OU Management
Created OUs for **HR** and **IT** departments with dedicated user accounts (John.HR, Alice.IT).
[ADUC Structure]

### 3. DHCP Configuration
Implemented a DHCP scope (192.168.29.101 - 110) to automatically assign IPs to client machines.
[DHCP Scope]

### 4. Group Policy Objects (GPOs)
- **Wallpaper Policy:** Applied a corporate background for the HR department.
- **USB Block:** Disabled removable storage for the IT department.
- **Password Policy:** Enforced a 12-character minimum password length.
[GPO Management]

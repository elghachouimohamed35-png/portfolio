Project Screenshots
# Windows Server Infrastructure (AD DS / DHCP / DNS)

## 📖 Project Overview

This project demonstrates the deployment of a complete Windows Server infrastructure in a VMware Workstation virtual environment.

The infrastructure includes:

- Active Directory Domain Services (AD DS)
- DNS Server
- DHCP Server
- Windows 10 Client joined to the domain
- User and Group Management

---

## 🛠 Environment

- Hypervisor: VMware Workstation
- Windows Server 2019
- Windows 10 Client
- Domain: GHACHOUI.ma
- Server IP: 192.168.1.10
- DHCP Scope: 192.168.1.11 – 192.168.1.100

---

# 📷 Project Screenshots

## 1. Windows Server Configuration

The Windows Server has been configured as the Domain Controller hosting Active Directory, DNS and DHCP services.

![Server](images/01-server-manager.png)

---

## 2. DHCP Scope

Creation of the DHCP scope used to distribute IP addresses automatically.

![DHCP](images/02-dhcp-scope.png)

---

## 3. DHCP Address Range

DHCP configured with an address range from **192.168.1.11** to **192.168.1.100**.

![DHCP Range](images/03-dhcp-range.png)

---

## 4. Active Directory

Active Directory Users and Computers console showing the domain structure.

![Active Directory](images/04-active-directory.png)

---

## 5. Security Group

Creation of a Global Security Group used for permission management.

![Security Group](images/05-security-group.png)

---

## 6. User Account

Configuration of the Active Directory user **malak**.

![User](images/06-user-malak.png)

---

## 7. Domain Login

Windows 10 client successfully authenticated using the domain account.

![Login](images/07-windows10-login.png)

---

## 8. Network Test

Verification of DHCP and DNS services using **ipconfig** and **ping**.

![Network Test](images/08-ping-ipconfig.png)

---

## ✅ Technologies

- Windows Server 2019
- Active Directory
- DNS
- DHCP
- VMware Workstation
- Windows 10

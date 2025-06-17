# 🧠 Home Lab Setup: Windows Server 2019 

This project documents my hands-on experience building a basic enterprise network simulation using **Oracle VirtualBox** and **Windows Server 2019**. I successfully set up a domain controller, DHCP server, and a Windows 10 client joined to the domain.

---

## 🔧 Project Overview

- Installed and configured **Windows Server 2019** in a VirtualBox environment.
- Promoted the server to a **Domain Controller (DC)**.
- Set up **Active Directory Domain Services (AD DS)**.
- Installed and configured **DHCP Server** to automatically assign IP addresses.
- Connected a **Windows 10 client** VM to the domain.
- Demonstrated basic **networking and system administration skills**.

---

## 🧰 Tools & Technologies

- 💻 **Oracle VirtualBox**
- 🖥️ **Windows Server 2019**
- 🧑‍💻 **Windows 10 (Client)**
- 🧠 **Active Directory Domain Services**
- 🌐 **DHCP Server**

---

## ⚙️ Key Skills Demonstrated

### 🖥️ Windows Server Setup
- Installed Windows Server 2019 on a VM.
- Configured server settings (static IP, hostname, etc.).

### 🏢 Active Directory (AD DS)
- Promoted server to Domain Controller.
- Configured domain: `yourdomain.local`.
- Created Organizational Units (OUs) and domain user accounts.
- Managed Group Policy Objects (GPOs) for basic configurations.

### 📡 DHCP Server
- Installed DHCP role.
- Created and activated IP address scopes.
- Verified successful IP assignment to client machines.

### 🧩 Client Integration
- Installed and configured Windows 10 VM.
- Joined client machine to the domain.
- Logged in using domain user credentials.
- Verified DNS resolution and domain communication.

### 🧠 Networking Concepts
- Set up static IPs, DNS configuration.
- Used `ipconfig`, `ping`, and other tools for diagnostics.
- Ensured internal network connectivity between VMs.

# Windows Server 2016 Lab Project

---

## Environment Setup
- **Virtualization Software:** VirtualBox
- **Server OS:** Windows Server 2016
- **Client OS:** Windows 10 (2 VMs)

---

## Project Steps

### 1. Installed and Configured Windows Server 2016
- Installed the OS on a VM.
- Configured networking and static IP.
- Renamed server and prepared it for domain setup.

### 2. Active Directory Setup
- Installed the **Active Directory Domain Services (AD DS)** role.
- Promoted the server to a Domain Controller.
- Created a new domain: `myhomelab.local`.

### 3. User and Group Management
- Created multiple **user accounts** in Active Directory.
- Organized users into **Organizational Units (OUs)**.
- Applied **Group Policies (GPOs)** for security and desktop settings.

### 4. Added Client Machines to Domain
- Created two Windows 10 VMs.
- Joined both clients to the `myhomelab.local` domain.
- Verified user login with domain accounts.

### 5. Software Deployment with PDQ
- Installed **PDQ Deploy** on the server.
- Pushed software packages (e.g., Chrome, Teams, 7-Zip) to client machines.
- Confirmed successful remote installation.

### 6. Remote Desktop Testing
- Enabled **Remote Desktop Services** on the server and clients.
- Connected to clients remotely using RDP.
- Tested domain account permissions and remote access.

---

## Skills Demonstrated
- Virtualization & Lab Setup
- Windows Server 2016 Administration
- Active Directory (AD DS, OUs, GPOs, User/Computer Management)
- Domain Join Process for Clients
- Software Deployment with PDQ
- Remote Desktop (RDP) Configuration and Testing
- Troubleshooting Networking and Login Issues

---

## Outcome
This lab demonstrates my ability to:
- Build and manage a Windows domain environment from scratch.
- Configure Active Directory and manage users/groups.
- Deploy software remotely and support end-users.
- Apply help desk and IT support skills in a simulated enterprise environment.

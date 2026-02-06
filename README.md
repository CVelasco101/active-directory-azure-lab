# Active Directory Home Lab in Azure

## Project Overview
Built and configured a complete Active Directory environment in Microsoft Azure to demonstrate enterprise IT administration skills for helpdesk and system administration roles.

## Objective
To gain hands-on experience with Active Directory, user management, Group Policy, and Azure cloud infrastructure - all critical skills for IT support roles.

## Technologies Used
- **Microsoft Azure** (Cloud Platform)
- **Windows Server 2022** (Domain Controller)
- **Windows 10 Pro** (Client Machine)
- **Active Directory Domain Services (AD DS)**
- **DNS**
- **Group Policy Management**
- **PowerShell**
- **Remote Desktop Protocol (RDP)**

## Lab Architecture

**Network Design:**
- Virtual Network: 10.0.0.0/16
- Subnet: 10.0.1.0/24
- Domain Controller (DC-01): 10.0.1.4 (Static IP)
- Client Machine (Client-01): DHCP assigned
- Domain Name: mylab.local

<img width="758" height="1196" alt="Network Diagram" src="https://github.com/user-attachments/assets/9c63af6f-778f-43e8-965e-7447b3b1db6c" />


## Skills Demonstrated

### 1. Azure Cloud Infrastructure
- Created and configured Azure Virtual Network
- Deployed Virtual Machines (Windows Server 2022 & Windows 10)
- Configured Network Security Groups (NSGs)
- Managed DNS settings for domain integration

### 2. Active Directory Administration
- Installed and configured Active Directory Domain Services (AD DS)
- Promoted Windows Server to Domain Controller
- Created Organizational Units (OUs) for IT, HR, and Sales departments
- Managed user accounts and security groups
- Joined Windows 10 client to domain

### 3. Group Policy Configuration
- Created and linked Group Policy Objects (GPOs)
- Configured password policies (minimum length, complexity, expiration)
- Set account lockout policies (5 attempts, 30-minute lockout)
- Enabled Remote Desktop access for specific security groups

### 4. User Management Tasks
- Created user accounts across multiple OUs
- Reset user passwords
- Unlocked locked accounts
- Added users to security groups
- Used PowerShell for user creation automation

### 5. Troubleshooting & Testing
- Verified DNS resolution for domain
- Tested Group Policy application with `gpupdate` and `gpresult`
- Validated account lockout policies
- Confirmed user authentication across domain

## Key Accomplishments
✅ Successfully built a multi-VM Active Directory environment from scratch  
✅ Configured enterprise-level security policies  
✅ Demonstrated understanding of network architecture and DNS  
✅ Practiced real-world helpdesk scenarios (password resets, account unlocks)  
✅ Documented entire process with screenshots and notes  

## Screenshots

### Domain Controller Setup
<img width="3293" height="1247" alt="step 6" src="https://github.com/user-attachments/assets/eb161369-607d-4d06-beea-3ea9819e94cd" />
*Windows Server 2022 Domain Controller successfully deployed in Azure*

### Active Directory Structure
![step 8](https://github.com/user-attachments/assets/721e8385-2b3d-4955-860b-1e8b6b44eb5a)
*Created OUs for IT, HR, Sales, and Admins departments*

![step 9](https://github.com/user-attachments/assets/2a137c38-1e44-4e5b-ba12-d8b26f6db8d3)
![step 9 pt2](https://github.com/user-attachments/assets/7f327ec1-2590-4cf9-8e58-ac8669279b94)
![step 9 pt3](https://github.com/user-attachments/assets/4d5b1c80-f9e6-482d-8f7f-12c877d45b94)

*Multiple user accounts created across different OUs*

### Domain Integration
![step 13](https://github.com/user-attachments/assets/1d8ee289-e8e5-4d65-a33d-730ff4df3720)

*Windows 10 client successfully joined to mylab.local domain*

### Group Policy Configuration
![step 16](https://github.com/user-attachments/assets/7c4d2484-5fc1-4116-a8e9-c0abf6c0ff3a)
![step 19](https://github.com/user-attachments/assets/d6c4a5cf-9852-4ea8-aefe-2b03a4ec57b7)
![step 20](https://github.com/user-attachments/assets/99ec268b-fd64-4b1c-9ddc-14d428ae4929)

*Configured enterprise password requirements*

![step 15](https://github.com/user-attachments/assets/8040e4ae-4022-40fc-b3bd-0d7b0a05ebce)

*Set account lockout threshold and duration*

### User Management
<img width="2769" height="1231" alt="step 21" src="https://github.com/user-attachments/assets/bac7913c-4f67-4aad-85c7-453aab3c332d" />
<img width="558" height="133" alt="step 22" src="https://github.com/user-attachments/assets/341cadd6-48cb-494f-b703-9c2161158cbf" />

*Performing password reset from Active Directory*

<img width="2256" height="976" alt="Unlocking User Account" src="https://github.com/user-attachments/assets/b4162983-f035-40da-b566-a9cb980a9483" />

*Unlocking a locked user account*

## Lessons Learned
- Importance of proper DNS configuration when building AD environments
- How Group Policies propagate through domain structure
- Practical understanding of Organizational Units for user management
- Real-world experience with cloud infrastructure (Azure)
- The relationship between networking and Active Directory functionality

## Future Enhancements
- Add DHCP server role to Domain Controller
- Configure file sharing with permissions based on security groups
- Implement multiple Domain Controllers for redundancy
- Add Certificate Services for secure authentication
- Create automated user provisioning scripts with PowerShell

## Relevant Skills for Helpdesk Roles
This lab directly demonstrates skills used daily in helpdesk positions:
- Resetting user passwords in Active Directory
- Unlocking locked accounts
- Managing user permissions and group memberships
- Troubleshooting domain connectivity issues
- Understanding enterprise network structure
- Working with Windows Server and client operating systems
  
---

*This lab was completed as part of my preparation for entering the IT industry in a helpdesk support role.*

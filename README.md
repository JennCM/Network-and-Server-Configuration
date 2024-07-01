# Network-and-Server-Configuration
Case project on configuring a secured Windows server that ensures the client's data is private.

# Project: Contoso Pharmaceuticals Network and Server Configuration

# Project Overview:
Contoso Pharmaceuticals, a global medical research company with 5000 employees, required a secure and efficient IT infrastructure to ensure the privacy of medical records and data. I was tasked with designing and implementing a robust Windows Server and Windows client infrastructure to meet their needs.

# Tools and Technologies Used:
•	Operating Systems: Windows Server, Windows Client

•	Server Roles: Active Directory, DHCP, DNS, Hyper-V, WSUS, iSCSI

•	Group Policy Management

•	Networking: DHCP Scopes, Superscope, Multicast Scope

•	Storage: Storage Pools, Virtual Disks

# Key Responsibilities and Achievements:

### Active Directory Installation:

•	Installed and configured a domain called `yourname.local` on Server Core.

•	Promoted the server to a Domain Controller (Figure 1, Figure 2).


### Group Policy Configuration:

•	Configured Group Policy to enforce a password change policy every 30 days (Figure 6, Figure 9).

### DHCP Server Installation and Configuration:

•	Installed the DHCP server role and configured four scopes for different locations: `TorontoLab`, `TorontoOffice`, `MontrealLab`, `MontrealOffice`.

•	Created a Superscope for Montreal and a Multicast scope (Figures 10-23).

### DNS Server Setup:

•	Configured the domain DNS server to forward all requests to Google's public DNS (8.8.8.8) (Figure 25).

### Storage Management:

•	Created a storage pool and a virtual disk for high availability (Figures 26-28).

•	Configured an iSCSI disk on Server 2 and attached it to Server 3 (Figure 29).


### Hyper-V Implementation:

•	Installed Hyper-V roles on Server 2 and Server 3.

•	Created and configured virtual machines and set up Hyper-V Replica for disaster recovery.


### WSUS Deployment:
•	Installed and configured Windows Server Update Services (WSUS).

•	Enforced WSUS settings through Group Policy to ensure clients receive timely updates without the option to pause them (Figures 30-33).



# Problem Solved:
The project addressed the critical need for a secure, scalable, and manageable IT infrastructure capable of supporting Contoso Pharmaceuticals' global operations. By implementing these solutions, we enhanced the security and efficiency of their network, ensured compliance with data privacy regulations, and provided a robust framework for future growth and scalability.


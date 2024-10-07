# FSLogix-Project

# Azure Virtual Desktop (AVD) Setup with FSLogix Profile Container

This guide covers the end-to-end process of setting up an Azure Virtual Desktop (AVD) environment using FSLogix Profile Containers for profile management. This includes configuring Active Directory Domain Services (ADDS), Azure AD Connect, creating a file share, setting up permissions, and installing FSLogix.

## Key Steps Covered:
1. **Creating a VM and Installing & Configuring ADDS & AD Connect:**
   - Set up a Virtual Machine (VM) and install ADDS and AD Connect to join Azure Entra ID (formerly Azure AD) for directory synchronization and authentication.
   
2. **Installing Active Directory Domain Services (ADDS) and AD Connect:**
   - Walkthrough for setting up ADDS and AD Connect to sync your on-premises directory with Azure AD.

3. **Creating Users and Security Groups:**
   - Create necessary Active Directory users and security groups that will be used for file share access and AVD deployment.

4. **Creating a File Share and Joining the Domain Controller:**
   - Set up a file share in Azure storage and ensure it is joined to the domain to support FSLogix profile storage.

5. **Creating a Virtual Machine for AVD:**
   - Step-by-step instructions on how to create a virtual machine in Azure tailored for the AVD environment.

6. **Setting Permissions:**
   - Set the required NTFS and file share permissions to allow users to access their profiles on the file share.

7. **Installing and Configuring FSLogix:**
   - Install FSLogix and configure it to use Profile Containers for seamless profile management across AVD sessions.

## References:
For detailed instructions on configuring FSLogix Profile Container with Azure Files and Active Directory, please refer to the official Microsoft documentation:
[Microsoft Documentation - Configure FSLogix Profile Container with Azure Files](https://learn.microsoft.com/en-us/azure/virtual-desktop/fslogix-profile-container-configure-azure-files-active-directory?tabs=aadds)


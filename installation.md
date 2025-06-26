# Installation

## Step 1: Prepare the Virtual Machine
- Change the hostname of the machine to something recognizable (e.g., `DC1`).
- Change the network mode from NAT to Bridge so it can communicate with other devices.

## Step 2: Install AD DS Role
1. Open **Server Manager**.
2. Click **Add roles and features**.
3. Follow the wizard:
   - **Installation Type**: Role-based
   - **Server Selection**: Choose local server
   - **Server Roles**: Check "Active Directory Domain Services"
   - Accept additional features if prompted
   - Leave features as-is, click **Next**
   - Check box for automatic restart
   - Click **Install**

Once complete, you'll see "Configuration required" under the AD DS role.

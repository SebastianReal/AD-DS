# Configuration

## Step 1: Promote Server to Domain Controller
1. In **Server Manager**, click the warning icon.
2. Select **Promote this server to a domain controller**.
3. In the wizard:
   - Choose **Add a new forest**
   - Set root domain name (e.g., `mydomain.local`)
   - Keep default forest/domain levels
   - Set Directory Services Restore Mode (DSRM) password
   - Accept DNS warning
   - Leave default paths
   - Review and click **Install**

System will reboot. The machine is now a domain controller with DNS.

## Step 2: Add a Second Domain Controller (Optional but Recommended)
- Repeat the steps on a second VM (e.g., `DC2`), but select **Add a domain controller to an existing domain**.
- Ensure `DC2` uses `DC1` for DNS.
- Choose replication source as "Any domain controller"

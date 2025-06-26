# Administration

## Active Directory Tools
Access from **Server Manager > Tools**:
- **AD Administrative Center**: Modern UI for managing AD
- **AD Users and Computers**: Classic interface for daily tasks
- **AD Sites and Services**: Manage physical site topology
- **AD Domains and Trusts**: Handle domain hierarchy and trust relationships

## FSMO Roles
- Domain roles: RID, PDC Emulator, Infrastructure
- Forest roles: Schema Master, Domain Naming Master
- Use UI or MMC Snap-ins to view/change roles

## Delegating Permissions
- Use **Advanced Features** in ADUC to manually set granular permissions
- Use **Delegation of Control Wizard** for common tasks (e.g., reset passwords)

## Managing Users and Groups
- Create users under OUs, not the default Users container
- Use templates for repeatable setups
- Assign permissions via groups, not individual users

## Organizational Units (OUs)
- Represent logical containers for objects
- Used to apply group policies and delegate control

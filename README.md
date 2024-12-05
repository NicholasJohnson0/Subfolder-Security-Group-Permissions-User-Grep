# Subfolder-Security-Group-Permissions-User-Grep

This program allows for administrators in a windows server environment the ability to audit security and group permissions in an Active Directory environment.

For this particular implementation, it utilizes icalcs to obtain folder security permissions and then runs a powershell script to get the specific users from each Domain Controller security group. If there is no security group on the domain, such as a local security group, then it will not print users.

# Map Network Drive

Check the share folder name from /etc/samba/smb.conf
For example, call it "folder_share_from_smb"


In Windows Explorer, Add a network location
Internet or network address:
Input \\192.168.1.x\folder_share_from_smb
You will be asked to create a name for this shortcut

== Problem ==
Windows cannot access \\192.168.x.x\folder_share_from_smb

# Type \\ip_address directly on the bar in Windows Explorer
Works, show nobody and folder_share_from_smb
Still cannot access folder_share_from_smb

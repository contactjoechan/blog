# User management
|   Info   | Display | Add | Update | Delete |
| --- | --- | --- | --- |--- |
| user |  |  |  |  |
| user group | | | | |

user
user details
user group
user group includes
password
permission of a folder
permission of a file

# List user
/etc/passwd

# Determine the usergroup of guestshare
groups guestshare


# List users in the usergroundA group
getent group usergroupA


# Grant guestshare access to the media folder
sudo usermod -aG www-data guestshare


# Password
update
sudo passwd user_name

## Update file permission
chmod 777 filename

## Update folder permission
chmod -R 777 foldername

sudo adduser new_user

# IP Device name
nslookup
ping
nmap

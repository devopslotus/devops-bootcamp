# Users & Permissions
## User Accounts
### 3 User Categories
- Superuser Account: 
> Root User - unrestricted permissions
- User Account:
> A regular user we create to login
- Service Account: 
> Relevant for Linux Server Distros - Each service will get its own user
 	-best practice for Security -Never run services with root user!
## Groups
### How to Manage permissions
- User Level:
> Give permissions to User directly
- Group Level:
> Group Users into Linus Groups
> Give permissions to the Group
> The way to go, if you manage multiple Users
## Linux Commands for Managing Users and their permissions
-`adduser``addgroup` `deluser` `delgroup` vs `useradd` `groupadd` `userdel` `groupdel`
### Adding user to secondary groups
 `usermod -g` = modifies users primary group
 `usermod -G` = adds user to a secondary group
 `usermod -aG`= append new groups to existing group
 `useradd [OPTIONS] <username>` = creeates new user with predefine modifcations
 > the low-level command compared to `adduser`
 > -G vreate user with multiple secondary groups
 > -d custom home directory
 > and other options for shell, etc.
## File Permissions and Ownership
* Everthing in Linux is a file *
### Ownership
- Who owns the file/directory?
> Owner is the user, qho created the file
> Owning group is the primary group of that user
### Changing ownership and permissions
 `chown` → change ownership
 `chown [username]:[groupname] <filename>` = changes the user and group
 `chown [username] <filename>` = changes the user only
 `chgrp [groupname]` = changes group
 `chmod` → change mod. eg:
  `chmod -x [filename] `= removes execution permission
#### Absolute (Numeric) Mode
	Number		Permission Type		Symbol
	0		No permission		---
	1		Execute			--x
	2		Write			-w-
	3		Write+Execute		-wx
	4		Read			r--
	5		Read+Execute		r-x
	6		Read+Write		rw-
	7		Read+Write+Execute	rwx

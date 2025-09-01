# Week 1: Linux Basics
## Navigation
- `pwd` → shows current directory
- `ls -a` → Show all (including hidden)
- `ls -lah` → lists all files with details and human-readable sizes
- `ls path/to/dir` → display files or contents from any directory
- `ls -R` → display all contents in all folders in the directory
- `cd /path/to/dir` → change directory using absolute path
## Files & Directories
- `mkdir` → creates folder
- `touch [filename]` → creates [filename]
- `rm [filename]` → deletes [filename]
- `rm -r [dirname]` → deletes folder
- `mv [filename] [new_filename]` → rename file
- `cp -r [dirname] [new_dirname]` → copy contents of a folder to a new folder
- `cp [filename] [new_filename]` → copy file to create to create a new file
## File Content
- `cat [filename]` → display file content
- `vim [filename]` → open file in vim editor
## Search
- `find / -name "file.txt"` → search for a file
- `grep "pattern" filename` → search for text inside file
## System Info
- `uname -a` → show system and kernel
- `lscpu` → show cpu information
- `lsmem` → show memory infomation
## Permissions & Users
- `sudo`→ run with root privileges
- `sudo adduser [username]` → creates new user [username]
- `sudo apt install [software]` → installs [software]
## Useful Shortcuts
- `CTRL + C` → stop current command
- `CTRL + SHIFT + C\V` → copy and paste inside terminal
## Vim Basics
- `i` → insert mode
- `esc` → exit instert mode to command mode
- `dd` → deletes entire line
- `u` → undo changes
- `A` → jump to end of line and switch to insert mode
- `/pattern` → search text 
- `:%s/old/new` → replaces string name with new name
- `:wq` → save changes
- `:q!` → discard changes

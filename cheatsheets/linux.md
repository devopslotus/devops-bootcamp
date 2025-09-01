# Week 1: Linux Basics
## Navigation
- `pwd` → shows current directory
- `ls -a` → Show all (including hidden)
- `ls -lah` → lists all files with details and human-readable sizes
- `ls path/to/dir` → display files or contents from any directory
- `ls -R` → display all contents in all folders in the directory
- `mkdir` → creates folder
- `cd /path/to/dir` → change directory using absolute path
- `touch [filename]` → creates [filename]
- `rm [filename]` → deletes [filename]
- `find / -name "file.txt"` → search for a file
- `rm -r [dirname]` → deletes folder
- `mv [filename] [new_filename]` → rename file
- `cp -r [dirname] [new_dirname]` → copy contents of a folder to a new folder
- `cp [filename] [new_filename]` → copy file to create to create a new file
- `cat [filename]` → display file content
## Useful Commands
- `CTRL + C` → stop current command
- `CTRL + SHIFT + C\V` → copy and paste inside terminal
- `uname -a` → show system and kernel
- `lscpu` → show cpu information
- `lsmem` → show memory infomation
## Sudo Commands
- `sudo`→ gives root security privileges
- `sudo adduser [username]` → creates new user [username]
- `sudo apt install [software]` → installs [software]
## Vim Editor
- `vim [filename]` → open [filename] in vim editor
- i → insert mode
- esc → exit instert mode to command mode
- dd → deletes entire line
- u → undo changes
- A → jump to end of line and switch to insert mode
- /pattern → search for pattern 
- :%s/old/new → replaces string name with new name
- :wq → save changes
- :q! → discard changes

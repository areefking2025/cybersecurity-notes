# 🐧 Linux Basics for Cybersecurity

> Essential Linux commands every SOC Analyst must know

## Why Linux is Important?
90% of hacking tools and servers run on Linux. As a SOC Analyst, you must know Linux.

## 📂 Basic Commands

### 1. Navigation
- `pwd` - Show current directory (Present Working Directory)
- `ls` - List files in folder
- `ls -la` - List all files including hidden
- `cd /home` - Go to home folder
- `cd ..` - Go back one folder

### 2. File Management
- `touch file.txt` - Create new empty file
- `mkdir myfolder` - Create new folder
- `cat file.txt` - Read file content
- `rm file.txt` - Delete file
- `rm -r myfolder` - Delete folder
- `cp file1 file2` - Copy file
- `mv file1 file2` - Move / Rename file

### 3. Important Commands for Hacking
- `whoami` - Who am I logged in as
- `id` - Show user id and groups
- `ifconfig` / `ip a` - Show IP address
- `ps aux` - Show running processes
- `netstat -tulpn` - Show open ports
- `chmod +x file.sh` - Make file executable

### 4. Searching & Finding
- `find / -name password.txt` - Find file anywhere
- `grep "password" file.txt` - Search word inside file
- `history` - See previous commands

## 🔥 My Practice
Today I practiced all these commands on TryHackMe Linux room.

## 🎯 Next Goal
Learn more about file permissions and networking commands.

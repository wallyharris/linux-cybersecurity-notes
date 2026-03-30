# Linux for Cybersecurity Notes

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Progress: Module 1](https://img.shields.io/badge/Progress-Module%201-blue.svg)

This repository contains my study notes and practical exercises from a Linux for Cybersecurity course, focusing on system administration, command line usage, and security fundamentals.

## 🎯 Objective

Document hands-on learning in Linux, building a strong foundation for cybersecurity applications.

## 📚 Contents

### Module 01 - Filesystem and Commands

#### Terminal Basics
- `pwd` → shows current directory  
  ![pwd](assets/pwd.png)
- `whoami` → shows current user  
  ![whoami](assets/whoami.png)
- `hostname` → shows machine name  
  ![hostname](assets/hostname.png)

#### Directory Navigation
- `ls` → list files  
  ![ls](assets/ls.png)
- `ls -l` → detailed list  
  ![ls_l](assets/ls_l.png)
- `ls -lh` → human-readable sizes  
  ![ls_lh](assets/ls_lh.png)
- `cd /` → go to root  
  ![cd_root](assets/cd_root.png)
- `cd ~` → go to home  
  ![cd_home](assets/cd_home.png)
- `cd ..` → go to parent directory  
  ![cd_parent](assets/cd_parent.png)
- `mkdir test-folder` → create directory  
  ![mkdir_test](assets/mkdir_test.png)
- `tree` → show directory tree  
  ![tree](assets/tree.png)
- `tree -L 1` → tree with depth 1  
  ![tree_L1](assets/tree_L1.png)

#### File Manipulation
- `touch file1.txt` → create empty file  
  ![touch_file](assets/touch_file.png)
- `echo "Hello World" > file1.txt` → write to file  
  ![echo_file](assets/echo_file.png)
- `cat file1.txt` → view file  
  ![cat_file](assets/cat_file.png)
- `nano file1.txt` → edit file  
  ![nano_file](assets/nano_file.png)
- `cp file1.txt file2.txt` → copy file  
  ![cp_file](assets/cp_file.png)
- `mv file2.txt file3.txt` → move/rename file  
  ![mv_file](assets/mv_file.png)
- `rm file3.txt` → delete file  
  ![rm_file](assets/rm_file.png)

#### File Permissions
- `ls -l` → view permissions  
  ![ls_permissions](assets/ls_permissions.png)
- `chmod 700 file1.txt` → set owner-only permissions  
  ![chmod_700](assets/chmod_700.png)
- `chmod +x file1.txt` → add execute permission  
  ![chmod_plusx](assets/chmod_plusx.png)
- `chmod -r file1.txt` → remove read permission  
  ![chmod_minusr](assets/chmod_minusr.png)

#### Terminal Shortcuts
- `Ctrl+C` → interrupt command  
- `Ctrl+L` → clear screen  
- `Ctrl+R` → search history  
- `Ctrl+Z` → suspend process  
- `!!` → execute last command

---

## 🛠️ Technologies

- Linux (Ubuntu)
- Bash
- VirtualBox

## 📂 Project Structure

# Module 01 – Filesystem & Commands

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Progress: Module 1](https://img.shields.io/badge/Progress-Module%201-blue.svg)

This module contains my study notes from the first part of the Linux for Cybersecurity course, focusing on filesystem, basic commands, terminal usage, and file permissions.

## 🎯 Objective

Document hands-on learning in Linux, covering terminal navigation, file manipulation, permissions, and useful shortcuts.

---

## 📚 Lessons

### 01 – Introduction
- Overview of Linux importance for cybersecurity
- Course structure and topics
- Instructor experience (Lucas Lemes, Cybersecurity Analyst)

### 02 – Installation
- Installing Ubuntu LTS in VirtualBox
- Setting language, keyboard, user account, password, and timezone
- Introduction to Ubuntu interface and terminal

### 03 – Intro to Terminal
- Terminal elements: username, hostname, current directory
- Commands: `sudo su`, `exit`, `clear`, `pwd`

### 04 – Terminal Shortcuts
- Tab → autocomplete commands
- Ctrl+C → stop command
- Ctrl+L → clear screen
- Ctrl+R → search history
- !! → execute last command
- Ctrl+Z → suspend process, resume with `fg`

### 05 – Directory Navigation
- `pwd` → current directory ![pwd](../../assets/pwd.png)
- `ls` → list files ![ls](../../assets/ls.png)
- `ls -l` → detailed list ![ls_l](../../assets/ls_l.png)
- `ls -lh` → human-readable sizes ![ls_lh](../../assets/ls_lh.png)
- `cd /` → go to root ![cd_root](../../assets/cd_root.png)
- `cd ~` → go to home ![cd_home](../../assets/cd_home.png)
- `cd ..` → go to parent ![cd_parent](../../assets/cd_parent.png)
- `mkdir test-folder` → create folder ![mkdir_test](../../assets/mkdir_test.png)
- `tree` → directory tree ![tree](../../assets/tree.png)
- `tree -L 1` → tree depth 1 ![tree_L1](../../assets/tree_L1.png)

### 06 – FHS (Filesystem Hierarchy)
- `/boot`, `/cdrom`, `/dev`, `/etc`, `/home`, `/media`, `/mnt`, `/opt`, `/proc`, `/root`, `/run`, `/srv`, `/tmp`, `/usr`, `/var`
- Understanding folder purpose is crucial for administration and security

### 07 – File Manipulation
- `touch file1.txt` → create file ![touch_file](../../assets/touch_file.png)
- `echo "Hello World" > file1.txt` → write to file ![echo_file](../../assets/echo_file.png)
- `cat file1.txt` → view file ![cat_file](../../assets/cat_file.png)
- `nano file1.txt` → edit file ![nano_file](../../assets/nano_file.png)
- `cp file1.txt file2.txt` → copy file ![cp_file](../../assets/cp_file.png)
- `mv file2.txt file3.txt` → move/rename file ![mv_file](../../assets/mv_file.png)
- `rm file3.txt` → delete file ![rm_file](../../assets/rm_file.png)

### 08 – File Permissions
- `ls -l` → view permissions ![ls_permissions](../../assets/ls_permissions.png)
- `chmod 700 file1.txt` → owner-only permissions ![chmod_700](../../assets/chmod_700.png)
- `chmod +x file1.txt` → add execute permission ![chmod_plusx](../../assets/chmod_plusx.png)
- `chmod -r file1.txt` → remove read permission ![chmod_minusr](../../assets/chmod_minusr.png)

---

## 📝 Key Learnings – Module 1
- Basic terminal navigation and commands
- Filesystem Hierarchy (FHS)
- Creating, editing, copying, moving, and deleting files
- Changing file permissions with `chmod`
- Useful terminal shortcuts for efficiency

---

## 🛠️ Technologies

- Linux (Ubuntu)
- Bash
- VirtualBox

## 🤝 Contributing

Feel free to open issues or submit pull requests to improve notes, add examples, or scripts.

## 📄 License

This project is licensed under the MIT License.
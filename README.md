# 🐧 50 Linux Commands You Should Know  
**Unleash your Linux prowess with these 50 must-know commands.**  
From file manipulation to network configuration, master the essentials for efficient system management.  
Boost productivity and navigate the Linux operating system like a pro.  
Perfect for beginners and seasoned users alike.  

📘 **By:** CodeWithHarry  
📅 **Updated:** April 5, 2025  

---

## 📂 File and Directory Management

| Command | Description | Example |
|----------|--------------|----------|
| `ls` | List files and directories | `ls` |
| `cd` | Change the current directory | `cd dir_name` |
| `mkdir` | Create a new directory | `mkdir rohan` |
| `rmdir` | Remove a directory | `rmdir rohan` |
| `pwd` | Print current working directory | `pwd` |
| `cp` | Copy files or directories | `cp example.txt backup/` |
| `mv` | Move or rename files or directories | `mv example.txt backup/` |
| `rm` | Remove files or directories | `rm example.txt` |
| `touch` | Create empty file or update timestamp | `touch shayan.txt` |
| `cat` | Display contents of a file | `cat example.txt` |

---

## 📖 Help and Permissions

| Command | Description | Example |
|----------|--------------|----------|
| `man` | Manual for a command | `man ls` |
| `htop` | Interactive process viewer | `htop` |
| `chmod` | Change file permissions | `chmod 700 file.txt` |
| `chown` | Change file owner | `chown new_owner example.txt` |

> **chmod permissions:**  
> - 0: no permission  
> - 1: execute only  
> - 2: write only  
> - 3: write + execute  
> - 4: read only  
> - 5: read + execute  
> - 6: read + write  
> - 7: read + write + execute  

---

## 🗜️ Compression and Archiving

| Command | Description | Example |
|----------|--------------|----------|
| `tar` | Create or extract archives | `tar cf archive.tar file1 file2 file3` |
| `gzip` | Compress files | `gzip file.txt` |
| `gunzip` | Decompress files | `gunzip file.txt.gz` |

---

## 🌐 Networking

| Command | Description | Example |
|----------|--------------|----------|
| `ssh` | Secure remote login | `ssh username@server_address` |
| `scp` | Securely copy between systems | `scp myfile.txt user@remotehost:/home/user/` |
| `ping` | Test network connectivity | `ping 8.8.8.8` |
| `ifconfig` | Configure network interfaces | `ifconfig` |
| `netstat` | Display network connections | `netstat` |
| `route` | Manage routing tables | `route add default gw 192.168.1.1` |

---

## ⚙️ System Monitoring and Management

| Command | Description | Example |
|----------|--------------|----------|
| `top` | Display running processes | `top` |
| `ps` | Display process info | `ps aux` |
| `kill` | Terminate a process | `kill [PID]` |
| `systemctl` | Control system services | `systemctl start nginx` |
| `service` | Manage services | `service apache2 start` |

---

## 👤 User Management

| Command | Description | Example |
|----------|--------------|----------|
| `useradd` | Add a new user | `useradd harry` |
| `passwd` | Change user password | `passwd harry` |
| `userdel` | Delete a user | `userdel harry` |
| `su` | Switch user | `su john` |
| `sudo` | Execute command as superuser | `sudo apt update` |

---

## 💾 System and Disk Usage

| Command | Description | Example |
|----------|--------------|----------|
| `uptime` | Show system uptime | `uptime` |
| `df` | Display disk space usage | `df -h` |
| `du` | Disk usage of directories/files | `du -sh *` |
| `mount` | Mount a file system | `sudo mount /dev/sdb1 /mnt/usb` |
| `umount` | Unmount a file system | `sudo umount /mnt/usb` |

---

## 🕒 System Info and Utilities

| Command | Description | Example |
|----------|--------------|----------|
| `date` | Show or set system date/time | `date` |
| `whoami` | Display current username | `whoami` |
| `which` | Locate program in PATH | `which ls` |
| `finger` | Show info about a user | `finger harry` |
| `uname` | Show system info | `uname -a` |
| `history` | Show command history | `history` |

---

## 🧰 Text and File Operations

| Command | Description | Example |
|----------|--------------|----------|
| `echo` | Print text or variables | `echo 'I need Tshirt from codeswear!'` |
| `tee` | Write output to file + console | `ls | tee file.txt` |
| `locate` | Find file on system | `locate file.txt` |
| `sort` | Sort lines in a file | `sort file.txt` |
| `uniq` | Remove duplicate lines | `uniq file.txt` |
| `head` | Show first lines of a file | `head file.txt` |
| `tail` | Show last lines of a file | `tail file.txt` |

---

## 🧠 Pro Tip

> Practice these commands daily — start with file navigation, then permissions, and finally process/network management.  
> Within a few weeks, you'll handle Linux like a pro 💪  

---

✨ **Keep Learning, Keep Building!**  
Made with ❤️ by **Chinmay**

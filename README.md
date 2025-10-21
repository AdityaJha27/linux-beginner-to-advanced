# linux-beginner-to-advanced
Learing for ethical hacking 

# 🐧 30 Days of Linux — Beginner to Advanced

Welcome to the **30 Days Linux Command Challenge** 🎯  
This plan will take you from **absolute beginner to advanced Linux user** step by step.  
Each day introduces new Linux commands with **meaning, example, and output**.

---

## 📅 Day 1 — Basic Navigation

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `pwd` | Print working directory | `pwd` | `/home/adityadev` |
| `ls` | List files and directories | `ls` | `Desktop Documents Downloads Music` |
| `cd folder` | Change directory | `cd Documents` | Moves to Documents |
| `cd ..` | Move back one directory | `cd ..` | Moves to parent folder |
| `clear` | Clear the terminal | `clear` | Screen cleared |

---

## 📅 Day 2 — File and Directory Management

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `mkdir foldername` | Create new folder | `mkdir Projects` | Folder created |
| `rmdir foldername` | Remove empty folder | `rmdir Projects` | Folder deleted |
| `touch file.txt` | Create empty file | `touch notes.txt` | File created |
| `rm file.txt` | Delete file | `rm notes.txt` | File removed |
| `cp file1 file2` | Copy file | `cp a.txt b.txt` | File copied |
| `mv file1 file2` | Move or rename file | `mv old.txt new.txt` | File moved/renamed |

---

## 📅 Day 3 — Viewing File Contents

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `cat file.txt` | Show file content | `cat hello.txt` | `Hello Linux World!` |
| `less file.txt` | Scrollable view | `less hello.txt` | Scroll file |
| `head file.txt` | Show first 10 lines | `head hello.txt` | Top 10 lines |
| `tail file.txt` | Show last 10 lines | `tail hello.txt` | Last 10 lines |
| `nl file.txt` | Show numbered lines | `nl hello.txt` | Lines numbered |

---

## 📅 Day 4 — File Permissions & Ownership

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `ls -l` | Show file permissions and ownership | `ls -l` | `-rw-r--r-- 1 adityadev adityadev 35 Oct 21 14:30 hello.txt` |
| `chmod 755 file.sh` | Change file permission | `chmod 755 script.sh` | File executable |
| `chown user file.txt` | Change file owner | `sudo chown adityadev notes.txt` | Owner changed |
| `chgrp group file.txt` | Change file group | `sudo chgrp devs notes.txt` | Group changed |

---

## 📅 Day 5 — System Information

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `uname -a` | Show system info | `uname -a` | Kernel, OS info |
| `hostname` | Show system hostname | `hostname` | `Ubuntu-24` |
| `uptime` | System running time | `uptime` | `up 2:15, 1 user` |
| `whoami` | Current user | `whoami` | `adityadev` |
| `date` | Show current date & time | `date` | `Tue Oct 21 10:00` |

---

## 📅 Day 6 — Disk & Memory Usage

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `df -h` | Disk usage in human-readable | `df -h` | `/dev/sda1 50G 20G 30G 40% /` |
| `du -sh folder` | Folder size | `du -sh Downloads` | `1.5G Downloads` |
| `free -h` | RAM usage | `free -h` | `Mem: 8G 3G used 5G free` |
| `top` | Real-time process monitoring | `top` | CPU & RAM usage |
| `htop` | Advanced monitor | `htop` | Interactive display |

---

## 📅 Day 7 — Process Management

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `ps` | Show running processes | `ps` | List of processes |
| `ps aux` | All processes | `ps aux` | Detailed list |
| `kill PID` | Stop process by PID | `kill 1234` | Process killed |
| `pkill name` | Kill process by name | `pkill firefox` | Firefox stopped |
| `bg / fg` | Background / Foreground process | `bg` | Resume background |

---

## 📅 Day 8 — Package Management (APT)

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `sudo apt update` | Update package info | `sudo apt update` | Updates repo |
| `sudo apt upgrade` | Upgrade installed packages | `sudo apt upgrade` | Packages upgraded |
| `sudo apt install git` | Install software | `sudo apt install git` | Git installed |
| `sudo apt remove nano` | Remove software | `sudo apt remove nano` | Nano removed |
| `apt list --installed` | List installed packages | `apt list --installed` | Shows package list |

---

## 📅 Day 9 — User Management

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `adduser` | Add new user | `sudo adduser testuser` | User created |
| `deluser` | Delete user | `sudo deluser testuser` | User removed |
| `passwd` | Change password | `passwd` | Password changed |
| `who` | List logged-in users | `who` | `adityadev pts/0 ...` |
| `id username` | User ID info | `id adityadev` | `uid=1000(adityadev) ...` |

---

## 📅 Day 10 — Networking Basics

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `ping` | Test connection | `ping google.com` | Replies with time |
| `ifconfig` | Network config | `ifconfig` | IP, netmask, interface |
| `hostname -I` | Show IP | `hostname -I` | `192.168.1.10` |
| `curl` | Fetch web content | `curl example.com` | HTML response |
| `wget` | Download file | `wget https://file.zip` | File downloaded |

---

## 📅 Day 11 — Searching Files & Text

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `find / -name file.txt` | Find a file by name | `find / -name notes.txt` | Path of file |
| `grep "text" file.txt` | Search for text in file | `grep "Linux" hello.txt` | Line(s) containing "Linux" |
| `grep -i "text" file.txt` | Case-insensitive search | `grep -i "linux" hello.txt` | Lines with "linux"/"Linux" |
| `grep -r "text" folder/` | Recursive search in folder | `grep -r "error" /var/log` | Lines with "error" |
| `locate file.txt` | Quick search using database | `locate notes.txt` | File path |

---

## 📅 Day 12 — Viewing & Editing Files

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `nano file.txt` | Open file in nano editor | `nano hello.txt` | File editable |
| `cat > file.txt` | Write new content to file | `cat > test.txt` | Overwrites file |
| `cat >> file.txt` | Append content to file | `cat >> test.txt` | Adds to file |
| `more file.txt` | View file page by page | `more hello.txt` | Paginated view |
| `less file.txt` | Scrollable view | `less hello.txt` | Scrollable content |

---

## 📅 Day 13 — Advanced Permissions

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `chmod u+x file.sh` | Make file executable | `chmod u+x script.sh` | Executable set |
| `chmod 644 file.txt` | rw-r--r-- permissions | `chmod 644 notes.txt` | Permissions set |
| `chmod 777 file.txt` | Full permissions | `chmod 777 data.txt` | Full access |
| `chown user:group file.txt` | Change owner & group | `sudo chown adityadev:dev notes.txt` | Ownership changed |

---

## 📅 Day 14 — Disk & Storage

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `lsblk` | List block devices | `lsblk` | sda, sdb, partitions |
| `fdisk -l` | Show partition table | `sudo fdisk -l` | Partition info |
| `mount /dev/sdb1 /mnt` | Mount drive | `mount /dev/sdb1 /mnt` | Drive mounted |
| `umount /mnt` | Unmount drive | `umount /mnt` | Drive unmounted |

---

## 📅 Day 15 — Environment Variables

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `echo $HOME` | Show home path | `echo $HOME` | `/home/adityadev` |
| `echo $USER` | Show username | `echo $USER` | `adityadev` |
| `export VAR=value` | Set custom variable | `export MYNAME=Aditya` | Variable set |
| `printenv` | List all environment variables | `printenv` | List of variables |

---

## 📅 Day 16 — Command History & Aliases

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `history` | Show command history | `history` | List of previous commands |
| `!5` | Run 5th command from history | `!5` | Executes 5th command |
| `alias ll='ls -l'` | Create shortcut | `alias ll='ls -l'` | Shortcut created |
| `unalias ll` | Remove shortcut | `unalias ll` | Alias removed |

---

## 📅 Day 17 — Archiving & Compression

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `tar -cvf file.tar folder/` | Create tar archive | `tar -cvf backup.tar Projects/` | Archive created |
| `tar -xvf file.tar` | Extract tar archive | `tar -xvf backup.tar` | Extracted files |
| `gzip file.txt` | Compress file | `gzip notes.txt` | File compressed |
| `gunzip file.txt.gz` | Decompress file | `gunzip notes.txt.gz` | File decompressed |
| `zip file.zip folder/` | Create zip | `zip -r backup.zip Projects/` | Zip created |

---

## 📅 Day 18 — System Logs

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `dmesg` | Kernel messages | `dmesg` | Boot logs |
| `tail -f /var/log/syslog` | Live system log | `tail -f /var/log/syslog` | Real-time logs |
| `journalctl -xe` | Systemd logs | `journalctl -xe` | Detailed logs |
| `cat /var/log/auth.log` | Authentication logs | `cat /var/log/auth.log` | User login info |

---

## 📅 Day 19 — Cron Jobs & Scheduling

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `crontab -e` | Edit cron jobs | `crontab -e` | Opens cron file |
| `crontab -l` | List cron jobs | `crontab -l` | Shows scheduled tasks |
| `* * * * * command` | Run every minute | `* * * * * echo Hello` | Hello every minute |
| `systemctl status cron` | Check cron service | `systemctl status cron` | Active/Inactive |

---

## 📅 Day 20 — Networking Advanced

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `netstat -tuln` | Show listening ports | `netstat -tuln` | Active ports |
| `ss -tuln` | Modern netstat | `ss -tuln` | TCP/UDP connections |
| `ping -c 4 google.com` | Ping 4 times | `ping -c 4 google.com` | 4 replies |
| `traceroute google.com` | Network route | `traceroute google.com` | Hops info |
| `nslookup google.com` | DNS lookup | `nslookup google.com` | IP info |

---

## 📅 Day 21 — SSH & Remote Access

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `ssh user@ip` | Remote login | `ssh aditya@192.168.1.10` | Connects to remote |
| `scp file user@ip:/path` | Copy file remote | `scp notes.txt aditya@192.168.1.10:/home/aditya` | File copied |
| `rsync -av folder/ user@ip:/path` | Sync folders remote | `rsync -av Projects/ aditya@192.168.1.10:/home/aditya` | Synced |
| `exit` | Logout from SSH | `exit` | Back to local |

---

## 📅 Day 22 — Disk Quota & Usage

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `quota -v` | Show disk quota | `quota -v` | Disk usage report |
| `df -h` | Disk usage | `df -h` | `/dev/sda1 50G 20G 30G` |
| `du -sh folder/` | Folder size | `du -sh Projects/` | `1.2G Projects/` |
| `ncdu folder/` | Interactive disk usage | `ncdu Projects/` | GUI style usage |

---

## 📅 Day 23 — Bash Scripting Basics

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `#!/bin/bash` | Bash script shebang | Add at top of script | Sets interpreter |
| `echo "Hello"` | Print text | `echo "Hello Linux"` | Hello Linux |
| `read var` | Take input | `read name` | Stores input |
| `if [ condition ]; then ... fi` | Conditional | `if [ $num -gt 5 ]; then echo hi; fi` | Executes if true |
| `for i in {1..5}; do echo $i; done` | Loop | Prints 1–5 | 1 2 3 4 5 |

---

## 📅 Day 24 — Bash Scripting Advanced

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| Functions | Create function | `myfunc() { echo hi; }` | Call `myfunc` prints hi |
| Arrays | Store list | `arr=(a b c)` | Access `${arr[1]}` → b |
| `case` | Conditional choice | `case $var in a) ... ;; esac` | Executes matching block |
| `$?` | Exit status | `echo $?` | 0 if success |

---

## 📅 Day 25 — Services & Systemctl

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `systemctl start service` | Start service | `sudo systemctl start apache2` | Service started |
| `systemctl stop service` | Stop service | `sudo systemctl stop apache2` | Service stopped |
| `systemctl restart service` | Restart service | `sudo systemctl restart apache2` | Service restarted |
| `systemctl status service` | Check service | `sudo systemctl status apache2` | Active/Inactive |
| `systemctl enable service` | Auto-start service | `sudo systemctl enable apache2` | Enabled |

---

## 📅 Day 26 — Logs & Troubleshooting

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `journalctl -u service` | Service logs | `journalctl -u apache2` | Logs |
| `dmesg | tail` | Kernel messages | `dmesg | tail` | Last messages |
| `tail -f /var/log/syslog` | Live log | `tail -f /var/log/syslog` | Real-time log |
| `grep error /var/log/syslog` | Search errors | `grep error /var/log/syslog` | Lines with error |

---

## 📅 Day 27 — Networking Troubleshooting

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `ping` | Check connectivity | `ping google.com` | Replies |
| `traceroute` | Check route | `traceroute google.com` | Hops |
| `netstat -tuln` | Show ports | `netstat -tuln` | TCP/UDP |
| `ss -tuln` | Modern netstat | `ss -tuln` | Connections |
| `nslookup` | DNS info | `nslookup google.com` | IP |

---

## 📅 Day 28 — Backup & Restore

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `tar -czvf backup.tar.gz folder/` | Create compressed backup | `tar -czvf backup.tar.gz Projects/` | Backup created |
| `tar -xzvf backup.tar.gz` | Extract backup | `tar -xzvf backup.tar.gz` | Extracted files |
| `rsync -av source/ dest/` | Sync files | `rsync -av Projects/ Backup/` | Synced |
| `cp -r folder1 folder2` | Copy folder recursively | `cp -r Projects Projects_backup` | Copied |

---

## 📅 Day 29 — Security Basics

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `ufw status` | Check firewall | `ufw status` | Active/Inactive |
| `ufw enable` | Enable firewall | `sudo ufw enable` | Enabled |
| `ufw allow port` | Allow port | `sudo ufw allow 22` | SSH allowed |
| `chmod 700 file` | Secure file | `chmod 700 secret.sh` | Only owner access |
| `passwd` | Change user password | `passwd` | Password updated |

---

## 📅 Day 30 — Final Review & Pro Commands

| Command | Meaning | Example | Output |
|---------|--------|---------|--------|
| `alias` | Show all aliases | `alias` | List |
| `uname -r` | Kernel version | `uname -r` | `5.19.0-40-generic` |
| `uptime` | Check system uptime | `uptime` | `up 5 days` |
| `history` | Command history | `history` | Previous commands |
| `man command` | Open manual | `man ls` | Manual page |

---



⭐ **Made by [Aditya Jha](https://github.com/)**


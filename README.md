# 🐧 Basic Linux Commands

This repository provides a simple overview of **basic Linux/Unix shell commands**. It's intended as a quick reference guide for beginners or anyone learning the Linux command line.

## 📂 Table of Contents

- [📂 File and Directory Commands](#-file-and-directory-commands)
- [🛠️ System Information](#️-system-information)
- [📦 Package Management](#-package-management)
- [👥 User Management](#-user-management)
- [🔍 Search Commands](#-search-commands)
- [🔧 File Permissions](#-file-permissions)
- [📡 Networking](#-networking)
- [📑 Miscellaneous](#-miscellaneous)

---

## 📂 File and Directory Commands

| Command | Description |
|--------|-------------|
| `ls` | List files and directories |
| `pwd` | Print current working directory |
| `cd` | Change directory |
| `mkdir` | Create a new directory |
| `touch` | Create an empty file |
| `cp` | Copy files/directories |
| `mv` | Move or rename files/directories |
| `rm` | Remove files/directories |
| `tree` | Display directory structure in tree format (may need installation) |

---

## 🛠️ System Information

| Command | Description |
|--------|-------------|
| `uname -a` | Show kernel and system information |
| `top` | Display real-time system processes |
| `htop` | Interactive process viewer (may need installation) |
| `df -h` | Show disk space usage |
| `free -h` | Show memory usage |
| `uptime` | Show system uptime |
| `whoami` | Show current user |
| `id` | Show user and group info |

---

## 📦 Package Management

### Debian/Ubuntu-based

| Command | Description |
|--------|-------------|
| `sudo apt update` | Update package index |
| `sudo apt upgrade` | Upgrade installed packages |
| `sudo apt install <pkg>` | Install a package |
| `sudo apt remove <pkg>` | Remove a package |

### RedHat/CentOS-based

| Command | Description |
|--------|-------------|
| `yum install <pkg>` | Install a package |
| `dnf update` | Update packages (newer systems) |

---

## 👥 User Management

| Command | Description |
|--------|-------------|
| `adduser <name>` | Add a new user |
| `passwd <name>` | Change user password |
| `who` | Show who is logged in |
| `su - <user>` | Switch to another user |
| `sudo <cmd>` | Run a command as superuser |

---

## 🔍 Search Commands

| Command | Description |
|--------|-------------|
| `find <path> -name <file>` | Find files by name |
| `grep <text> <file>` | Search for text in a file |
| `locate <file>` | Find files using database |
| `which <cmd>` | Show full path of a command |

---

## 🔧 File Permissions

| Command | Description |
|--------|-------------|
| `chmod` | Change file permissions |
| `chown` | Change file owner |
| `ls -l` | Show file permissions in long format |

---

## 📡 Networking

| Command | Description |
|--------|-------------|
| `ifconfig` / `ip a` | Show network interfaces |
| `ping <host>` | Test connectivity |
| `netstat -tulnp` | List open ports and services |
| `curl <url>` | Fetch content from URL |
| `wget <url>` | Download file from web |

---

## 📑 Miscellaneous

| Command | Description |
|--------|-------------|
| `man <cmd>` | Show manual for a command |
| `history` | Show command history |
| `clear` | Clear terminal screen |
| `alias` | Create shortcuts for commands |

---

## 🧠 Tips

- Use `TAB` to auto-complete file/folder names.
- Use `Ctrl + C` to stop a running command.
- Use `Ctrl + L` to clear terminal.
- Use `!!` to repeat the last command.

---

## 📌 Note

To get help with any command:

```bash
man <command>
# or
<command> --help

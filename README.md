# Linux Basics Guide

Welcome to the Linux Basics Guide repository! This guide is designed to help you understand and use essential Linux commands. Each command is explained in simple language with examples to make learning easy.

# Table of Contents

1. [sudo](#sudo)
2. [apt](#apt)
3. [mkdir](#mkdir)
4. [cd](#cd)
5. [ls](#ls)
6. [nano](#nano)
7. [wget](#wget)
8. [curl](#curl)
9. [bash](#bash)
---

## sudo
### Full Form: Super User Do

The sudo command allows you to run programs with the security privileges of another user, typically the superuser (root). This is useful when you need to perform administrative tasks that require higher permissions.

### Usage:
```bash
sudo [command]
```

### Examples:
```bash
sudo apt update
```
This command updates the list of available packages and their versions, but it does not install or upgrade any packages.

```bash
sudo reboot
```
This command restarts the computer immediately.

---

## apt
### Full Form: Advanced Package Tool

The apt command is used to manage software packages on Ubuntu/Debain systems. You can install, update, upgrade, and remove software packages using apt.

### Usage:
```bash
apt [options] [command]
```

### Examples:
```bash
sudo apt install nano
```
This command installs the nano text editor on your system.

```bash
sudo apt removes nano
```
This command removes the nano text editor from your system.

---

## mkdir
### Full Form: Make Directory

The mkdir command is used to create new directories (folders) in the file system.

### Usage:
```bash
mkdir [directory_name]
```

### Examples:
```bash
mkdir my_new_directory
```
This command creates a directory named my_new_directory.

```bash
mkdir -p parent/child
```
This command creates a nested directory structure with parent as the parent directory and child as a subdirectory inside parent.

---

## cd
### Full Form: Change Directory

The cd command is used to change the current working directory in the terminal.

### Usage:
```bash
cd [directory_name]
```

### Examples:
```bash
cd my_new_directory
```
This command changes the current directory to my_new_directory.

```bash
cd ..
```
This command moves up one directory level to the parent directory.

---

## ls
### Full Form: List

The ls command lists the contents of a directory. It shows the files and directories within the specified directory.

### Usage:
```bash
ls [options] [directory]
```

### Examples:
```bash
ls
```
This command lists all files and directories in the current directory.

```bash
ls -l
```
This command lists all files and directories in the current directory in a detailed (long) format, showing permissions, number of links, owner, group, size, and time of last modification.

```bash
ls -a
```
This command lists all files and directories, including hidden ones (those that start with a dot .).

---

## nano
### Full Form: Nano's ANOther editor

The nano command opens the nano text editor, which is a simple, easy-to-use text editor for the command line.

### Usage:
```bash
nano [file_name]
```

### Examples:
```bash
nano myfile.txt
```
This command opens the file myfile.txt in the nano editor. If the file does not exist, nano will create it.

```bash
nano /etc/hosts
```
This command opens the system file hosts located in the /etc directory for editing.

---

## wget
### Full Form: World Wide Web get

The wget command is used to download files from the internet. It supports HTTP, HTTPS, and FTP protocols.

### Usage:
```bash
wget [options] [url]
```

### Examples:
```bash
wget http://example.com/file.zip
```
This command downloads the file from the specified URL to the current directory.

```bash
wget -O myfile.html http://example.com
```
This command downloads the content from http://example.com and saves it as myfile.html.

---

## curl
### Full Form: Client URL

The curl command is used to transfer data to or from a server. It supports various protocols including HTTP, HTTPS, FTP, and many others.

### Usage:
```bash
curl [options] [url]
```

### Examples:
```bash
curl http://example.com
```
This command fetches the content from the specified URL and displays it in the terminal.

```bash
curl -O http://example.com/file.zip
```
This command downloads the file from the specified URL and saves it with its original name.

---

## bash
### Full Form: Bourne Again SHell

bash is a command processor that typically runs in a text window where the user types commands that cause actions. It is the default shell on many Linux systems.

### Usage:
```bash
bash [script.sh]
```

### Examples:
```bash
bash myscript.sh
```
This command runs the shell script myscript.sh.

```bash
bash -c 'echo Hello, World!'
```
This command runs the command echo Hello, World! within a new instance of the bash shell.

---

# Contributing
Feel free to submit issues, fork the repository, and send pull requests. Contributions are welcome!

# License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

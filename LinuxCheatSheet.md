# Linux Command Cheat Sheet

## Basic Navigation
- `pwd` – Print current directory path
- `ls` – List directory contents
  - `ls -l` (detailed list), `ls -a` (show hidden files)
- `cd [directory]` – Change directory
  - `cd ..` (up one directory), `cd ~` (home directory)

## File and Directory Operations
- `mkdir [directory]` – Create a new directory
- `rmdir [directory]` – Remove an empty directory
- `rm [file]` – Delete a file
  - `rm -r [directory]` (delete directory and contents)
- `cp [source] [destination]` – Copy files or directories
  - `cp -r` (recursive for directories)
- `mv [source] [destination]` – Move or rename files

## Viewing and Editing Files
- `cat [file]` – View file contents
- `nano [file]` – Open a file in the Nano editor
- `touch [file]` – Create an empty file or update the timestamp

## Permissions and Ownership
- `chmod [permissions] [file]` – Change file permissions (e.g., `chmod 755 file`)
- `chown [user]:[group] [file]` – Change file owner and group

## Searching and Finding
- `grep [pattern] [file]` – Search for a pattern in a file
- `find [directory] -name [filename]` – Find files by name
- `locate [filename]` – Find file locations (use `sudo updatedb` to update database)

## System Information and Processes
- `top` – Display running processes
- `ps aux` – Show all running processes
- `kill [PID]` – Terminate a process by its PID
- `df -h` – Show disk space usage
- `free -m` – Show memory usage

## Networking
- `ping [hostname]` – Check connectivity to a host
- `ifconfig` or `ip addr` – Display IP addresses and network interfaces
- `netstat -tuln` – List listening ports and active connections

## Package Management (Debian/Ubuntu)
- `sudo apt update` – Update package list
- `sudo apt upgrade` – Upgrade all packages
- `sudo apt install [package]` – Install a package
- `sudo apt remove [package]` – Remove a package

## File Compression
- `tar -czvf [archive.tar.gz] [directory]` – Compress a directory into a `.tar.gz` file
- `tar -xzvf [archive.tar.gz]` – Extract a `.tar.gz` file

## System Management
- `sudo reboot` – Restart the system
- `sudo shutdown now` – Shut down the system immediately

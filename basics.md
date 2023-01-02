## System Information
- `uname`

Displays information about the current system, such as the kernel version and the hostname.
```  
uname -a
```
- `lsb_release`

Displays information about the current Linux distribution, such as the distribution name and version.
``` bash
lsb_release -a
```
- `df`

Displays information about the usage and availability of disk space on the system.
``` bash
df -h
```
- `free`

Displays information about the usage and availability of memory on the system.
```
free -m
```
## File Management
- `ls`

Shell command that lists files and directories within a directory

- `cp`

Copies a file from one location to another.
```
cp file.txt /path/to/destination/directory
```
- `mv`

Moves a file from one location to another, or renames a file.
```
mv file.txt /path/to/destination/directory
mv file.txt new_file_name.txt
```
- `rm`

Deletes a file.
```
rm file.txt
```
- `mkdir`

Creates a new directory.
```
mkdir new_directory
```
- `rmdir`

Deletes an empty directory.
```
rmdir empty_directory
```
## Process Management
- `ps`

Lists the processes running on the system.
```
ps -aux
```
- `top`

Displays information about the top processes running on the system, sorted by CPU usage.
```
top
```
- `kill`

Terminates a process by ID.
```
kill 12345
```
- `killall`

Terminates all processes with a given name.
```
killall process_name
```
## Networking
- `ping`

Sends a request to a specified host and displays the response time.
```
ping www.example.com
```
- `traceroute`
traceroute command in Linux prints the route that a packet takes to reach the host. This command is useful when you want to know about the route and about all the hops that a packet takes. Below image depicts how traceroute command is used to reach the Google(172.217.26.206) host from the local machine and it also prints detail about all the hops that it visits in between.

```
traceroute -6 google.com
```
- `dig`

Queries DNS servers for information about a domain.
```
dig example.com
```
- `netstat`

Displays active network connections and their status.
```
netstat -tulpn
```
## Security
- `chmod`

Changes the permissions of a file or directory.
```
chmod 755 file.txt
```
- `chown`

Changes the owner of a file or directory.
```
chown user:group file.txt
```
- `sudo`

Executes a command with root privileges.
```
sudo command
```
I hope this first file of this repository of Linux commands is helpful to you! If you have any questions or suggestions for other commands to include, feel free to contact me.

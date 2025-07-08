# System Information in Linux

Linux provides a variety of commands to display detailed information about the system, including hardware, kernel, memory, CPU, storage, network, and running processes. These commands are useful for troubleshooting, monitoring, and system administration.

---

## Common System Information Commands

| Command            | Description                                         | Example                        |
|--------------------|-----------------------------------------------------|--------------------------------|
| uname -a           | Show all system information                         | `uname -a`                     |
| hostname           | Show or set the system's host name                  | `hostname`                     |
| lsb_release -a     | Display Linux distribution information              | `lsb_release -a`               |
| cat /etc/os-release| Show OS version details                             | `cat /etc/os-release`          |
| uptime             | Show how long the system has been running           | `uptime`                       |
| whoami             | Display the current username                        | `whoami`                       |
| who                | Show who is logged on                               | `who`                          |
| w                  | Show who is logged on and what they are doing       | `w`                            |
| id                 | Display user and group information                  | `id`                           |
| top                | Display dynamic real-time system information        | `top`                          |
| htop               | Interactive process viewer (requires installation)  | `htop`                         |
| ps aux             | Report a snapshot of current processes              | `ps aux`                       |
| free -h            | Display memory usage                                | `free -h`                      |
| vmstat             | Report virtual memory statistics                    | `vmstat`                       |
| iostat             | Report CPU and I/O statistics                       | `iostat`                       |
| mpstat             | Report processors related statistics                | `mpstat`                       |
| pidstat            | Report statistics by process                        | `pidstat`                      |
| lscpu              | Display CPU architecture information                | `lscpu`                        |
| cat /proc/cpuinfo  | Display CPU information                             | `cat /proc/cpuinfo`            |
| lsblk              | List block devices (disks, partitions)              | `lsblk`                        |
| blkid              | Locate/print block device attributes                | `blkid`                        |
| df -h              | Display disk space usage in human-readable format   | `df -h`                        |
| du -sh /home/user  | Estimate file and directory space usage             | `du -sh /home/user`            |
| ifconfig           | Configure network interfaces (deprecated; use ip)   | `ifconfig`                     |
| ip a               | Show network interfaces                             | `ip a`                         |
| dmesg              | Print or control the kernel ring buffer             | `dmesg | less`                 |
| lsmod              | Show the status of modules in the Linux kernel      | `lsmod`                        |
| lspci              | List all PCI devices                                | `lspci`                        |
| lsusb              | List all USB devices                                | `lsusb`                        |
| dmidecode          | Display hardware information from the BIOS          | `sudo dmidecode`               |

---

> **Tip:**  
> Use the `man` command (e.g., `man uname`) to learn more about any
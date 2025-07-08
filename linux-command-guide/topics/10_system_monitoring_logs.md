# System Monitoring and Logs

System monitoring and log analysis are essential for maintaining system health, troubleshooting issues, and optimizing performance. Linux provides a variety of commands to monitor system resources and view logs.

---

## Common System Monitoring and Log Commands

| Command         | Description                                                      | Example                                 |
|-----------------|------------------------------------------------------------------|-----------------------------------------|
| dmesg           | Print or control the kernel ring buffer                          | `dmesg | less`                          |
| journalctl      | Query the systemd journal                                        | `journalctl -xe`                        |
| tail -f         | Follow a file in real-time                                       | `tail -f /var/log/syslog`               |
| syslog          | System log file (location: /var/log/syslog or /var/log/messages) | `cat /var/log/syslog`                   |
| vmstat          | Report virtual memory statistics                                 | `vmstat`                                |
| sar             | Collect and report system activity information                   | `sar -u 1 3`                            |
| iostat          | Report CPU and I/O statistics                                    | `iostat`                                |
| mpstat          | Report processors related statistics                             | `mpstat`                                |
| pidstat         | Report statistics by process                                     | `pidstat`                               |
| uptime          | Show how long the system has been running                        | `uptime`                                |
| watch           | Execute a program periodically, showing output fullscreen        | `watch -n 1 date`                       |
| top             | Display and manage running processes                             | `top`                                   |
| htop            | Interactive process viewer (requires installation)               | `htop`                                  |
| lsof            | List open files                                                  | `lsof -i :80`                           |
| strace          | Trace system calls and signals                                   | `strace ls`                             |
| netstat -tuln   | Show listening ports and their status                            | `netstat -tuln`                         |
| iftop           | Display bandwidth usage on an interface (requires installation)  | `iftop`                                 |
| nload           | Visualize network traffic in real-time (requires installation)   | `nload`                                 |
| iotop           | Display I/O usage by processes (requires installation)           | `iotop`                                 |
| sar -u          | Report CPU usage                                                 | `sar -u 1 3`                            |

---

> **Tip:**  
> Use the `man` command (e.g., `man top`) to learn more
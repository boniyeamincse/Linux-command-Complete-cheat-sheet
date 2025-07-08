# Process Management in Linux

Process management is essential for monitoring, controlling, and optimizing running applications and system services. Linux provides a variety of commands to view, manage, and control processes.

---

## Common Process Management Commands

| Command    | Description                                                      | Example                        |
|------------|------------------------------------------------------------------|--------------------------------|
| ps         | Report a snapshot of current processes                           | `ps aux`                       |
| top        | Display and manage running processes                             | `top`                          |
| htop       | Interactive process viewer (requires installation)               | `htop`                         |
| kill       | Terminate a process by PID                                       | `kill 1234`                    |
| killall    | Kill processes by name                                           | `killall firefox`              |
| bg         | Resume a suspended job in the background                         | `bg %1`                        |
| fg         | Bring a background job to the foreground                         | `fg %1`                        |
| jobs       | List active jobs                                                 | `jobs`                         |
| nohup      | Run a command immune to hangups                                  | `nohup command &`              |
| nice       | Run a command with modified scheduling priority                  | `nice -n 10 command`           |
| renice     | Alter the priority of running processes                          | `renice 10 1234`               |
| pstree     | Display a tree of processes                                      | `pstree`                       |
| pgrep      | Look up processes based on name and other attributes             | `pgrep ssh`                    |
| watch      | Execute a program periodically, showing output fullscreen        | `watch -n 1 date`              |
| strace     | Trace system calls and signals                                   | `strace ls`                    |
| lsof       | List open files                                                  | `lsof -i :80`                  |
| pidof      | Find the process ID of a running program                         | `pidof sshd`                   |
| systemctl  | Control the systemd system and service manager                   | `systemctl status ssh`         |
| service    | Control system services                                          | `service ssh status`           |
| at         | Schedule a command to be run once at a particular time           | `echo "ls" | at 09:00`         |

---

> **Tip:**  
> Use the `man` command (e.g., `man ps`) to learn more about each command and its options.


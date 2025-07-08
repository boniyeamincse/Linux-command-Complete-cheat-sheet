# System Administration

System administration involves managing users, services, scheduling tasks, and configuring system settings. Below are essential commands for system administration in Linux.

---

## Common System Administration Commands

| Command         | Description                                         | Example                                 |
|-----------------|-----------------------------------------------------|-----------------------------------------|
| systemctl       | Control the systemd system and service manager      | `systemctl status ssh`                  |
| service         | Control system services                             | `service ssh restart`                   |
| shutdown        | Bring the system down                               | `sudo shutdown now`                     |
| reboot          | Reboot the system                                   | `sudo reboot`                           |
| halt            | Stop the system                                     | `sudo halt`                             |
| crontab -e      | Edit the cron jobs for scheduling tasks             | `crontab -e`                            |
| at              | Schedule a command to run once at a particular time | `echo "ls" | at 09:00`                  |
| hostnamectl     | Control the system hostname                         | `hostnamectl set-hostname newname`      |
| timedatectl     | Control the system time and date settings           | `timedatectl set-time "2025-07-08 10:00:00"` |
| localectl       | Control system locale settings                      | `localectl set-locale LANG=en_US.UTF-8` |
| sudo            | Execute a command as another user (usually root)    | `sudo apt update`                       |
| visudo          | Safely edit the sudoers file                        | `sudo visudo`                           |
| passwd          | Change a user's password                            | `passwd username`                       |
| useradd         | Create a new user                                   | `sudo useradd newuser`                  |
| userdel         | Delete a user account                               | `sudo userdel olduser`                  |
| usermod         | Modify a user account                               | `sudo usermod -aG group username`       |
| chage           | Change user password expiry information             | `sudo chage -l username`                |
| groupadd        | Create a new group                                  | `sudo groupadd newgroup`                |
| groupdel        | Delete a group                                      | `sudo groupdel oldgroup`                |
| groups          | Show groups a user belongs to                       | `groups username`                       |

---

> **Tip:**  
> Use the `man` command (e.g., `man systemctl`) to learn more about each command and its options.
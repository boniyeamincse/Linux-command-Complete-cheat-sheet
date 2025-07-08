# Security and Permissions

Managing security and permissions is critical for protecting Linux systems. Below are essential commands for user authentication, file permissions, firewall management, and monitoring.

---

## Common Security and Permissions Commands

| Command                | Description                                                      | Example                                 |
|------------------------|------------------------------------------------------------------|-----------------------------------------|
| sudo                   | Execute a command as another user (usually root)                 | `sudo apt update`                       |
| visudo                 | Safely edit the sudoers file                                     | `sudo visudo`                           |
| passwd                 | Change a user's password                                         | `passwd username`                       |
| passwd -l username     | Lock a user account                                              | `sudo passwd -l username`               |
| passwd -u username     | Unlock a user account                                            | `sudo passwd -u username`               |
| ssh-keygen             | Generate SSH keys                                                | `ssh-keygen`                            |
| ssh-copy-id            | Install your public key on a remote machine for SSH access       | `ssh-copy-id user@host`                 |
| chmod                  | Change file permissions                                          | `chmod 755 file.txt`                    |
| chown                  | Change file ownership                                            | `chown user:group file.txt`             |
| setfacl                | Set file access control lists                                    | `setfacl -m u:username:rwx file.txt`    |
| getfacl                | Get file access control lists                                    | `getfacl file.txt`                      |
| chattr                 | Change file attributes on a Linux file system                    | `chattr +i file.txt`                    |
| iptables               | Configure packet filtering rules                                 | `sudo iptables -L`                      |
| firewall-cmd           | Configure the firewall (for systems using firewalld)             | `sudo firewall-cmd --list-all`          |
| ufw                    | Uncomplicated Firewall, a user-friendly way to manage iptables   | `sudo ufw enable`                       |
| fail2ban               | Protect against brute-force attacks                              | `sudo fail2ban-client status`           |
| auditd                 | Audit daemon for monitoring system calls                         | `sudo systemctl status auditd`          |
| last                   | Show a listing of last logged in users                           | `last`                                  |
| who                    | Show who is logged on                                            | `who`                                   |
| finger                 | Display information about users                                  | `finger username`                       |

---

> **Tip:**  
> Use the `man` command (e.g., `man chmod`) to learn more about
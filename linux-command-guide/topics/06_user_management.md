# User Management

User management in Linux involves creating, modifying, and deleting user accounts, managing user groups, and setting permissions. Below are some common commands used for user and group management.

---

## Common User Management Commands

| Command                | Description                                         | Example                              |
|------------------------|-----------------------------------------------------|--------------------------------------|
| whoami                 | Display the current username                        | `whoami`                             |
| adduser                | Add a new user                                      | `sudo adduser username`              |
| deluser                | Remove a user                                       | `sudo deluser username`              |
| passwd                 | Change user password                                | `passwd username`                    |
| groups                 | Show groups a user belongs to                       | `groups username`                    |
| su                     | Switch user                                         | `su - username`                      |
| sudo                   | Execute a command as another user (usually root)    | `sudo command`                       |
| visudo                 | Edit the sudoers file safely                        | `sudo visudo`                        |
| chage                  | Change user password expiry information             | `sudo chage -l username`             |
| usermod                | Modify a user account                               | `sudo usermod -aG group username`    |
| userdel                | Delete a user account                               | `sudo userdel username`              |
| id                     | Print user and group IDs                            | `id username`                        |
| finger                 | Display information about users                     | `finger username`                    |
| last                   | Show a listing of last logged in users              | `last`                               |
| who                    | Show who is logged on                               | `who`                                |
| newgrp                 | Log in to a new group                               | `newgrp groupname`                   |
| getent                 | Get entries from administrative databases           | `getent passwd username`             |
| chsh                   | Change the login shell                              | `chsh -s /bin/bash username`         |

---

> **Tip:**  
> Use the `man` command (e.g., `man adduser`) to learn more about any command.
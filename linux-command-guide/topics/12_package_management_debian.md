# Package Management (Debian/Ubuntu)

Debian-based systems (including Ubuntu) use the `apt` and `dpkg` tools for package management. These commands help you install, update, remove, and manage software packages.

---

## Common Package Management Commands

| Command                   | Description                                         | Example                                 |
|---------------------------|-----------------------------------------------------|-----------------------------------------|
| apt update                | Update package index                                | `sudo apt update`                       |
| apt upgrade               | Upgrade installed packages                          | `sudo apt upgrade`                      |
| apt install               | Install a package                                   | `sudo apt install package_name`         |
| apt remove                | Remove a package                                    | `sudo apt remove package_name`          |
| apt search                | Search for a package                                | `apt search package_name`               |
| apt show                  | Display package details                             | `apt show package_name`                 |
| apt autoremove            | Remove unused packages                              | `sudo apt autoremove`                   |
| dpkg -i                   | Install a .deb package                              | `sudo dpkg -i package.deb`              |
| dpkg --list               | List installed packages                             | `dpkg --list`                           |
| apt-cache policy          | Show package version information                    | `apt-cache policy package_name`         |
| apt-mark hold             | Prevent a package from being upgraded               | `sudo apt-mark hold package_name`       |
| apt-mark unhold           | Allow a package to be upgraded                      | `sudo apt-mark unhold package_name`     |
| apt list --upgradable     | List upgradable packages                            | `apt list --upgradable`                 |
| apt full-upgrade          | Upgrade packages, handling dependencies intelligently| `sudo apt full-upgrade`                 |
| apt edit-sources          | Edit the sources list for package repositories      | `sudo apt edit-sources`                 |

---

> **Tip:**  
> Use the `man` command (e.g., `man apt`) to learn more about any
# Package Management (Red Hat/CentOS)

Red Hat-based systems (including CentOS, Fedora, and RHEL) use `yum`, `dnf`, and `rpm` for package management. These commands help you install, update, remove, and manage software packages.

---

## Common Package Management Commands

| Command            | Description                                         | Example                                 |
|--------------------|-----------------------------------------------------|-----------------------------------------|
| yum update         | Update all packages                                 | `sudo yum update`                       |
| yum install        | Install a package                                   | `sudo yum install package_name`         |
| yum remove         | Remove a package                                    | `sudo yum remove package_name`          |
| yum search         | Search for a package                                | `yum search package_name`               |
| yum clean all      | Clean up cached files                               | `sudo yum clean all`                    |
| yum info           | Display information about a package                 | `yum info package_name`                 |
| yum history        | Show the history of transactions                    | `yum history`                           |
| dnf update         | Update all packages (newer versions of RHEL/CentOS) | `sudo dnf update`                       |
| dnf install        | Install a package (newer versions of RHEL/CentOS)   | `sudo dnf install package_name`         |
| dnf remove         | Remove a package (newer versions of RHEL/CentOS)    | `sudo dnf remove package_name`          |
| dnf search         | Search for a package (newer versions of RHEL/CentOS)| `dnf search package_name`               |
| dnf autoremove     | Remove unused packages (newer versions of RHEL/CentOS) | `sudo dnf autoremove`                |
| dnf info           | Display information about a package (newer versions of RHEL/CentOS) | `dnf info package_name`    |
| rpm -i             | Install an RPM package                              | `sudo rpm -i package.rpm`               |
| rpm -qa            | Query all installed RPM packages                    | `rpm -qa`                               |
| rpm -q             | Query a specific RPM package                        | `rpm -q package_name`                   |

---

> **Tip:**  
> Use the `man` command (e.g., `man yum`) to learn more about any command.
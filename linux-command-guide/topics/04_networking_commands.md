# Networking Commands in Linux

Linux provides a wide range of networking commands to test connectivity, transfer files, troubleshoot, and manage network configurations. Below is a list of essential networking commands with brief descriptions.

| Command      | Description                                                        | Example                                 |
|--------------|--------------------------------------------------------------------|-----------------------------------------|
| ping         | Check network connectivity                                         | `ping google.com`                       |
| curl         | Transfer data from or to a server                                  | `curl https://example.com`              |
| wget         | Download files from the web                                        | `wget https://example.com/file.zip`     |
| ssh          | Secure shell to connect to remote machines                         | `ssh user@host`                         |
| scp          | Securely copy files between hosts                                  | `scp file.txt user@host:/path/`         |
| ftp          | File transfer protocol client                                      | `ftp ftp.example.com`                   |
| netstat      | Network statistics (deprecated; use ss)                            | `netstat -tuln`                         |
| ss           | Utility to investigate sockets                                     | `ss -tuln`                              |
| traceroute   | Trace the route packets take to a network host                     | `traceroute google.com`                 |
| nslookup     | Query DNS information                                              | `nslookup example.com`                  |
| dig          | DNS lookup utility                                                 | `dig example.com`                       |
| route        | Show or manipulate the IP routing table                            | `route -n`                              |
| whois        | Query information about a domain                                   | `whois example.com`                     |
| hostname     | Show or set the system's host name                                 | `hostname`                              |
| curl -I      | Fetch HTTP headers                                                 | `curl -I https://example.com`           |
| nmap         | Network exploration tool and security/port scanner (needs install) | `nmap 192.168.1.1`                      |
| arp          | View and modify the ARP cache                                      | `arp -a`                                |
| ip route     | Show and manipulate the routing table                              | `ip route`                              |
| ip link      | Show and manipulate network interfaces                             | `ip link show`                          |
| mtr          | Network diagnostic tool combining ping and traceroute              | `mtr google.com`                        |

---

> **Tip:**  
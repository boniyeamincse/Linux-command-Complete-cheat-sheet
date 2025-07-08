# Miscellaneous Utilities

This section covers various useful Linux utilities and options that don't fit into other categories but are helpful for scripting, automation, downloading, and version control.

---

## Common Miscellaneous Utilities

| Command / Option                | Description                                              | Example                                 |
|---------------------------------|----------------------------------------------------------|-----------------------------------------|
| bc                              | An arbitrary precision calculator language               | `echo "2+2" | bc`                       |
| expr                            | Evaluate expressions                                    | `expr 5 + 3`                            |
| yes                             | Output a string repeatedly until killed                  | `yes "Hello"`                           |
| sleep                           | Delay for a specified amount of time                     | `sleep 5`                               |
| watch                           | Execute a program periodically, showing output fullscreen| `watch -n 1 date`                       |
| time                            | Measure the time taken to execute a command              | `time ls`                               |
| tee                             | Read from stdin and write to stdout and files            | `ls | tee files.txt`                     |
| xargs                           | Build and execute command lines from standard input      | `find . -name "*.txt" | xargs rm`       |
| pv                              | Monitor the progress of data through a pipeline          | `pv file.iso | dd of=/dev/null`          |
| curl -O                         | Download a file and save it with the same name           | `curl -O https://example.com/file.txt`  |
| curl -s                         | Silent mode, no progress meter or error messages         | `curl -s https://example.com`           |
| curl -v                         | Verbose mode, show detailed information                  | `curl -v https://example.com`           |
| wget -c                         | Continue getting a partially-downloaded file             | `wget -c https://example.com/file.zip`  |
| wget -r                         | Download files recursively                               | `wget -r https://example.com/dir/`      |
| wget -q                         | Quiet mode, no output                                    | `wget -q https://example.com/file.zip`  |
| wget --limit-rate=200k          | Limit download speed                                     | `wget --limit-rate=200k https://example.com/file.zip` |
| wget --no-check-certificate     | Ignore SSL certificate checks                            | `wget --no-check-certificate https://example.com/file.zip` |
| git                             | Version control system                                   | `git status`                            |
| git clone                       | Clone a repository                                       | `git clone https://github.com/user/repo.git` |
| git commit                      | Commit changes to the repository                         | `git commit -m "message"`               |

---

> **Tip:**  
> Use the `man` command (e.g., `man bc`, `man git`, `man wget`) to learn more about any command.
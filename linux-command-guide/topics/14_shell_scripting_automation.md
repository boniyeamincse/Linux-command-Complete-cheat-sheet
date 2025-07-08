# Shell Scripting and Automation

Shell scripting allows you to automate repetitive tasks, manage system operations, and create powerful workflows in Linux. Below are common commands, constructs, and best practices used in shell scripting and automation.

---

## Common Shell Scripting Commands and Constructs

| Command / Construct         | Description                                               | Example / Syntax                          |
|----------------------------|-----------------------------------------------------------|-------------------------------------------|
| bash / sh                  | Start a new Bash or Bourne shell                          | `bash`, `sh`                              |
| chmod +x script.sh         | Make a script executable                                  | `chmod +x script.sh`                      |
| ./script.sh                | Execute a script                                          | `./script.sh`                             |
| source script.sh           | Run a script in the current shell                         | `source script.sh`                        |
| echo "text" > file.txt     | Write text to a file                                      | `echo "Hello" > file.txt`                 |
| cat file.txt               | Display the contents of a file                            | `cat file.txt`                            |
| grep "pattern" file.txt    | Search for a pattern in a file                            | `grep "root" /etc/passwd`                 |
| sed 's/old/new/g' file.txt | Replace text in a file                                    | `sed 's/foo/bar/g' file.txt`              |
| awk '{print $1}' file.txt  | Print the first column of a file                          | `awk '{print $1}' file.txt`               |
| for ...; do ...; done      | Loop through a set of commands                            | `for i in *; do echo $i; done`            |
| while ...; do ...; done    | Execute commands as long as a condition is true           | `while [ $n -le 5 ]; do echo $n; done`    |
| if ...; then ...; fi       | Execute commands based on a condition                     | `if [ -f file.txt ]; then echo "Yes"; fi` |
| case ... in ... esac       | Execute commands based on a pattern                       | `case $var in pattern) ... ;; esac`       |
| function name { ... }      | Define a function in a script                             | `function greet() { echo "Hi"; }`         |
| return                     | Return a value from a function                            | `return 0`                                |
| exit                       | Exit a shell or script                                    | `exit 1`                                  |
| trap                       | Execute commands when receiving signals                   | `trap "echo Signal received" SIGINT`      |
| set -e                     | Exit immediately if a command exits with non-zero status  | `set -e`                                  |
| set -x                     | Print commands and their arguments as they are executed   | `set -x`                                  |

---

> **Tip:**  
> Use the `man` command (e.g., `man bash`) to learn more about shell scripting and automation. The `man` command displays the manual pages for commands and programs, providing detailed information about their usage, options, and examples.
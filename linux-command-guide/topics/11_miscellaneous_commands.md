# Miscellaneous Commands

These Linux commands provide various utilities for date/time, calculations, environment management, shell operations, and more.

---

## Common Miscellaneous Commands

| Command         | Description                                         | Example                                 |
|-----------------|-----------------------------------------------------|-----------------------------------------|
| date            | Display or set the system date and time             | `date`                                  |
| cal             | Display a calendar                                  | `cal`                                   |
| bc              | An arbitrary precision calculator language          | `echo "2+2" | bc`                       |
| expr            | Evaluate expressions                                | `expr 5 + 3`                            |
| yes             | Output a string repeatedly until killed             | `yes "Hello"`                           |
| sleep           | Delay for a specified amount of time                | `sleep 5`                               |
| echo $PATH      | Display the current PATH variable                   | `echo $PATH`                            |
| env             | Display environment variables                       | `env`                                   |
| printenv        | Print all or part of the environment                | `printenv HOME`                         |
| set             | Set shell options and positional parameters         | `set`                                   |
| trap            | Run a command when a signal is received             | `trap "echo Signal received" SIGINT`    |
| export          | Set environment variables                           | `export VAR=value`                      |
| unset           | Remove variable or function names                   | `unset VAR`                             |
| source          | Execute commands from a file in the current shell   | `source ~/.bashrc`                      |
| sh              | Start a new Bourne shell                            | `sh`                                    |
| bash            | Start a new Bash shell                              | `bash`                                  |
| fgrep           | Search fixed strings in files                       | `fgrep "text" file.txt`                 |
| egrep           | Extended grep for regular expressions               | `egrep "pattern" file.txt`              |
| basename        | Strip directory and suffix from filenames           | `basename /path/to/file.txt .txt`        |
| dirname         | Strip the last component from file name             | `dirname /path/to/file.txt`              |

---

> **Tip:**  
> Use the `man` command (e.g., `man date`) to learn more about any command.



Package Management (Debian/Ubuntu)
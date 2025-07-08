# File Search and Text Processing

Linux provides powerful commands for searching files and processing text. These tools are essential for system administration, scripting, and data analysis.

---

## Common File Search and Text Processing Commands

| Command   | Description                                         | Example                                 |
|-----------|-----------------------------------------------------|-----------------------------------------|
| locate    | Find files by name                                  | `locate filename.txt`                   |
| grep      | Search text using patterns                          | `grep "pattern" file.txt`               |
| sed       | Stream editor for filtering and transforming text   | `sed 's/old/new/g' file.txt`            |
| awk       | Pattern scanning and processing language            | `awk '{print $1}' file.txt`             |
| cut       | Remove sections from each line of files             | `cut -d':' -f1 /etc/passwd`             |
| sort      | Sort lines of text files                            | `sort file.txt`                         |
| uniq      | Report or omit repeated lines                       | `uniq file.txt`                         |
| head      | Output the first part of files                      | `head -n 10 file.txt`                   |
| tail      | Output the last part of files                       | `tail -n 10 file.txt`                   |
| diff      | Compare files line by line                          | `diff file1.txt file2.txt`              |
| tr        | Translate or delete characters                      | `tr 'a-z' 'A-Z' < file.txt`             |
| fmt       | Simple text formatter                               | `fmt file.txt`                          |
| nl        | Number lines of files                               | `nl file.txt`                           |
| split     | Split a file into pieces                            | `split -l 1000 bigfile.txt`             |
| paste     | Merge lines of files                                | `paste file1.txt file2.txt`             |
| tac       | Concatenate and display files in reverse            | `tac file.txt`                          |
| join      | Join lines of two files on a common field           | `join file1.txt file2.txt`              |
| shuf      | Generate random permutations                        | `shuf file.txt`                         |
| od        | Dump files in octal and other formats               | `od -c file.txt`                        |
| rev       | Reverse lines of a file                             | `rev file.txt`                          |

---

> **Tip:**  
> Use the `man` command (e.g., `man grep`) to learn more about any
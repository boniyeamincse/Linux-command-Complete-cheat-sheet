# Archiving and Compression in Linux

Archiving and compression are essential for managing backups, transferring files, and saving disk space. Linux provides several commands to create, extract, and manage archives in various formats.

---

## Common Archiving and Compression Commands

| Command         | Description                                   | Example                                 |
|-----------------|-----------------------------------------------|-----------------------------------------|
| tar -cvf        | Create a tarball                              | `tar -cvf archive.tar file1 file2`      |
| tar -xvf        | Extract a tarball                             | `tar -xvf archive.tar`                  |
| tar -czvf       | Create a compressed tarball (gzip)            | `tar -czvf archive.tar.gz file1 file2`  |
| tar -xzvf       | Extract a compressed tarball (gzip)           | `tar -xzvf archive.tar.gz`              |
| tar -czf        | Create a gzipped tarball                      | `tar -czf archive.tar.gz dir/`          |
| tar -xzf        | Extract a gzipped tarball                     | `tar -xzf archive.tar.gz`               |
| zip             | Package and compress files                    | `zip archive.zip file1 file2`           |
| unzip           | Extract compressed files                      | `unzip archive.zip`                     |
| gzip            | Compress files                                | `gzip file.txt`                         |
| gunzip          | Decompress files                              | `gunzip file.txt.gz`                    |
| bzip2           | Compress files using bzip2                    | `bzip2 file.txt`                        |
| bunzip2         | Decompress bzip2 files                        | `bunzip2 file.txt.bz2`                  |
| xz              | Compress files using LZMA                     | `xz file.txt`                           |
| unxz            | Decompress LZMA files                         | `unxz file.txt.xz`                      |
| zipinfo         | List the contents of a zip file               | `zipinfo archive.zip`                   |

---

> **Tip:**  
> Use the `man` command (e.g., `man tar`) to learn more about any command.
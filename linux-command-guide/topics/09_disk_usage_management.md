# Disk Usage and Management

Disk usage and management are crucial for maintaining system health, optimizing storage, and preventing data loss. Linux provides a variety of commands to monitor, manage, and troubleshoot disks and file systems.

---

## Common Disk Usage and Management Commands

| Command           | Description                                                      | Example                                 |
|-------------------|------------------------------------------------------------------|-----------------------------------------|
| fdisk             | Partition table manipulator for Linux                            | `sudo fdisk /dev/sda`                   |
| parted            | Partition manipulation program                                   | `sudo parted /dev/sda`                  |
| mkfs              | Create a file system on a disk                                   | `sudo mkfs.ext4 /dev/sda1`              |
| tune2fs           | Adjust tunable file system parameters (ext2/ext3/ext4)           | `sudo tune2fs -l /dev/sda1`             |
| badblocks         | Search a device for bad sectors                                  | `sudo badblocks -v /dev/sda1`           |
| resize2fs         | Resize ext2/ext3/ext4 file systems                               | `sudo resize2fs /dev/sda1`              |
| mount             | Mount a file system                                              | `sudo mount /dev/sda1 /mnt`             |
| mount -o loop     | Mount a file as a file system                                    | `sudo mount -o loop disk.img /mnt`      |
| umount            | Unmount a file system                                            | `sudo umount /mnt`                      |
| fsck              | Check and repair a Linux file system                             | `sudo fsck /dev/sda1`                   |
| dd                | Convert and copy a file                                          | `dd if=/dev/sda of=/dev/sdb bs=4M`      |
| df -h             | Display disk space usage in human-readable format                | `df -h`                                 |
| du -sh            | Display total disk usage of a directory                          | `du -sh /home/user`                     |
| lsblk             | List block devices                                               | `lsblk`                                 |
| hdparm            | Get/set SATA/IDE device parameters                               | `sudo hdparm -I /dev/sda`               |

---

> **Tip:**  
> Use the `man` command (e.g., `man fdisk`) to learn more about each command and its options.
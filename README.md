[![Picture](./Linux_file_hierarchy.png)](./Linux_file_hierarchy.png)
**Root Directory (/)**
The root is the top-level directory in Linux. Every file and directory starts from here. It is the beginning of the file system hierarchy.

## Important Subdirectories
1. /bin (Binaries)
Contains essential user command binaries (e.g., ls, cp, mv).
Commands needed for basic system operation, available in single-user mode.
2. /boot (Boot Loader Files)
Contains files needed for booting the system, such as:
The kernel (vmlinuz)
Bootloader files (e.g., GRUB configurations).
3. /dev (Device Files)
Special device files representing hardware or virtual devices.
Example:
/dev/sda for hard drives.
/dev/null, /dev/tty.
4. /etc (Configuration Files)
Stores system-wide configuration files.
Examples:
/etc/passwd: User accounts.
/etc/fstab: File system mount information.
5. /home (User Home Directories)
Contains personal directories for each user.
Example: /home/mahfuz (your personal directory).
6. /lib (Libraries)
Shared libraries and kernel modules required for system operation.
Includes libraries for binaries in /bin and /sbin.
7. /media (Mount Points for Removable Media)
Automatically mounts removable media like USB drives and CDs.
8. /mnt (Temporary Mount Point)
Used for temporarily mounting file systems.
9. /opt (Optional Software)
For installing optional software packages.
10. /proc (Process Information)
Virtual filesystem providing information about processes and system resources.
Examples:
/proc/cpuinfo: CPU information.
/proc/meminfo: Memory usage.
11. /root (Root User's Home Directory)
Home directory for the superuser (root).
12. /run (Runtime Data)
Temporary files storing runtime information like PIDs and sockets.
Exists only during system runtime.
13. /sbin (System Binaries)
System administration binaries (e.g., fsck, reboot).
Requires superuser permissions to execute.
14. /srv (Service Data)
Data for services provided by the system (e.g., web server files).
15. /sys (System Information)
Provides access to system and kernel data structures.
16. /tmp (Temporary Files)
Temporary storage for files that can be deleted after a reboot.
17. /usr (User Binaries and Data)
Secondary hierarchy containing user applications and utilities.
/usr/bin: Non-essential command binaries.
/usr/lib: Libraries for binaries in /usr/bin.
/usr/local: Locally installed software.
18. /var (Variable Data Files)
Files that frequently change during system operation.
Logs: /var/log.
Mail: /var/mail.
Caches: /var/cache.
Structure Visualization

/
├── bin
├── boot
├── dev
├── etc
├── home
├── lib
├── media
├── mnt
├── opt
├── proc
├── root
├── run
├── sbin
├── srv
├── sys
├── tmp
├── usr
└── var

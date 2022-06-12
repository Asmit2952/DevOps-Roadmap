# Filesystem Hierarchy Standard (FHS)

Linux uses the ‘/’ character to separate paths, and does not have drive letters. Multiple drives and/or partitions are mounted as directories in the single filesystem. Removable media such as USB drives and CDs and DVDs will show up as mounted.

All Linux filesystem names are case-sensitive

|Directory| Definition                      |
|---------|---------------------------------|
| `/`     | Root directory of entire FHS    |
| `/bin`  | Essential user command binaries |
| `/boot` | Static files of the boot loader |
| `/dev`  | Device files                    |
| `/etc`  | Host specific system configuration |
| `/home` | User home directories |
| `/lib`  | Essential shared libraties and kernel modules |
| `/media`| Mount point for removable media |
| `/mnt`  | Mount point for temporary mounted file systems |
| `/opt`  | Add-on application software packages |
| `/sbin` | System Binaries                 |
| `/srv`  | Data for services provided by this system |
| `/tmp`  | Temporary files                 |
| `/usr`  | Multi-user utilities and application |
| `/var`  | Variable files                  |
| `/root` | Home directory for the root user |
| `/proc` | Virtual filesystem documenting kernel and process status as text files |

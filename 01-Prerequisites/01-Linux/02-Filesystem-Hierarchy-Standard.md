# Filesystem Hierarchy Standard (FHS)

Linux uses the ‘/’ character to separate paths, and does not have drive letters. Multiple drives and/or partitions are mounted as directories in the single filesystem. Removable media such as USB drives and CDs and DVDs will show up as mounted.

|Directory| Definition                      |
|---------|---------------------------------|
| `/`     | Root directory of entire FHS    |
| `/bin`  | Essential user command binaries |
| `/boot` | Static files of the boot loader |

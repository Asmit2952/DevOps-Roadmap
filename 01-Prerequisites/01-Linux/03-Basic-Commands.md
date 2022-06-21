# Basic Commands in Linux

* `whoami`: To find the current user ID
* `man`: It searches, formats, and displays the information contained in the man page system.
* `sudo`: Provides the user with administrative (admin) privileges when required
* `su`: Switch to the root user
* `cat`: Used to type out a file (or combine files)
* `head`: Used to show the first few lines of a file
* `tail`: Used to show the last few lines of a file
* `man`: Used to view documentation.
* `which`: Used to locate the executable file associated with the given command
* `whereis`: Alternative to `which`. Looks for packages in a broader range of system directories
* `pwd`: Displays current working directory
* `cd`: Change to your home directory
* `cd ..`: Change to parent directory
* `cd -`: Change to previous directory
* `tree`: To get a bird’s-eye view of the filesystem tree
* `ls`: List the contents of the present working directory
* `ls -a`: List all files, including hidden files and directories (those whose name start with . )
* `touch`: Used to create an empty file
* `touch -t`: Set the date and timestamp of the file to a specific value
* `mkdir`: Used to create a directory
* `rmdir`: Used to remove a directory (works only on empty directory)
* `mv`: Rename a file or move a file to another location
* `rm`: Remove a file 
* `rm -f`: Forcefully remove a file
* `rm –i`: Interactively remove a file (to prompt before every removal)
* `rm -rf`: Forcefully remove a directory recursively
* `echo`: To print anything on the terminal
* `du`: Allows a user to gain disk usage information quickly
* `cp`: Used to copy files or group of files or directory
* `ps`: Provides information about currently running processes keyed by PID
* `pstree`: Displays the processes running on the system in the form of a tree diagram
* `top`: Provides information about currently running processes every two seconds

## Keyboard Shortcuts

* `CTRL-L`: Clears the screen
* `CTRL-D`: Exits the current shell
* `CTRL-Z`: Puts the current process into suspended background
* `CTRL-C`: Kills the current process
* `CTRL-H`: Works the same as backspace
* `CTRL-A`: Goes to the beginning of the line
* `CTRL-W`: Deletes the word before the cursor
* `CTRL-U`: Deletes from beginning of line to cursor position
* `CTRL-E`: Goes to the end of the line
* `Tab`: Auto-completes files, directories, and binaries

## File Permissions

* `chown`: Used to change user ownership of a file or directory
* `chgrp`: Used to change group ownership
* `chmod`: Used to change the permissions on the file, which can be done separately for owner, group and the rest of the world (often named as other)

### chmod
A single digit suffices to specify all three permission bits for each entity. This digit is the sum of:
* `4` if read permission is desired
* `2` if write permission is desired
* `1` if execute permission is desired.

Thus, `7` means read/write/execute, `6` means read/write, and `5` means read/execute.

```
$ chmod 755 demo
$ ls -l somefile
-rwxr-xr-x 1 student student 1601 Mar 9 15:04 demo
```
This grants the user, groups, and other users access to the `demo` file with read, write, and execute permissions.

## File Manipulation Utilities

* `sort`: Used to rearrange the lines of a text file, in either ascending or descending order according to a sort key
* `uniq`: Removes duplicate consecutive lines in a text file
* `paste`: Used to combine fields from different files, as well as combine lines from multiple files
* `join`: Enhanced version of `paste`. It first checks whether the files share common fields, and then joins the lines in two files based on a common field.
* `split`: Used to break up (or split) a file into equal-sized segments for easier viewing and manipulation.

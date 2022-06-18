# Text Editors

## nano

```
nano <filename>
```

* `CTRL-G`: Display the help screen
* `CTRL-O`: Write to a file
* `CTRL-X`: Exit a file
* `CTRL-R`: Insert contents from another file to the current buffer
* `CTRL-C`: Show cursor position

## vim

```
vi <filename>
```

* `vi -r myfile`: Start and edit myfile in recovery mode from a system crash
* `:r file2`: Read in file2 and insert at current position
* `:w`: Write to the file
* `i`: Switch to insert mode
* `:w myfile`: Write out to myfile
* `:w! file2`: Overwrite file2
* `:x or :wq`: Exit and write out modified file
* `:q`: Quit
* `:q!`: Quit even though modifications have not been saved

### Changing Cursor Positions

* `arrow keys`: To move up, down, left and right
* `j`: To move one line down
* `k`: To move one line up
* `h`: To move one character left
* `l`: To move one character right
* `0`: To move to beginning of line
* `$`: To move to end of line
* `w`: To move to beginning of next word
* `:0`: To move to beginning of file
* `:n`: To move to line n
* `:$`: To move to last line in file
* `CTRL-F or Page Down`: To move forward one page
* `CTRL-B or Page Up`: To move backward one page
* `^l`: To refresh and center screen

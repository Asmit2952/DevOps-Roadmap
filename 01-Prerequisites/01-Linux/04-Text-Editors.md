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
* `Esc key`: Switch to normal mode
* `:w myfile`: Write out to myfile
* `:w! file2`: Overwrite file2
* `:x or :wq`: Exit and write out modified file
* `:q`: Quit
* `:q!`: Quit even though modifications have not been saved

### Changing Cursor Positions in vi

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

Refer this [document](./commands-for-vi.pdf) for more vi commands in detail

## emacs

```
emacs <filename>
```

* `CTRL-x i`: Insert prompted for file at current position
* `CTRL-x s`: Save all files
* `CTRL-x CTRL-w`: Write to the file giving a new name when prompted
* `CTRL-x CTRL-s`: Saves the current file
* `CTRL-x CTRL-c`: Exit after being prompted to save any modified files

### Changing Cursor Positions in emacs

* `arrow keys`: To move up, down, left and right
* `CTRL-n`: One line down
* `CTRL-p`: One line up
* `CTRL-f`: One character forward/right
* `CTRL-b`: One character back/left
* `CTRL-a`: Move to beginning of line
* `CTRL-e`: Move to end of line
* `Meta-f`: Move to beginning of next word
* `Meta-b`: Move back to beginning of preceding word
* `Meta-<`: Move to beginning of file
* `Meta-g-g-n`: Move to line n (can also use 'Esc-x Goto-line n')
* `Meta->`: Move to end of file
* `CTRL-v or Page Down`: Move forward one page
* `Meta-v or Page Up`: Move backward one page
* `CTRL-l`: Refresh and center screen

Refer this [document](./commands-for-emacs.pdf) for more emacs commands in detail

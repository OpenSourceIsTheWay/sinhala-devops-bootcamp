vim is a unix text editor.

cli tool

why we need it?

Linux CLI has a built in text editor vi or vim (vi modern).

can be used to manipulate files inside cli

- small edits in the CLi instead of an IDE saves time
- faster than manually opening files
- supports many file types

- writing git commit messages
- checking config files
- quick editing of config files

need to learn the basic vim commands

type "vim <file name>"
  
  sudo apt install vim
  
  vim has two modes
  - command mode - this is the default mode
  - edit (insert) mode
 
 to switch between modes, press i for insert mode
 to save the file, pres esc to go to command mode
 type :wq - save and close
  
 q! - quit without saving file
  
vim <new file>
  
dd - remove the current line
d10 d - delete 10 lines from the cursor
u - undo the change
A - switch to insert mode and go to EOL
0 - jump to start of a line
$ - jump to end of a line
12G - jump to line
  
/<pattern> - search file
n - jump to next match
N - jump to previous match
  
:%s/old/new - replace old string with the new string

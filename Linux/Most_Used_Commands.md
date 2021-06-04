## The Pipe Command ( | )
- cat tepe.txt | grep “tepe"  ==> read tepe.txt and look for "tepe"

## move to Home directory of your Machine
- cd ~ 
- cd

## My Current Path
- pwd 

## list all folders and files
- ls 

## List the contents of the directory, including file date, size, 
- ls -l

## Show all files and directories, including hidden files 
- ls -a

## Remove all files is current path/dir
- rm *

## Rename app.js to newApp.js
- mv app.js newApp.js

## Show all running process in your machine. hit q to stop.
- top

## The shell you want to use
- for Bash that would be /bin/bash. For Zsh that would be /usr/bin/zsh

*To make any shell your default, first verify it is installed and recognized on your computer by looking at the contents of 
- /etc/shells

*Then use chsh to change your shell:

- sudo chsh -s /usr/bin/bash $(whoami) # or sudo chsh -s /bin/bash $(whoami)









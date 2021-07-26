# LINUX-BASE
LINUX BASE COMMOND


## Show hidden file  ls -lah /
## show 


## search for a file that contains two or more words, use an asterisk (*).
For example, locate -i school*note command will search for any file that contains the word “school” and “note”, whether it is uppercase or lowercase.

find command
Similar to the locate command, using find also searches for files and directories. The difference is, you use the find command to locate files within a given directory.

As an example, find /home/ -name notes.txt command will search for a file called notes.txt within the home directory and its subdirectories.

Other variations when using the find are:

To find files in the current directory use, find . -name notes.txt
To look for directories use, / -type d -name notes. txt

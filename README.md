# holbertonschool-shell
# PLD : Shell Scripting

Practical Tasks: Shell Scripting
1. Create a script that prints *"Hello, World!"* to the terminal.
- **#!/bin/bash echo "Hello World"**
2.How would you write a shell script that *prints* the current working directory?
- **#!/bin/bash pwd**
3. Write a shell script that *lists* all files and directories in the current directory.
- **#!/bin/bash -l** 
4. How would you write a script that *creates a new directory* named "backup" in the current directory?
- **#!/bin/bash mkdir backup**
5. How can you write a script that *renames* a file from "oldname.txt" to "newname.txt"?
- **#!/bin/bash mv oldname.txt newname.txt**
6. Create a shell script that deletes all files in a directory with a ".log" extension
- **#!/bin/bash rm *.log
7.Write a shell script that *creates* a new file named "newfile.txt" in the current directory.
- **#!/bin/bash touch newfile.txt**
8. Display current directory contents, including hidden files (starting with .). Use the long format.
- **#!/bin/bash ls -la**
9. Create a script that *copies* all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
- **#!/bin/bash cp -u** ***.html ../**
10. Create a *symbolic link* to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
- **#!/bin/bash ln -s bin/ls __ls__**
11. Create a script that *deletes* all files in the current working directory that end with the character ~.
- **#!/bin/bash rm ~***


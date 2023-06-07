#!/bin/bash
pwd - Prints absolute path name of working directory
ls - Lists files and directories
cd ~ - Changes from current directory to user's home directory
ls -l - Lists files in current directory in long format
ls -la - Lists current diectory contents including hidden files
ls -al - Displays current directory contents in long format with user and group IDs displayed numerically and hidden files (starting with .)
mkdir - Create directory 'my_first_directory' in /tmp directory
mv - move betty from /tmp to /tmp/my_first_directory
rm - delete file 'betty'
rm -r - delete directory 'my_first_directory'
cd -  - To change the working directory to the previous one
ls -al . .. /boot - To list all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
type /tmp/iamafile - To print the type of the file
ln -s /bin/ls __ls__ - To Create a symbolic link to /bin/ls, named __ls__.
cp *.html ../ - Create a script that copies all the HTML files from the current working directory to the parent of the working directory*
mv [[:upper]]* /tmp/u - *Create a script that moves all files beginning with an uppercase letter to the directory /tmp/u.
rm *~ - *To Create a script that deletes all files in the current working directory that end with the character ~.
mkdir -p welcome/to/school
ls -ampv 


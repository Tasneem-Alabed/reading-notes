# Practice in the Terminal

### What is it, how does it work and how do I get to one

A command line, or terminal, is a text based interface to the system.The command line typically presents you with a prompt

### An introduction to the Linux directory system and how to get around it

At first each directory has a path and to trancfare from directory to other we have to know the bath and uso some of comand
cd to go to the root
cd with directory name or path to open it
pwd to show the path
ls to show list of the directories and files in the current directory

### Find out some interesting characteristics of files and directories in a Linux environment

Everything in linuxs is actually a file.(A text file is a file, a directory is a file, the keyboard is a file and your monitor is a file )
Also be aware of case sensitivity when dealing with command line options. For instance with the command ls there are two options s and S both of which do different things. A common mistake is to see an option which is upper case but enter it as lower case and wonder why the output doesn't match your expectation.Spaces in file and directory names are perfectly valid but we need to be a little careful with them.
Hidden file and directory
Linux actually has a very simple and elegant mechanism for specifying that a file or directory is hidden. If the file or directory's name begins with a . (full stop) then it is considered to be hidden.

### Learn how to make the most of the Linux commands you are learning

The manual pages are a set of pages that explain every command available on your system including what they do, the specifics of how you run them and what command line arguments they accept.
man command
Look up the manual page for a particular command.
man -k search term
Do a keyword search for all manual pages containing the given search term.
/ term
Within a manual page, perform a search for 'term'
n
After performing a search within a manual page, select the next found item.

### How to make, remove, rename, copy and move files and directories

to create a directory use mkdir then its name

to rename direectory rmdir

to creating a Blank File touch

to copy files cp [options] source destination

to move file or directory mv [options] source destination

to removing a File rm



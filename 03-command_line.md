# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > REPLACE THIS TEXT WITH YOUR RESPONSE

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > 
`ls` > > lists files in the working directory
`ls -a`  > > lists all files, including hidden files, in the working directory
`ls -l`  > > lists files in the working directory in long format
`ls -lh`  > > lists files in working directory in long human readable format
`ls -lah`  > > lists all files, including hidden files, in working directory in long format with human readable size
`ls -t`  > > lists files in working directory ordered by time of last modification
`ls -Glp` > > lists long format directories with "/" appended to the end and without user group names

---

### Q3.  More List Files in Unix  

ExploRre these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 
ls -u
ls -1
ls -R
ls -S
ls -d

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > 'xargs' reads data from standard input (stdin) and executes the command (supplied to it as an argument) one or more times based on the input read. Any blanks and spaces in the input are treated as delimiters, while blank lines are ignored. 
example: xargs find -name

 


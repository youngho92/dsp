# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

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

> > 
ls
mkdir temp
rm temp.txt
touch temp.txt
rm -r temp
cat temp.txt > temp2.txt
ls -a
cp a.txt b/

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  list all files
`ls -a`  list hidden files starting with .
`ls -l`  list with long format
`ls -lh`  list long format with readable size
`ls -lah`  list long format with hidden files
`ls -t`  list sorted by time & date
`ls -Glp`  IDK

> > REPLACE THIS TEXT WITH YOUR RESPONSE

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 
ls -X
ls -s
ls -d
ls -f
ls -S


---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs is a command on Unix and most Unix-like operating systems used to build and execute commands from standard input.
cat temp.txt | sort > temp2.txt (save sorted version of temp.txt in temp2.txt)

 


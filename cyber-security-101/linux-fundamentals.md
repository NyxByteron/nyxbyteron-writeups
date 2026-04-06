# 🐧 Linux Fundamentals
## 🧠 What I Learned
- Basic concepts and fudamentals of Linux.  
  → I learned a bit about how Linux works and its basic concepts
- Running my first Linux commands.  
  → I learned to execute basic commands on Linux, delete folders, rename files, etc
- Searching for Files.  
  → I learned how to search for files and folders using commands.
- Shell Operators.  
  → I learned how to use shell operators in Linux.


---

## 📄 Introduction

In reality Linux is a term used to refer to several operating systems that are based in UNIX. It has several variations commonly called distros. The Linux systems are used in several locations such as traffic light controllers, car multimedia systems, servers, websites, etc.  
One of the great advantages of Linux systems is that in general they are lighter compared to other systems like Windows.

---

## 💻 Running my first Linux commands

In this module I logged into my first Linux machine (running in a browser) and executed my first commands.  

echo → The echo command shows text on the terminal. (example: echo hello)  
If I want to show more than one word I need to use the double quotes. (example: echo "hello friend")  
whoami → This command is used to find out the username I'm logged in with.

---

## 📁 Interacting with the filesystem   

In this module I learned how to use commands to navigate through folders without a desktop environment, or rather, using only the command line.  

ls(listing) → List the files and folders in the current folder.  
cd(change directory) → As the name suggests, change the directory.  
cat(concatenate) → The name is self-explanatory too.  
pwd(print working directory) → Shows the current directory.  

It's possible to list contents of a directory without necessarily accessing it, using ls + the name of the directory.  
It's also possible to open a file, for example a .txt file, without necessarily entering the folder where the file is. Just type the command cat followed by the path where the file is. For example: "cat /home/tryhackme/folder1/note.txt".  

### 🔍 Searching for Files  

Besides navigating through folders, I learned a few commands to find files.  

find → It can be used in different ways. Knowing the name of the file, we can search for it using "find -name notes.txt"
We can search for files by extension. For example: "find -name *.txt".  
grep → It's used to search for patterns in files. For example: "grep 'password' passwords.txt".  
There are many uses for this command. It is mainly useful in large files, such as logs.

---

## 📓 An Introduction to Shell Operators  

Linux operators are a good way to power up my command line and are very useful. I learned a few of them and found them very interesting.  

& → Allows running commands in the background.  
&& → Allows combining multiple commands in a single line.  
'>' → It is a redirect operator, we can get the output of a command and redirect it to another location.  
'>>' → Has the same function as the previous one, but appends the output instead of replacing it.


---
## 💭 Notes

- Understanding how to use basic Linux commands is important.
- Knowing how to navigate directories and search for files is essential.
- Linux operators will be very important in my career.


---

> A strong foundation builds a stronger future.

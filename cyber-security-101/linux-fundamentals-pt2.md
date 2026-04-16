# 🐧 Linux Fundamentals Part 2  

## 🧠 What I Learned  

- Acessing Your Linux Machine Using SSH  
  → I made my first connection SSH using two Linux machines.
- Introduction to Flags and Switches  
  → I learned why to use arguments with commands.
- Filesystem Interaction Continued  
  → I learned how to create, move and delete directories and files, continuing my learning of interacting with the filesystem.


--- 

## 🖥️ Acessing Your Linux Machine Using SSH (Deploy)  

- In this module, I basically learned how to make an SSH connection using two Linux machines.   
  → For the connection to work, it is necessary to have the login credentials (username and password) of the target machine.  
  → The command is simple: ssh "login@ip_from_machine". After that, the password will be requested.

---


## ⚙️ Introduction to Flags and Switches

Most Linux commands can receive arguments.  
Generally speaking, when the command is used alone it executes the default action.  
The arguments can be used to extend the funcionality of commands.  
  → For example, the ls command by default shows the files in the current directory. If we use ls -a it lists all files, including hidden files.  

To consult the manual of commands, you can be use man + "command name". For example, man ls.  
Another way to access the manual is online.  

In summary, there are many flags and switches, and they are very useful, but the best way to learn how to use them is by using them daily and checking the command manual.


--- 

## 📂 Filesystem Interaction Continued  

In this module I learned how to interact with the Linux filesystem, such as creating, moving, and renaming files.  

Creating files  
touch → Command to create files. "touch note" creates a file named note. However, to insert content, it is necessary to use commands like echo or text editors like nano.  
mkdir → Command to create a directory. "mkdir directory" creates a directory called directory.  

Removing files  
rm → Command to remove files and directories. "rm note" removes the note file. To remove directories, it is necessary to use -R(recursively) option. For example, rm -R directory.  

Copying and moving files  
cp → Command to copy files. To copy a file, it is necessary to use two arguments. The first is the name of the file to be copied, and the second is the name of new file. For example, "cp note note2".  
mv → Command to moves and rename files. It needs two arguments like cp, but instead of creating a second file, it replaces the second file. mv can be used to change the name of a file or directory.  

Determining the file type  
Usually we see files with extensions like .txt, .pdf, but this isn't necessarily mandatory. The lack of an extension can cause confusion when we are faced with a file without an exetension and don't know the context.  
To help with this problem, we can use the "file" command. For example, "file note" will return the file type, something like: ASCII text.  
file → shows the file type.

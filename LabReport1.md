```
[user@sahara ~]$ cd lecture1
[user@sahara ~/lecture1]$ cd
[user@sahara ~]$ 
```
**The working directory when the code was run was lecture1. There was no output because the cd command allows you to move between directories. Without an argument, the command has no output but returns you to the home directory. The output is not an error.**

```
[user@sahara ~]$ cd lecture1
[user@sahara ~/lecture1]$ ls
Hello.class  Hello.java  messages  README
```
**The working directory when the code was run was lecture1. The output of the ls command are the files that are in the lecture1 directory except for hidden files such as those in the messages file. The output is not an error.**

```
[user@sahara ~/lecture1]$ cat

```
**The working directory when the command was run is lecture1. There was no output because the cat command reads each file in order and prints it out. When there is no specified file name, the cat command reads the standard input. The output is not an error.** 

```
[user@sahara ~]$ cd lecture1
[user@sahara ~/lecture1]$
```
**The working directory when the command was run is the home directory. There was no output, however after the command was run, the working directory is lecture1. The output is not an error.**

```
[user@sahara ~/lecture1]$ ls messages
en-us.txt  es-mx.txt  fr.txt  zh-cn.txt
```
**The working directory when the command was run is lecture1. The output of this command was the list of the files in the messages directory. This output is not an error.**

```
[user@sahara ~/lecture1]$ cat messages
cat: messages: Is a directory
```
**The working directory when the command was run is lecture1. The output that was received was an error message stating that the command cannot be used because you cannot print out a directory. The cat command can only be used on files.**

```
[user@sahara ~/lecture1]$ cd README
bash: cd: README: Not a directory
```
**This working directory when the command was run is lecture1. The output was an error message stating that the cd command cannot be used on a file. This is because this command can only used on a directory as it displays the name of or changes the current directory.**

```
[user@sahara ~/lecture1]$ ls README
README
```
**This working directory when the command was run is lecture1. The output was the file name. When ls is used on a file rather than a directory it repeats its name. The output is not an error.**

```
[user@sahara ~/lecture1]$ cat README
To use this program:

javac Hello.java
java Hello messages/en-us.txt
```
**This working directory when the command was run is lecture1. The output is what was in the file README. The cat command reads the file and prints files in the order of the arguments. In this case the only argument was README and its contents are printed. The output is not an error.**

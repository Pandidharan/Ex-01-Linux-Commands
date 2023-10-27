# Ex-01-Linux-Commands


## Aim:

To study the execution of various Linux operating system commands.

## Linux:

Linux is an open-source operating system. The kernel is the heart of Linux OS which
 
helps the communication between hardware and software. The main advantage of Linux was that programmers can use Linux kernel to design their own custom OS.

Linux Commands:
All basic and advanced tasks can be done by executing commands. The commands are executed on Linux terminal. Linux commands are case sensitive.


## Commands:

### 1)	ls Command

The ls command is used to display a list of content of a directory.

 Syntax: ls
 
 ![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/89ec8929-4d16-4b35-b3d2-51da771c3176)



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/4462be43-d757-489e-9bb7-16fcd5dd9926)


 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/d1b12143-7ad7-49c8-bd38-7cf7eb9f12f6)



### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>



### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/b1ab67a9-4859-4817-9c4e-8b4b389658be)



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/bdc06415-5a10-4bfe-9c81-e41d48fb136f)


 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/bbbb8312-3af5-4413-943d-aab7f8217d96)




### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/f5bd04e8-eb71-4705-9305-1dd5b9358298)



### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/6c107376-1e37-483a-82bd-1f12d517f30f)



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/8f763495-65ce-4473-b9bf-269b9357fd76)


 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/681e1834-6cdd-415c-a937-c3909547fe46)



### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/7b2bb1a6-603a-4b69-881e-73d1bb80179d)



### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/cdc4c338-d072-48bb-87d8-f75fa8f93d73)


 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/f05843c4-c7a6-489c-953d-bda59f3ade9f)



### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/7e551196-6ac1-4d9a-86c3-ce574b1fc0e9)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/db2ac5ee-1f93-461c-a3c7-a7fcd42e6c8f)


### 17)	chmod Command

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<options><permissions><file_name>

### 18)	tar Command

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved]

$ tar xvzf file.tar *.c
 
### 19)	chown Command

The chown command is used to change ownership.

Syntax: chown owner_name file_name

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/e9ae4918-c1ef-4b6b-a329-fabe6d85dd05)


### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/e3bed057-6b8e-4660-980d-05b3a1ff4a0f)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/43295fc4-f5c7-49e7-857b-1ddbb6e305d0)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/81ce8d44-007a-408b-8196-c609009a90ac)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/8c795c6b-5080-4693-95f6-e06ca2e02860)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/eb441626-b28c-45b1-b5ae-26076342bb7e)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/afd6ed9f-8950-4f6f-9280-27ba0ecec915)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/a81c11b1-04ce-4a1a-9db4-8b9ed5034be3)



### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/11bf4f52-1709-4566-90b9-7c45f0822e6d)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![image](https://github.com/Pandidharan/Ex-01-Linux-Commands/assets/118343569/bebb1d24-8e90-4ec5-9bfb-538b8f0dd942)


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”



## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.

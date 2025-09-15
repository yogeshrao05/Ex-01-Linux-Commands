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

<img width="1216" height="265" alt="image" src="https://github.com/user-attachments/assets/66aadaa2-3b69-40ee-96e9-44d4d7848ed1" />



### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

<img width="1104" height="96" alt="image" src="https://github.com/user-attachments/assets/c092adfa-0430-4e68-afed-28951829935c" />

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

<img width="1046" height="75" alt="image" src="https://github.com/user-attachments/assets/1105e0d5-3945-45f4-9f76-65c8e579721b" />


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

<img width="608" height="41" alt="image" src="https://github.com/user-attachments/assets/afaa3ca0-f2cd-4d78-a47b-38a0910df86d" />


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>

<img width="610" height="45" alt="image" src="https://github.com/user-attachments/assets/c59e33dd-7c7a-415b-a6f1-be743a3fa8dd" />


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="624" height="75" alt="image" src="https://github.com/user-attachments/assets/ba36866c-7b90-468e-a5eb-53ee5c3731f3" />

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

<img width="607" height="44" alt="image" src="https://github.com/user-attachments/assets/fbe6bd72-96dd-41b4-a51b-15e27813433f" />



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="645" height="21" alt="image" src="https://github.com/user-attachments/assets/805a3b97-cfc0-433c-9f91-82cd3ad6d495" />


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

<img width="622" height="67" alt="image" src="https://github.com/user-attachments/assets/de9a0d41-7d67-4954-8117-6f4be5525ae1" />


### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

<img width="600" height="21" alt="image" src="https://github.com/user-attachments/assets/e0ddb833-badb-490d-992b-7984142db505" />

 
## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="684" height="166" alt="image" src="https://github.com/user-attachments/assets/173fc676-cc57-4525-b902-5e61f90be193" />


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

<img width="612" height="201" alt="image" src="https://github.com/user-attachments/assets/59a98116-a44a-4158-9638-23c929ca0e1b" />


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

<img width="474" height="202" alt="image" src="https://github.com/user-attachments/assets/e3c3395a-0413-4984-aaca-c75211a3e472" />


 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="726" height="78" alt="image" src="https://github.com/user-attachments/assets/b8f475c9-b748-482c-a78f-9a52829fc60d" />



### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

<img width="622" height="41" alt="image" src="https://github.com/user-attachments/assets/9920417b-23d4-4936-8305-34d0cad14486" />


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="707" height="128" alt="image" src="https://github.com/user-attachments/assets/f7d3dec2-036e-41a9-a9ec-c8f779c0aadb" />


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

<img width="579" height="199" alt="image" src="https://github.com/user-attachments/assets/50465d0c-6c06-46d7-ad95-55fd4433d14b" />

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="679" height="59" alt="image" src="https://github.com/user-attachments/assets/25f91bdc-4a2e-44c1-9a62-d41d0168652b" />


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="874" height="178" alt="image" src="https://github.com/user-attachments/assets/563e6594-3009-496d-8441-009857c1d38b" />


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder


### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

<img width="647" height="38" alt="image" src="https://github.com/user-attachments/assets/d85a5355-58dd-42a7-9d70-732862fe692b" />


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

<img width="696" height="187" alt="image" src="https://github.com/user-attachments/assets/b6e08d86-a2a8-4aae-9a80-ab8e591b7c77" />



### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

<img width="692" height="131" alt="image" src="https://github.com/user-attachments/assets/a03f94a1-f80f-4386-b1ce-9811d78efa89" />


 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="627" height="161" alt="image" src="https://github.com/user-attachments/assets/d69f2139-2687-407a-8b9d-e9f3c0ea7ae8" />



### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="704" height="186" alt="image" src="https://github.com/user-attachments/assets/6ce8615d-2bd5-43c0-bb4f-49c25d4362e1" />


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>
<img width="858" height="81" alt="image" src="https://github.com/user-attachments/assets/bafa07b4-e2ea-4833-9d45-ba793e6fd4f4" />


 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="730" height="238" alt="image" src="https://github.com/user-attachments/assets/2ce04712-7ff0-482f-b188-35c90d23bfc4" />


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”





















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.

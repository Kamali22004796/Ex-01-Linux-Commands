# Ex-01-Linux-Commands

# Name: kamali E
# dept: cse - iot
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
 
![image](https://github.com/user-attachments/assets/a6bd3756-6323-4efa-ac06-07cd864418ef)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd

![image](https://github.com/user-attachments/assets/3d3a273b-f055-41cd-8eae-f654ca8f7333)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>

![image](https://github.com/user-attachments/assets/a73abb8e-ff73-4472-8365-6929a72b8ba2)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![image](https://github.com/user-attachments/assets/a03e1c8a-5674-4ee3-83b2-efe014b61799)


### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>



### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

![image](https://github.com/user-attachments/assets/051a1128-6eaa-446a-ac62-6a6662139052)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>

![image](https://github.com/user-attachments/assets/8f935475-f923-4d1c-ba80-ef844b236b80)


### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

![image](https://github.com/user-attachments/assets/5aa9b1a1-b8f4-4845-9215-9a106d011686)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![image](https://github.com/user-attachments/assets/8a0ee86d-4bc7-44c6-9142-20cada6eb0ad)



### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

![image](https://github.com/user-attachments/assets/c7f30902-7d0e-44eb-81d6-49f167ecf778)

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

![image](https://github.com/user-attachments/assets/5091551c-9f5a-4930-8a85-f88eaca22f10)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>

![image](https://github.com/user-attachments/assets/a796fd81-df4e-4ff4-ae87-9a02191c08e2)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>

![image](https://github.com/user-attachments/assets/2734daa8-df16-4f6c-b4f3-75103a6f1566)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

![image](https://github.com/user-attachments/assets/bcfc49c4-9cb0-476f-9140-5c6918054fbe)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/user-attachments/assets/a804b1b0-6e10-4759-84af-e4770a9b87f6)


### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

![image](https://github.com/user-attachments/assets/17d7155a-2598-44ff-8e3b-fdc7c72a7735)

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

![image](https://github.com/user-attachments/assets/8fcd2a59-619b-40d8-879b-c92da3273b06)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

![image](https://github.com/user-attachments/assets/d54a9ff0-a798-4e27-8e21-99b5497663c8)

### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

![image](https://github.com/user-attachments/assets/37d5f49f-2747-4aa7-9516-9dcbda1376a9)


### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 
### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>

![image](https://github.com/user-attachments/assets/76e44713-d614-489a-889b-8ba94727462b)


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..

![image](https://github.com/user-attachments/assets/c019e93e-9c2d-46ff-9fbc-d28f2d12d3ea)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>

![image](https://github.com/user-attachments/assets/6289e0c5-669c-4d47-8f62-2e3c0b650062)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

![image](https://github.com/user-attachments/assets/a321bd2a-af05-4a2a-a4b7-f898d4329713)


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear

![image](https://github.com/user-attachments/assets/77d6de1f-5e0d-48cf-879a-1f769d3bb163)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

![image](https://github.com/user-attachments/assets/352984c7-4189-4c4f-b9c0-e943536ca5f9)

 
### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

![image](https://github.com/user-attachments/assets/8ba46b1a-5a65-402e-b547-ccc5bb2f036a)


### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.

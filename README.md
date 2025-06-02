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
![image](https://github.com/user-attachments/assets/767a5efe-c4de-4ff8-8156-2228be0d97a6)


### 2)	pwd Command

The pwd command is used to display the location of the current working directory.

Syntax: pwd
![image](https://github.com/user-attachments/assets/79a24af6-39cb-436f-87d4-22c4fd5f6d75)

 
### 3)	mkdir Command

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir <directory name>
![image](https://github.com/user-attachments/assets/133e02f3-8601-4050-84e4-64eb9e8296ef)


### 4)	rmdir Command

The rmdir command is used to delete a directory.

Syntax: rmdir <directory name>

![image](https://github.com/user-attachments/assets/655b5deb-d647-4384-8363-04cfb94b6d17)

### 5)	cd Command

The cd command is used to change the current directory.

Syntax: cd <directory name>
![image](https://github.com/user-attachments/assets/ce99b684-0120-49d6-acca-059d2a145e80)


### 6)	cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..
![image](https://github.com/user-attachments/assets/59a46bce-4319-47f4-98c2-640e589f11cd)

 
### 7)	cp Command

The cp command is used to copy a file or directory.

Syntax: cp <existing file name> <new file name>
![image](https://github.com/user-attachments/assets/aad144ce-0b5f-4e5d-aa1e-aa79c7ad82c2)



### 8)	gedit Command

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name
![image](https://github.com/user-attachments/assets/aa0aa08f-73eb-4977-ad73-435dd499d4a7)


### 9)	su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su <user name>

![image](https://github.com/user-attachments/assets/56e54100-3911-4a14-ba38-b538408312b1)

### 10)	mv Command

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv <file name> <directory path>

 ![image](https://github.com/user-attachments/assets/d3114861-09b9-4569-b1f7-6007feb06f70)

## 11)	rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files
![image](https://github.com/user-attachments/assets/392d3b7e-c0dd-477d-845b-a682dcf0dfc5)


### 12)	head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head <file name>
![image](https://github.com/user-attachments/assets/5a1c121f-660b-43a4-a20e-ff2bf7962e5e)


### 13)	tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail <file name>
![image](https://github.com/user-attachments/assets/670d36e0-b97a-4802-bde0-02843df07ce0)

 
### 14)	id Command

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id
![image](https://github.com/user-attachments/assets/e510c74c-ace9-426f-a546-b5f6bdccaf36)


### 15)	grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep <search word>

![image](https://github.com/user-attachments/assets/f60d069e-6b0b-4dbe-824a-ac7b57f11547)

### 16)	tr Command

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>
![image](https://github.com/user-attachments/assets/8b4e3cf3-a448-4f09-bddf-f5294cea03dd)

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
![image](https://github.com/user-attachments/assets/4496334f-6da0-407a-a605-777f0d6b2b70)

### 20)	make Command

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….
![image](https://github.com/user-attachments/assets/73da9246-6d29-4d9d-ad78-abc6732cba1e)


### 21)	ifconfig Command

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]
![image](https://github.com/user-attachments/assets/0320b8e2-2984-4c0d-8b51-e503f222b2f0)

### 22)	chmod 777 Command

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name
$chmod -R 777 /path/to/file/or/folder
 ![image](https://github.com/user-attachments/assets/9d357e92-54ae-409e-ab92-769be3675a48)

### 23)	host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host <domain name> or <ip address>


### 24)	gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip <file1> <file2> <file3>..
![image](https://github.com/user-attachments/assets/48132589-fcfb-40c2-8188-d75e7527f49c)


### 25)	sort Command

The sort command is used to sort files in alphabetical order.

Syntax:sort <file name>
![image](https://github.com/user-attachments/assets/2aaa568f-f2cd-4d52-a4d2-621f4be0e16e)

 
### 26)	cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal


### 27)	clear Command

Linux clear command is used to clear the terminal screen.

Syntax: clear
![image](https://github.com/user-attachments/assets/9ba618d4-a022-4ce1-90f3-2f9b941cf29b)


### 28)	mail Command

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject" <recipient address>

 ![image](https://github.com/user-attachments/assets/d969b3da-a033-4970-97b6-ee214fe62788)

### 29)	df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df
![image](https://github.com/user-attachments/assets/ca8a3018-35a3-4c01-9891-ac95c0d63fe8)

### 30)	find Command

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

![image](https://github.com/user-attachments/assets/55ada786-f784-4c0e-880b-36652c22f445)




















## Result:

Thus, the execution of various Linux commands is executed successfully using Ubuntu OS.

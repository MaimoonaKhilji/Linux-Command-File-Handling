# Linux-Command-File-Handling


1.	Try the following command sequence:
-	cd
-	pwd
-	ls –al
-	cd .
-	pwd     (where did that get you?)
-	cd ..
-	pwd
-	ls –al
-	cd ..
-	pwd
-	ls -al
-	cd ..
-	pwd     (what happens now)
-	cd /etc
-	ls -al | more
-	cat passwd
-	cd -
-	pwd
2.	Explore /dev. Can you identify what devices are available? Which are character-oriented and which are block-oriented? Can you identify your tty (terminal) device ; who is the owner of your tty (use ls -l)?
Can you identify what devices are available?  $ mount
Which are character-oriented and which are block-oriented? Their type are also indicated as "c" or "b" in the permission column of the ls -l output.
For tty information: $ w
3.	Change back into your home directory.
4.	Create a directory called OSLab2.
5.	Make subdirectories called work and play .
6.	Delete the subdirectory called work.
7.	Copy the file /etc/passwd into play directory in single command.
8.	Move it into the subdirectory play.
9.	What is the difference between listing the contents of directory play with ls -l , ls and ls -L?
10.	Create a file called hello.txt that contains the words "hello world". 
11.	Imagine you were working on a system and someone accidentally deleted the ls command (/bin/ls). How could you get a list of the files in the current directory? Try it.
12.	 How would you create and then delete a file called "$SHELL"? Try it.
13.	How would you create and then delete a file that begins with the symbol #? Try it.
14.	How would you create and then delete a file that begins with the symbol -? Try it.
15.	What is the output of the command: echo {con,pre}{sent,fer}{s,ed}? Now, from your home directory, copy /etc/passwd and /etc/group into your home directory in one command given that you can only type /etc once.
16.	Still in your home directory, copy the entire directory play to a directory called work.
17.	Delete the work directory and its contents with one command. Accept no complaints or queries.
18.	Experiment with the options on the ls command. What do the d, l, R and F options do?
19.	Try ls --help
 

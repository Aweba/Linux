<p>cd : change directory</p>
we can use this command with an absolute o relative path
Example:
	suposse that we are in /home
	relative path:
	cd ../etc
	absolute path:
	cd /etc
	both will take you to /etc
Also you can use 
	cd : the same directory
	cd .. : one directory before

ls: list directory contents
we can use this command with an argument to do an specific action
	ls -a : it show all the archives even the hidden
	ls -l --author : print the autor for each file
cal : display a calendar
If no arguments are specified, the current month is displayed.
echo : display a line of text
For example 
	echo "Hola mundo" 
	>>Hola mundo
	echo $HOSTNAME
	>>localhost.localdomain
pwd: print name of working directory

grep : print lines matching a pattern
 For example if you have the archive fiore.txt
	Hello world
	The world is a little place to live
	I'm writing this archive
 And you type in the prompt 
	grep world fiore.txt
 The output in the console will be
	Hello **world**
	The **world** is a little place to live
cat : concatenate files and print on the standard output
more : it shows you the file but let you move just to the end of the file.
less : it let you move to the end or the opposite too.
mkdir : make directories
lspci : list all PCI devices
cp : copy files and directories
man : it shows you an interface to the on-line reference manuals
route : show / manipulate the IP routing table
rm : remove files or directories
mv : move/rename files
ipconfig : configure a network interface

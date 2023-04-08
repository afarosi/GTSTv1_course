# Linux For User
## Overview of kali linux
* Specifically, i will going to show you with
“kali linux” with gnome but you can have
any kinda, BUT Debian is recommended.
* Previously known as Backtrack
* Login Interface
* You can switch between your Desktop environment
# There are 4 Types of desktop environment on linux
*1 Gnome
*2 KDE plasma
*3 mate
*4 XFCE
# 1) Information gathering
* ●Tools for information gathering, in system,network, host
* dmitry
* ike-scan
* legion
* maltego
# 2) Vulnerability Analysis
* ●Tools for Finding Vulnerabilities
* lynis 
* nikyo
* nmap
* unix-prives
# 3) Web Application Analysis
● Tools for Finding
Vulnerabilities and
exploits on websites.
* burpsuite
* commix
* httrack
* skipfish
# 4) Database Assessment
● Tools for Finding
Vulnerabilities and
exploits on Databases.
* jSL injecti
* mdb-sql
* oscanner
* sidguesser
# 5) Password Attacks
● Tools for exploiting
Passwords for
login,websites,application,
windows..
* cewl
* crunch
* john
* medusa
* ophcrack
# 6) Wireless Attacks
● Tools for exploiting
Wireless Systems like wifi,
bluetooth..
* aircrack-ng
* chirp
* mdk3
* pixiewps
# 7) Reverse Engineering
● Tools for exploiting
Softwares, Mobile
Applications and any
binary files
* apktool
* NASM shell
* clang++
* dex2jar
# 8) Exploitation Tools
● Tools for exploiting
Softwares, Mobile
,Computers ,websites and
any things
* armitage
* searchsploit
* almap
* beef xss fra
# 9) Sniffing & Spoofing
● Tools for Listening or
hijacking networks
* hamster
* driftnet
* mitmproxy
* wireshark
# 10) POST exploitation
● Tools for Maintaining our
access. Used after
exploiting a system
* nishang
* weevely
* exe2hex
* powersploit
# 11) Forensics
● Tools for Doing researches
and investigate a Cyber
Attacks.
* autospy
* binwalk
* galleta
* chkrootkit
# 12) Reporting tools
● Tools for Report
preparation. After some
forensic you will get data
and you will write report
and these tools will help
you.
* cutycapt
* maltego
* pipal
* recordmyd
# 13) Social Engineering tools
● Tools Used for Social
Engineering attacks
* maltego
* msf payloa
* social engin
* backdooe-file
#14) System Services
● Buttons used to start some
services.
* beef start
* beef stop
* dradis start
* dradis stop
# 15) Usually used applications
● Softwares for some basic
purposes
# Folder managers
* 1) Dolphin
* 2) Thunar
* 3) Nautilus
# Linux Commands
*● Linux Systems uses shell. The shell help us to
Communicate with the kernel and helps to execute
codes.
*● This is the shells icon —->
*● Shell also called “Terminal
*● The terminal have 5 parts.
○ Username = rexder
○ Hostname = HunterMachine
○ Current Directory = PATH
○ Priviledge = $-(user) , #-(root)
○ Command place = _
*● Home directory is ~
*● Local directory with .
*● All directory *
# Linux Command Basics
*● On linux there are over 100
commands. But we will see
the main and the useful
only.
*● Also those commands have
their own options and
arguments.
# What is command
## “Small programs that do one task well”
# ls / List Directory
SYNOPSIS
ls [OPTION]... [FILE]...
DESCRIPTION
List information about the FILEs (the
current directory by default).
● ls -l
● ls -a
● ls filename
● ls -R => recursive
You can combine them, ls
-Rla
Linux hidden files start
with dot.
# cd / Change Directory
SYNOPSIS
cd [directory]
DESCRIPTION
It is used to change current working
directory.
● cd / => root
● cd => home
● cd .. => 1x Back
● cd ../.. => 2x Back
● cd foldername
If folder name have space you
have to add the name inside “
folder name “
cd “folder name”
# Pwd / print working directory
SYNOPSIS
pwd [-options]
DESCRIPTION
It prints the path of the working directory,
starting from the root.
Example after typing pwd:
/home/omar/Desktop/OSLab
# echo
SYNOPSIS
echo [option] [string]
DESCRIPTION
echo command in linux is used to
display line of text/string that are
passed as an argument . This is a built
in command that is mostly used in
shell scripts and batch files to output
status text to the screen or a file.
*● You can write texts into
files.
○ echo text > file.txt
*● You can add texts(append)
○ echo text >> file.txt
# cat / head / tail / less
SYNOPSIS
cat [FILE]...
DESCRIPTION
Used to show the content of a file
# touch
SYNOPSIS
touch [FILE1] [FILE2] [FILE3]
DESCRIPTION
Creates any kind of Files with the name
you gave it. With empty inside.
# Mkdir / make directory
SYNOPSIS
mkdir [FOLDER-NAME1]
[FOLDER-NAME2] [FOLDER-NAME3]
DESCRIPTION
Creates Folder with the name u gave it.
- DON’T forget to add the “ “ when you
are using folders with space between
them.
# clear
SYNOPSIS
clear
DESCRIPTION
Clears your screen.
# rm / remove
SYNOPSIS
rm [FILE1] [FILE2] [FILE3]
DESCRIPTION
Remove file.
● rm -r => recursive(4 folders)
● rm -i => for prompt(ask)
● rm -f => force delete
You can use them in combination
too like, rm -rf ‘filename’
# Cp| mv / copy,move
SYNOPSIS
cp [oldFILEplace] [newfilePlace]
Mv [oldFILEplace] [newfilePlace]
DESCRIPTION
Copy/move files & folders
# grep - global search for regular expression
● grep [options] pattern [files]
● The grep filter searches a file for a
particular pattern of characters, and
displays all lines that contain that pattern.
The pattern that is searched in the file is
referred to as the regular expression (grep
stands for global search for regular
expression and print out).
*● grep -i “search” file
○ - case insensitive
*● grep -c “search” file
○ - count numbers
*● grep -l “search” *
○ - displays filename
*● grep -R “search” foldername
○ - search text in folders
# Wc - word count
SYNOPSIS
wc [OPTION]... [FILE]...
DESCRIPTION
It is used to find out number of lines,
word count, byte and characters count in
the files specified in the file arguments.
Line(-l) word(-w) byte(-c)
# Multiple Command Executions
*● You can run/ execute multiple commands in 1 line.
*● using 3 methods:
○ And ( && )
○ Or ( || )
○ Pipeing( | )
# AND ( && )
On AND operation All
commands you entered will be
executed. If both are working
without error
# OR ( || )
On OR operation the
command will be executed. If it
have error or not
# Piping ( | )
On pipe, will help you run
commands by using the output
of the 1st command as the
input for the next one.
# Class is Over!
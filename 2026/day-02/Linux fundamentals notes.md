******* Linux Fundamentals day-01 ******** Linux Torwalds (Linux owner)

What is operating system --> Software to run CPU.

Different Operating systems :
1) Windows
2) MacOs
3) Linux Os


Client OS --> Designed for individual users, used on PCs, Laptop.
Main Features : (1) Graphical User Interface (GUI) focused  (2) Optimized for daily tasks  (3) Limited number of concurrent users  (4) Less powerful networking and security control.
Examples : Windows 10, MacOS, Ubuntu Desktop


Server OS  --> Designed to serve multiple clients, Runs on servers/ Data centers.
Main Features : (!) can handle thousands of users.  (2) Optimized for Performance, Stability, Uptime.    (3) Advanced security and access control.  (4) Often CLI-based (minimal GUI)
Examples : Windows server 2022, Red Hat Enterprise Linux (RHEL) , Ubuntu Server.


**** Ways to install Linux in your system *****
1) Cloud Server (AWS, AZURE,GCP,UTHO etc)
2) Virtual box
3) Windows subsystem for Linux (WSL oe WSL2)
4) Dual book ( not recommended)
5) Docker 
6) Playground ( Linux playground Killercoda )
7) Use Linux as OS
8) GitBash


*** Linux :
Linux us an open- source operating system built around the Linux Kernel, It manages hardware, processes, files and users and let application run safely.

Linux Architecture (How it is build)  :  ASK principle (A - Application , S - SHell , K - Kernal )
Linux works in layers :

User ---> Applications (ls, vi, python, browsers)   ----> SHell (bash, sh)  --> Kernal ---> Hardware ( CPU, RAM, Disk, Network) 

Main components :

1) Kernal (Heart of Linux)  ---> The Kernal talks directly to hardware. It handles Process management, File systems, Securities & Permissions, Networking.|
                            ---> Kernal contain program which interact with Hardware. It uses Binary [ 0, 1 ] . ----> C language to convert Binary
2) Shell ( command Interpreter)  ---> SHell is interface between user and Kernel    [CLI --> Command Line Interface] 
3) Applications ( User Space) ---> Browsers, Editors, Database
4) File system (Everything is a file)   ---> Examples : Hardware --> /dev , Config --> /etc , User data --> /home , Logs --> /var/log



AWS ---> Elastic compute cloud ( EC2) 


Linux Flavors / Distributions :
1) Ubuntu 
2) Fedora
3) CentOs (Generally used in startups )
4) RHEL ( Red Hat Enterprise Linux )


*** UNIX is SHELL based operating system with a command line interface (CLI).
** Linux is UNIX based operating system which is open source.


*** Different Shell types :
1) SH  --> Standard shell  (First Shell)
2) bash --> born again SH    (Wiedly used)
3) C SH --> corn shell
4) Z SHELL ---> 
5) Fish Shell 



"/"   --> root directory 


**************** Different Directories in Linux *****************
1) Var    ----> Anything that can vary (Variable)
Ex : Backups, Cache, Log, Lib, crash, local etc

2) tmp   ---> Temporary folder, anyone can use this folder  --> this folder is not that much protective.

3) proc --> process are running in this folder

4) mnt   ---> To mount external storage devices and filesystems.

5) home   ----> Users are present in the home.
EX: Ubuntu

6) dev --> Device

7) snap   ---> to install something

8) sbin   ---> System Bineries   ---> System level binaries file kept in the sbin.

9) bin ---> binaries, either 0 or 1 . 

10) root  ---> root user that is handling all the Linux system.  ( Super user) 

11) media   ---> to save file, folders, images, videos.

12) etc  ---> all configuration you can find in this folder.
Ex : Hostname, hosts, network configuration

13) boot   ---> when you are starting any system, that system can run program in the RAM and because of that program your operating system will start, that process is nothing but booting.
     EX:  GRUB ( Grand Unified Bootloader )  
14) 

***************************************************************

Packages in Linux :

Ubuntu  --> Packages ---> Package Manager (help to install packages in Ubuntu)  --> that package manager is known as "apt"    (here apt --> Application Package Manager) 
RHEL  ---> dnf or YUM


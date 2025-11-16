Assignment 02
Basics of Linux and Open-Source Tools


Course Code: ETCCCP105
Course Name: Computer Science Fundamentals & Career Pathways








                                              Name = Anant Kumar
                                    Roll no. = 2501730189
                                 Course = B-Tech CSE AI/ML
                                     Section = A



1. Introduction
A popular open-source operating system, Linux is renowned for its dependability, adaptability, and leadership in server, cloud, DevOps, cybersecurity, AI, and embedded systems. Shell scripting and command-line abilities are crucial for professional workflows and system automation. 
The purpose of this assignment is to give students practical experience installing Linux using VMware Workstation Pro, running necessary shell commands, creating automation shell scripts, and submitting their work to GitHub. These exercises promote practical IT skills needed for technical development and system administration.

2. Step 1 – Linux Installation (Using VMware Workstation Pro)
2.1 Hardware Configuration (Used in VM Setup)
Component	Configuration
CPU	2 Cores
RAM	4 GB
Storage	15-20 GB (virtual disk)
OS ISO	Ubuntu 24.04.3
Software	VMware Workstation Pro (Windows)

2.2 Installation Steps
Step 1: Install VMware Workstation Pro
•	Download VMware Workstation Pro installer from the official VMware website.
•	Run the installer → Click Next → Accept License Agreement → Complete installation.





Step 2: Create a New Virtual Machine 
•	Open VMware Workstation Pro
•	Click Create a New Virtual Machine
•	Select Typical (Recommended) → Next
•	Choose Installer disc image file (ISO)
•	Browse and select Ubuntu 22.04 LTS ISO
 



Step 3: Configure Guest Operating System
•	Guest OS: Linux
•	Version: Ubuntu 64-bit

Step 4: Name the Virtual Machine & Choose Location
•	VM Name: Ubuntu 64 bit
•	Location: Choose preferred folder.

Step 5: Allocate Disk Space
•	Maximum disk size: 15-20 GB
•	Select Store virtual disk as a single file

Step 6: Customize Hardware
•	Memory: 4 GB
•	Processors: 3 cores
•	Network Adapter: NAT
•	Display: Accelerate 3D graphics (optional)
 
Step 7: Start the Virtual Machine
•	Click Finish
•	VM boots using the Ubuntu ISO.






Step 8: Install Ubuntu
•	Click Install Ubuntu
•	Keyboard layout → Continue
•	Select Normal Installation
•	Select Erase disk and install Ubuntu (only affects virtual disk)
•	Set username, password, and computer name.

Step 9: Complete Setup
•	Installer finishes → Restart VM
•	Login to Ubuntu desktop.
 









3. Step 2 – Shell Command Implementation (20 Commands)
Documented with syntax, purpose, and example outputs.

File Navigation Commands
1. pwd
Syntax: pwd
Shows current directory path.
________________________________________
2. ls
Lists directory contents.
________________________________________
3. ls -l
Long listing format with permissions.
________________________________________
4. cd
Change directory.
Example: cd /home/user/Documents
________________________________________
5. tree
Shows folder structure in tree form.
(May need installation: sudo apt install tree)
________________________________________
File & Directory Management
6. mkdir — create directory
mkdir projects
________________________________________
7. touch — create empty file
touch notes.txt
________________________________________
8. cp — copy files
cp file.txt backup/
________________________________________
9. mv — move/rename
mv test.txt old.txt
________________________________________
10. rm — remove file
rm temp.txt
________________________________________
11. rm -r — remove folder
rm -r foldername
________________________________________
Permissions Management
12. chmod
Change permissions.
chmod 755 script.sh
________________________________________
13. chown
Change owner of file.
sudo chown user:user file.txt
________________________________________
Process Monitoring
14. ps
View active processes.
ps aux
________________________________________
15. top
Live system monitoring tool.
________________________________________


16. kill
Terminate a process.
kill 1234
________________________________________
Networking Tools
17. ping
Test connectivity.
ping google.com
________________________________________
18. ip a
Show network interfaces.
________________________________________
19. netstat
List active connections.
netstat -tulnp
________________________________________
20. wget
Download file.
wget https://example.com/file.zip

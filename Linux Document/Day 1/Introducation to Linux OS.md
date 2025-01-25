1.Introducation to Linux Operating system

A.What is Linux ?
  -Linus Torvalds in 1991
  -Linus + Unix  = Linux 
  -OS vs Kernal  
  
2.History of Linux 
  -Origins : Minix OS
  -Evolution :Various distros
  
4.Key Feartures of Linus
 
   - open source: 
   - Security:
   - Stability & Performance 
   - Portability :
   - Multi-User & MultiTasking:

5.Linux Distor's:
   -ubuntu:
   -Fedora:
   -Debian:
   -Centos:
   -Arch


6.Linux Desktop Enviroment 

   -GNOME:
   -KDE Plasma:
   -XFCE:
   -LXDE.
   
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

2.Types of Linux
   -Genearl-Purpose
       Ex:Ubuntu,Debian,Fedora
	 
	 -Enterprise Linux Distor
	    Ex:RHEL,Centos,SUSE.
		
	-Specialized Linux Distor
	  Ex:Kail,Raspberry Pi OS,Arch Linux
	  
	  -Rolling Releases:
	   -Ex:Arch ,Manjaro,Gentoo

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

	
3.Which Linux Operating System are mostly used in cloud and Devops
 1.Ubuntu
 
 2.Centos/RHEL:
 
 3.Debian:
 
 4.Fedora:
 
 5.OpenSUSE:
 
 6.Alpine
 
 7.Arch:

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

4.How to create Ubuntu Linux Instance in AWS EC2
  -Name : MUM-UBT-AMI
  -Application OS image:Ubuntu
  -Instance Type: t2.micro
  -Key pair :MUM-UB-AMI-WEB-KEYPAIR
     * Key pair Type         - RSA
	 * Private Key file format - ppk
	 
  -Network Setting 
    *VPC    - Default VPC Wil select
	
	*Subnet - Default Subnet will select
	
	*Auto-assign public IP -  Enable 
	
	*Firewall(Security Groups) - Select Existing Security Group
    
	*Configure storage      - 8 Gib gp3
	
     *Start Launch Instance
5.How to Create Amazon Linux Instance in AWS EC2?
   -Name : MUM-AL-AMI
   -Application OS image: Amazon-Linux
   -Instance Type: t2..micro
   -Key Pair : MUM-AL-AMI-WEB-KEYPAIR
     *Key pair Type  -RSA
	 *Private Key File Format: ppk
	 
   - Network Setting 
    *VPC    - Default VPC Wil select
	
	*Subnet - Default Subnet will select
	
	*Auto-assign public IP -  Enable 
	
	*Firewall(Security Groups) - Select Existing Security Group
    
	*Configure storage      - 8 Gib gp3
	
     *Start Launch Instance
 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 
5.What is your free-tier limit in AWS ?

 EC2 & EBS
    
	 - 750 hours (Window & Linux ) Per Month
	 - only create instance in t2.micro or t3.micro
	 - Ipv4 Public IP address usage 750 free hours per month
	 - EBS 30GB Storage
	 - 2 million IO's
	 - 1 Gb Snapshot
	 - 100 Gb 
	 
	 ++++++++++++++++++++++++++++++++++++++++++
	 
	 6.How many ways to connect Linux machine from AWS EC2?
	   
	  1.AWS EC2 Instance Connect
	  
	  2.Putty 
	  
	  3.Mobaxterm
	  
	  4.WinSCP
	 +++++++++++++++++++++++++++++++++++++++
Linux Dir Structure
1.Root Directory(/)
Icon : \
 The root directory is the top level of the file system.
 All other directories and files are contained within it.

2.bin
Icon : \ 
 Contains essential binary executable for system utilities and application 
 needed in Single user moder

3./boot:
 Contain boot loader files,kernel images,and other files 
 required for booting the system

4./dev:
  Holds device files,which are special files that represent hard devices

5./etc:
  Contains configuration files and scripts required 
  for system administration and configuration

6./home
 User home directories are stored here.Each user has a subdirectory within/home

7./lib:
 Conatains shared library files used by the binaries in /bin and /sbin

8./media:
 Temporary mount points for removable media such as CDs,DVDs and USB drives

9./mnt :
 Generic mount point for mounting filesystem temporarily.

10./opt
 Directory for Installing optional software packages

11./proc :
 Virtual filesystem providing information about system processes and other system

12./root:
 Home directory for the root user

	13./run
 Conatain runtime data for processes started since the last boot
 
	14./sbin :
 Contains essential system binaries,typically for system administration tasks.
 
15./src :
 Conatain data for services provided by the system.
 
 16./sys :
  Virtual file system that provides information and configuration for 
  the kernel and system devices.
  
  17./tmp:
   Temporary files Created by application are stored here.
   
   18./usr :
    Contains user utilities and applications.Subdirectories include
	/usr/bin, /usr/lib, /usr/sbin and /usr/local.
	
19./var :
 Contains Variable data files such as logs,mail,and databases.
  
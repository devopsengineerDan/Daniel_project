
PAUL ->
0752417150 Driver
0769 863503 Kiarie

-------------------
https://foht.co.ke/  Software Engineer
https://thintech.co.ke/  Consultance

-------------------

Cybersecurity firms 
onsite cybersecurity firm  contact Sam for location
Safaricom
Serianu
Sentinel
Ekraal

Law link
https://www.qub.ac.uk/courses/undergraduate/2021/law-senior-status-llb-m101/

PPoE user 0711444518
PPoE password 0000
IP address 10.5.10.52 
Gateway 10.5.10.1
tick Firewall Router 

Local Network 
IP address 192.168.88.1
Netmask 255.255.255.0(/24)
tick DHCP Server 

DHCP Server Range 192.168.88.10.192.168.88.254
tick NAT 

VPN
VPN address 8ce5083f2021.sn.mynetname.net
==============================================================================================================================================
                                                        
							<--STUFF-->

ADOBE PHOTOSHOP  1045-1656-1984-6490-9561-5688

http://127.0.0.1:8000/register?next=/

Important links

Datascience Concepts

https://t.co/zfWgEfyA8d?amp=1

https://t.co/SQamq5CSRQ?amp=1

https://github.com/jakevdp/PythonDataScienceHandbook/tree/master/notebooks

Network and Software Engineering https://mega.nz/#F!rqpiBQIa!aqY8L9NmaifoXTGVQogiWg   

Cybersecurity and AI Engineering https://mega.nz/#F!2fRgmYSa!dvEPOubQEBUiRaXu7SktBg!jXw3ySIS

Cybersecurity
[7:01 PM, 3/28/2019] Anthony - CEH: https://katcr.co/torrent/364470/udemy-practice-your-first-penetration-test-kali-amp-metasploit-lab.html
[7:02 PM, 3/28/2019] Anthony - CEH: https://monova.to/167CEE868BB34A178B72B530BE27CD98EFBE0688
[7:03 PM, 3/28/2019] Anthony - CEH: https://katcr.co/torrent/307838/udemy-ethical-hacking-with-metasploit-the-penetration-testing-tool.html

Applying for Attachment:

Networks  
Unitel Kenya Contacts:
0722774801
0722782035
info@unitel.co.ke
Vision Plaza, Mombasa RD.

Data Science    https://okhi.recruiterbox.com/jobs/fk0j7cr/
Cybersecurity   https://www.un-yk.com/
Freelance       Appwork
Fitness         https://www.youtube.com/watch?v=3p8EBPVZ2Iw    

*********************************************************************
0713835028*

<a href="mailto:dancunmanyinsait@gmail.com" target="_blank">
                       Email: dancunmanyinsait@gmail.com
                    </a>

web: gunicorn waweru.wsgi --log-file -


*********************************************************************

==================================

PHONE BACKUP

https://findmymobile.samsung.com
Model number:  SM-G950FD 
Serial number: RF8K21X3L2K
IMEI (slot 1): 355258091801717
IMEI (slot 1): 355259091801715

KRA 
A012540149K
engineerDaniel@1234

Microsoft Teams: conardmomanyi1234

SAF PORTAL: @@aUrsAP@w9x.j@

ID: 35687960
#equity: 0764465804
#jkuat co-op acc: 01129098952900
#equity acc: 1520179881302
#equity business paybill: 247247
saf: 0711444518
airtel: 0733712755
telkom: 0778860407


http://portal.jkuat.ac.ke/Home/Index
=================================================================================================================================================================
                                                                    
								    
						     <--  SYSTEM UI AND INPUT/OUTPUT -->

MAINTENANCE OF SSD
sudo systemctl enable fstrim.timer
systemctl status fstrim.timer 


GRUB RESCUE ERROR FIX

sudo update-grub2
sudo grub-install /dev/sda

sudo add-apt-repository -y ppa:yannubuntu/boot-repair
sudo apt-get update
sudo apt-get install -y boot-repair && boot-repair

=================================

REMOVE

sudo rm -rf 

=================================

FIX FLASH ON UBUNTU TERMINAL 

sudo fdisk -l

1st option
sudo mkfs.msdos -f 32 /dev/sdb
DEFRAGMENT sudo e4defrag /dev/sda7

2nd option
udisksctl power-off -b /dev/sdb

FIX FLASH ON WINDOWS TERMINAL 
diskpart
list disk
attributes disk
attributes disk clear diskonly
exit



=================================
UBUNTU TRANSPARENCY(MENU BAR AND TAB)
Install (Dynamic Panel Transparency ) in ubuntu softwares
-------------------------------------------
gsettings set org.gnome.shell.extensions.dash-to-dock transparency-mode 'FIXED'
gsettings set org.gnome.shell.extensions.dash-to-dock background-opacity 0.2
-------------------------------------------
Install  dash-dock extension 
-------------------------------------------
(ARCH && FEDORA) ENABLE PANTHEON DESKTOP ENVIRONMENT
sudo systemctl disable lightdm.service
sudo systemctl enable gdm.service

(DEBIAN) ENABLE PANTHEON DESKTOP ENVIRONMENT
sudo systemctl disable lightdm.service
sudo systemctl enable gdm.service
 systemctl start gdm

(UBUNTU 20- ONWARDS )XFCE INSTALLATION 
sudo add-apt-repository ppa:xubuntu-dev/staging
sudo apt update

sudo apt upgrade
sudo apt install xubuntu-desktop


===============================================================================================================================================


			<---NETWORKS--->
			
VIRTUALBOX

Assigning static ip address to the local network

(((    ifconfig OR ip a    )))
sudo ifconfig enp9s0 192.168.92.5 netmask 255.255.0.0
OR sudo ifconfig eth0 192.168.92.5 netmask 255.255.0.0


sudo route add default gw 192.168.92.1 enp9s0
ping 192.168.92.5

Assigning dynamic ip address to the local network

sudo dhclient enp9s0
----------------------------------------------------------
DHCP

sudo apt install isc-dhcp-server
sudo nano /etc/dhcp/dhcpd.conf

EDIT THIS FILE
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
default-lease-time 600;
max-lease-time 7200;

ddns-update-style none;

authoritative;

subnet 192.168.92.0 netmask 255.255.255.0{
	range 192.168.92.0 192.168.92.100;
	option routers 192.168.91.1;
	option subnet-mask 255.255.255.0;
	option domain-name-servers 192.168.92.1, 8.8.8.8;
}

host Windows7{
	hardware ethernet 00:0c:29:e6:75:b9;
	fixed-address 192.168.92.1;
}
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
sudo systemctl restart isc-dhcp-server
sudo systemctl status isc-dhcp-server


===============================================================================================================================================


nmcli connection add con-name 'Ethernet' ifname enp9s0 type ethernet 

sudo netdiscover 
rfkill 

sudo service NetworkManager start
sudo service NetworkManager stop 

MICROTIK
startx
service gdm3 restart 

			<---SYSTEM--->
			
sudo passwd root -Change password for root
 
(PHONE)TERMUX

pkg install lynx
termux-setup-storage

Install Genymotion (ANDROID EMULATOR)
sudo apt update
sudo apt install virtualbox
Download Genymotion from the official website of Genymotion 
ls -l ~/Downloads/
chmod +x ~/Downloads/genymotion-3.0.2-linux_x64.bin
sudo ~/Downloads/genymotion-3.0.2-linux_x64.bin


+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
VIRTUAL BOX
 
RAM 4096
STORAGE 200.00GB
 
INSTALL VIRTUALBOX IN UBUNTU
sudo apt install virtualbox
 
ADDING GUEST EDITION ISO TO ENLARGE THE SCREEN + OTHER FEATURES
TERMINAL OPTION  
# su
# apt-get update && apt-get install -y linux-headers - $ (uname -r) 
# cp /media/cd-rom/VBoxLinuxAdditions.run / root / 
# chmod 755 /root/VBoxLinuxAdditions.run 
# cd / root 
# ./VBoxLinuxAdditions.run 
UI OPTION


*VIRTUALBOX GUEST ADDITIONS ISO 	http://download.virtualbox.org/virtualbox/5.0.24/VBoxGuestAdditions_5.0.24.iso		
*install kali tools ( install katoolin)

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
CHECK SYSTEM INFO
lscpu

CHECK NUMBER OF CORES AND THREADS
lscpu | grep -E '^Thread|^Core|^Socket|^CPU\('

++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
(PC)
			
Set flash sudo users

sudo adduser dan vboxusers

-------------------------------------------
Set up ssh on host machine

1st)Assigning static ip address to the local network

2nd)

sudo apt install ssh

Performing ssh

ssh pentester@127.0.0.1

       0R   USING PASSWORD
sudo ssh pentester@127.0.0.1 -p 2000

sudo service ssh status

       OR   USING KEYS
ssh-keygen
cat ~/.ssh/id_rsa.pub | ssh pentester@127.0.0.1 -p 2000 "mkdir -p ~/.ssh && chmod 700 ~/.ssh && cat >> ~/.ssh/authorized_keys"
ssh pentester@127.0.0.1 -p 2000

--------------------------------------------
Set up ssh on virtual machine
++++++++++++++++++++++++++++
sudo nano /etc/network/interfaces

EDIT THIS FILE
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
#This file describes the network interfaces availableon your system and how to activate them....
source /etc/network/interfaces.d/*

#The loopback network interface
auto lo
iface lo inet loopback

auto eth1 
iface eth1 inet static
	address 192.168.92.10
	netmask 255.255.255.0
	broadcast 192.168.92.255
	network 192.168.92.0
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

++++++++++++++++++++++++++++++
sudo nano /etc/ssh/ssh_config
sudo nano /etc/ssh/sshd_config
adduser pentester
adduser pentester sudo
service sshd status
service ssh status

++++++++++++++++++++++++++++++++++++++
Performing ssh

systemctl enable ssh.service
service ssh start

++++++++++++++++++++++++++
loginctl list-sessions 
loginctl terminate-session 
++++++++++++++++++++++++++



UPGRADING TO FEDORA HIGHER VERSION e.g 34

sudo dnf upgrade --refresh
sudo dnf install dnf-plugin-system-upgrade
sudo dnf system-upgrade download --releasever=34
sudo dnf system-upgrade reboot
sudo dnf system-upgrade clean
sudo dnf clean packages

                                        
UPGRADING TO UBUNTU HIGHER VERSION


sudo apt update && sudo apt upgrade
sudo reboot 

sudo apt --purge autoremove  ->Remove old unused kernels

sudo apt install update-manager-core
sudo do-release-upgrade
sudo do-release-upgrade -d   ->Pass the -d option to get the latest supported release forcefully
sudo reboot

lsb_release -a


Verify Linux kernel version and other log files
tail -f /var/log/my-app.log
uname -mrs
++++++++++++++++++++++++++++++++++++++++++++++++++++++

FIREWALL CONFIGURATION 

ARCH FIREWALL SETUP
sudo pacman -S ufw
sudo ufw enable
sudo ufw status verbose
sudo systemctl enable ufw.service

FEDORA FIREWALL SETUP
Installing firewalld
Install firewalld:
Run this command on the command line:

sudo dnf install firewalld
Starting firewalld
Start firewalld, by entering the following commands:

$ sudo systemctl unmask firewalld
$ sudo systemctl start firewalld
To make firewalld start automatically at system start:

$ sudo systemctl enable firewalld
Stopping firewalld
To stop firewalld, enter the following command as root:

$ sudo systemctl stop firewalld
Prevent firewalld from starting automatically at system start, enter the following command as root:

$ sudo systemctl disable firewalld
Make sure firewalld is not started by accessing the firewalld D-Bus interface and also if other services require firewalld, enter the following command as root:

$ sudo systemctl mask firewalld


DEBIAN 10 FIREWALL SETUP

Step 1  Installing UFW7
Debian does not install UFW by default. If you followed the entire Initial Server Setup tutorial, you will have installed and enabled UFW. If not, install it now using apt:

sudo apt install ufw
We will set up UFW and enable it in the following steps.

Step 2  Using IPv6 with UFW (Optional)
This tutorial is written with IPv4 in mind, but will work for IPv6 as long as you enable it. If your Debian server has IPv6 enabled, you will want to ensure that UFW is configured to support IPv6; this will ensure that UFW will manage firewall rules for IPv6 in addition to IPv4. To configure this, open the UFW configuration file /etc/default/ufw with nano or your favorite editor:

sudo nano /etc/default/ufw
Then make sure the value of IPV6 is yes. It should look like this:

/etc/default/ufw excerpt
IPV6=yes
Save and close the file. Now when UFW is enabled, it will be configured to write both IPv4 and IPv6 firewall rules. Before enabling UFW, however, you will want to ensure that your firewall is configured to allow you to connect via SSH. Lets start with setting the default policies.

Step 3  Setting Up Default Policies
If youre just getting started with your firewall, the first rules to define are your default policies. These rules handle traffic that does not explicitly match any other rules. By default, UFW is set to deny all incoming connections and allow all outgoing connections. This means anyone trying to reach your server would not be able to connect, while any application within the server would be able to reach the outside world.

Lets set your UFW rules back to the defaults so we can be sure that youll be able to follow along with this tutorial. To set the defaults used by UFW, use these commands:

sudo ufw default deny incoming
sudo ufw default allow outgoing
These commands set the defaults to deny incoming and allow outgoing connections. These firewall defaults alone might suffice for a personal computer, but servers typically need to respond to incoming requests from outside users. Well look into that next.

Step 4  Allowing SSH Connections
If we enabled our UFW firewall now, it would deny all incoming connections. This means that we will need to create rules that explicitly allow legitimate incoming connections  SSH or HTTP connections, for example  if we want our server to respond to those types of requests. If youre using a cloud server, you will probably want to allow incoming SSH connections so you can connect to and manage your server.

To configure your server to allow incoming SSH connections, you can use this command:

sudo ufw allow ssh
This will create firewall rules that will allow all connections on port 22, which is the port that the SSH daemon listens on by default. UFW knows what port allow ssh means because its listed as a service in the /etc/services file.

However, we can actually write the equivalent rule by specifying the port instead of the service name. For example, this command produces the same result as the one above:

sudo ufw allow 22
If you configured your SSH daemon to use a different port, you will have to specify the appropriate port. For example, if your SSH server is listening on port 2222, you can use this command to allow connections on that port:

sudo ufw allow 2222
Now that your firewall is configured to allow incoming SSH connections, you can enable it.

Step 5  Enabling UFW
To enable UFW, use this command:

sudo ufw enable
You will receive a warning that says the command may disrupt existing SSH connections. We already set up a firewall rule that allows SSH connections, so it should be fine to continue. Respond to the prompt with y and hit ENTER.

The firewall is now active. Run the sudo ufw status verbose command to see the rules that you have set. The rest of this tutorial covers how to use UFW in more detail, including allowing and denying different types of connections.

Step 6  Allowing Other Connections
At this point, you should allow all of the other connections that your server needs to function properly. The connections that you should allow depend on your specific needs. Luckily, you already know how to write rules that allow connections based on a service name or port; we already did this for SSH on port 22. You can also do this for:

HTTP on port 80, which is what unencrypted web servers use. To allow this type of traffic, you would type sudo ufw allow http or sudo ufw allow 80.
HTTPS on port 443, which is what encrypted web servers use. To allow this type of traffic, you would type sudo ufw allow https or sudo ufw allow 443.
There are other ways to allow connections, however, aside from specifying a port or known service. We will discuss those next.

Specific Port Ranges
You can specify port ranges with UFW. For example, some applications use multiple ports instead of a single port.

For example, to allow X11 connections, which use ports 6000-6007, use these commands:

sudo ufw allow 6000:6007/tcp
sudo ufw allow 6000:6007/udp
When specifying port ranges with UFW, you must specify the protocol (tcp or udp) that the rules should apply to. We havent mentioned this before because not specifying the protocol automatically allows both protocols, which is OK in most cases.

Specific IP Addresses
When working with UFW, you can also specify IP addresses. For example, if you want to allow connections from a specific IP address, such as a work or home IP address of 203.0.113.4, you need to specify from and then the IP address:

sudo ufw allow from 203.0.113.4
You can also specify a specific port that the IP address is allowed to connect to by adding to any port followed by the port number. For example, if you want to allow 203.0.113.4 to connect to port 22 (SSH), use this command:

sudo ufw allow from 203.0.113.4 to any port 22
Subnets
If you want to allow a subnet of IP addresses, you can do so using CIDR notation to specify a netmask. For example, if you want to allow all of the IP addresses ranging from 203.0.113.1 to 203.0.113.254 you can use this command:

sudo ufw allow from 203.0.113.0/24
Likewise, you may also specify the destination port that the subnet 203.0.113.0/24 is allowed to connect to. Again, well use port 22 (SSH) as an example:

sudo ufw allow from 203.0.113.0/24 to any port 22
Connections to a Specific Network Interface
If you want to create a firewall rule that only applies to a specific network interface, you can do so by specifying allow in on, followed by the name of the network interface.

You may want to look up your network interfaces before continuing. To do so, use this command:

ip addr
Output
2: eth0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc pfifo_fast state
. . .
3: eth1: <BROADCAST,MULTICAST> mtu 1500 qdisc noop state DOWN group default
. . .
The highlighted output indicates the network interface names. They are typically named something like eth0 or enp3s2.

If your server has a public network interface called eth0, for example, you could allow HTTP traffic to it with this command:

sudo ufw allow in on eth0 to any port 80
Doing so would allow your server to receive HTTP requests from the public internet.

Or, if you want your MySQL database server (port 3306) to listen for connections on the private network interface eth1, you could use this command:

sudo ufw allow in on eth1 to any port 3306
This would allow other servers on your private network to connect to your MySQL database.

Step 7  Denying Connections
If you havent changed the default policy for incoming connections, UFW is configured to deny all incoming connections. Generally, this simplifies the process of creating a secure firewall policy by requiring you to create rules that explicitly allow specific ports and IP addresses through.

Sometimes you will want to deny specific connections based on the source IP address or subnet, however, perhaps because you know that your server is being attacked from there. Also, if you want to change your default incoming policy to allow (which is not recommended), you would need to create deny rules for any services or IP addresses that you dont want to allow connections for.

To write deny rules, you can use the commands described above, replacing allow with deny.

For example, to deny HTTP connections, you could use this command:

sudo ufw deny http
Or if you want to deny all connections from 203.0.113.4 you could use this command:

sudo ufw deny from 203.0.113.4
Now lets take a look at how to delete rules.

Step 8  Deleting Rules
Knowing how to delete firewall rules is just as important as knowing how to create them. There are two ways to specify which rules to delete: by the rule number or by the rule itself. This is similar to how the rules were specified when they were created. Well start by explaining the delete by rule number method.

By Rule Number
If youre using the rule number to delete firewall rules, the first thing youll want to do is get a list of your firewall rules. The UFW status command has the numbered option, which displays numbers next to each rule:

sudo ufw status numbered
Output
Status: active

     To                         Action      From
     --                         ------      ----
[ 1] 22                         ALLOW IN    15.15.15.0/24
[ 2] 80                         ALLOW IN    Anywhere
If we decide that we want to delete rule 2, which allows HTTP connections on port 80, we can specify this in the following UFW delete command:

sudo ufw delete 2
This will show a confirmation prompt, which you can answer with y/n. Typing y will then delete rule 2. Note that if you have IPv6 enabled, you will want to delete the corresponding IPv6 rule as well.

By Actual Rule
The alternative to rule numbers is to specify the actual rule to delete. For example, if you want to remove the allow http rule, you could write it like this:

sudo ufw delete allow http
You can also specify the rule with allow 80 instead of the service name:

sudo ufw delete allow 80
This method will delete both IPv4 and IPv6 rules, if they exist.

Step 9  Checking UFW Status and Rules
At any time, you can check the status of UFW with this command:

sudo ufw status verbose
If UFW is disabled, which is the default, youll see something like this:

Output
Status: inactive
If UFW is active, which it should be if you followed Step 3, the output will say that its active and will list any rules that you have set. For example, if the firewall is set to allow SSH (port 22) connections from anywhere, the output might look something like this:

Output
Status: active

To                         Action      From
--                         ------      ----
22/tcp                     ALLOW IN    Anywhere
Use the status command if you want to check how UFW has configured the firewall.

Step 10  Disabling or Resetting UFW (optional)
If you decide you dont want to use UFW, you can disable it with this command:

sudo ufw disable
Any rules that you created with UFW will no longer be active. You can always run sudo ufw enable if you need to activate it later.

If you already have UFW rules configured but you decide that you want to start over, you can use the reset command:

sudo ufw reset
This will disable UFW and delete any rules that you have previously defined. Keep in mind that the default policies wont change to their original settings if you modified them at any point. This should give you a fresh start with UFW.


NETWORK ADMIN
https://medium.com/@adinika.15/installing-active-directory-on-windows-server-2012-r2-e9e614770588





REMOVE OLD UBUNTUUPDATEFILES FROM /boot

sudo apt-get-clean

First, get the name of the kernel the system is currently running by using uname like this:

-----------------------------------------------
ARCH

REMOVING OLD KERNELS
pacman -Ql pacman-contrib | awk -F"[/ ]" '/\/usr\/bin/ {print $NF}'
sudo pacman purge linux-image-5.3.0-18-generic
sudo pacman autoremove

RETAINING LTS STABLE VERSIION
sudo nano /etc/pacman.conf
....Then edit the file....
IgnorePkg = linux
sudo pacman -Syu
uname -r

-----------------------------------------------
DEBIAN

uname -sr
dpkg -l | grep linux-image | awk '{print$2}'
sudo apt-get purge linux-image-5.3.0-18-generic
sudo apt autoremove
-----------------------------------------------
FEDORA

rpm -qa kernel\* |sort -V
## dnf repoquery set negative --latest-limit ##
## as how many old kernels you want keep ##
sudo dnf remove $(dnf repoquery --installonly --latest-limit=-2 -q)
##Make Amount of Installed Kernels Permanent on Fedora## 
installonly_limit=2



FEDORA GRUB INSTALL ???? COMPLEX ????

sudo dnf reinstall grub2-efi-x64 shim-x64
sudo grub2-mkconfig -o /boot/efi/EFI/fedora/grub.cfg

-----------------------------------------------


Or if you use aptitude use this variant of the command:

sudo aptitude purge linux-image-x.x.x.1-generic


Make a note of that because that is the name of the current active kernel you donât want to remove. Now knowing that, we need to figure out what the otherâextraneousâkernels are


CREATING SWAP  AFTER LINUX INSTALLATION

In case you don't want or you're not sure how to create a swap partition, you can create a swap file which will work in the same way as partition. Here are the steps (using terminal):

Create an empty file (1K * 4M = 4 GiB).

sudo mkdir -v /var/cache/swap
cd /var/cache/swap
sudo dd if=/dev/zero of=swapfile bs=1K count=4M
sudo chmod 600 swapfile
Convert newly created file into a swap space file.

sudo mkswap swapfile
Enable file for paging and swapping.

sudo swapon swapfile
Verify by: swapon -s or top:

top -bn1 | grep -i swap
Should display line like: KiB Swap:  4194300 total,  4194300 free

To disable, use sudo swapoff swapfile command.

Add it into fstab file to make it persistent on the next system boot.

echo "/var/cache/swap/swapfile none swap sw 0 0" | sudo tee -a /etc/fstab
Re-test swap file on startup by:

sudo swapoff swapfile
sudo swapon -va
===============================================================================================================================================
                        <------DEVOPS------->

#install docker
sudo docker ps  - show no. of running pods
*sudo docker run –d –p  3000:80 daniel/helloworld –create app daniel and run instance 3000 of that specific container
*sudo docker run –d –p  3001:80 daniel/helloworld –create app daniel and run instance 3001 of that specific container
* sudo docker kill 607800a4d691 bcb86e3a2972 -  container id of 3001 and container id of 3002
#install minikube – local host testing platform of kuberenetes
#install kubectl – command line tool to interact with kubernetes  cluster
minikube start



===============================================================================================================================================

			<---CYBER SECURITY--->


===============================================================================================================================================

			<---SOFTWARE ENGINEERING (QUANTUM AI, QUANTUM MECHANICS ,AI && DIGITAL COMPUTING) : (ELECTRONICS AND MECHANICS)--->
		
                                            DESIGN PATTERNS FOR SOFTWARE ENGINEERS
 
1 Observer                                    3 Facade
2 Strategy                       4 Singleton           5  Adapter/ Bridge
  
  
  
1 Principal software engineer                  2 Software Architect
                                 3 Lead software engineer           5 Junior software engineer
                                 4 Senior software engineer

                                           
					   SOLID Design Principle
What is SOLID Design

Michael Feathers can be credited for creating the mnemonic SOLID which is based on principles from Robert C. Martin’s paper, “Design Principles and Design Patterns”.
The principles are

    Single Responsibility Principle
    Open Closed Princple
    Liskov's Substitutablilty Principle
    Interface Segregation Principle
    Dependency Inversion Principle

We will cover these in more detail shortly. The most important thing to note about the SOLID design principles is they are meant to be used holistically. Choosing one and just one is not going to do much for you. It's when used together you start to see the real value in these principles.
What is the Pythonic Way

Although there is no official definition for the Pythonic way a little Googling gives you several answers along this general vain.

    "Above correct syntax Pythonic code follows the normally accepted conventions of the Python community, and uses the language in a way that follows the founding philosophy." - Derek D.

I think the most accurate description comes from the Zen of Python.

    The Zen of Python, by Tim Peters


    Beautiful is better than ugly.
    Explicit is better than implicit.
    Simple is better than complex.
    Complex is better than complicated.
    Flat is better than nested.
    Sparse is better than dense.
    Readability counts.
    Special cases aren't special enough to break the rules.
    Although practicality beats purity.
    Errors should never pass silently.
    Unless explicitly silenced.
    In the face of ambiguity, refuse the temptation to guess.
    There should be one-- and preferably only one --obvious way to do it.
    Although that way may not be obvious at first unless you're Dutch.
    Now is better than never.
    Although never is often better than right now.
    If the implementation is hard to explain, it's a bad idea.
    If the implementation is easy to explain, it may be a good idea.
    Namespaces are one honking great idea -- let's do more of those!

One Last Thing

Before I jump right into the principles and how they relate to the Zen of Python, there's one thing I want to do that no other SOLID tutorial does. Instead of using a different code snippet for each principle, We are going to work with a single code base and make it more SOLID as we cover each principle. Here is the code we are going to start with.

class FTPClient:
  def __init__(self, **kwargs):
    self._ftp_client = FTPDriver(kwargs['host'], kwargs['port'])
    self._sftp_client = SFTPDriver(kwargs['sftp_host'], kwargs['user'], kwargs['pw'])

  def upload(self, file:bytes, **kwargs):
    is_sftp = kwargs['sftp']
    if is_sftp:
      with self._sftp_client.Connection() as sftp:
        sftp.put(file)
    else:
      self._ftp_client.upload(file)

  def download(self, target:str, **kwargs) -> bytes:
    is_sftp = kwargs['sftp']
    if is_sftp:
      with self._sftp_client.Connection() as sftp:
        return sftp.get(target)
    else:
      return self._ftp_client.download(target)

Single Responsibility Principle (SRP)

Definition: Every module/class should only have one responsibility and therefore only one reason to change.

Relevant Zen: There should be one-- and preferably only one --obvious way to do things

The Single Responsibility Principle (SRP) is all about increasing cohesion and decreasing coupling by organizing code around responsibilities. It's not a big leap to see why that happens. If all the code for any given responsibility is in a single place that's cohesive and while responsibilities may be similar they don't often overlap. Consider this non-code example. If it is your responsibility to sweep and my responsibility to mop there's no reason for me to keep track of whether or not the floor has been swept. I can just ask you, "has the floor been swept"? and base my action according to your response.

I find it useful to think of responsibilities as use cases, which is how our Zen comes into play. Each use case should only be handled in one place, in turn, creating one obvious way to do things. This also satisfies the, "one reason to change" portion of the SRP's definition. The only reason this class should change is if the use case has changed.

Examining our original code we can see the class does not have a single responsibility because it has to manage connection details for an FTP, and SFTP server. Furthermore, the methods don't even have a single responsibility because both have to choose which protocol they will be using. This can be fixed by splitting the FTPClient class into 2 classes each with one of the responsibilities.

class FTPClient:
  def __init__(self, host, port):
    self._client = FTPDriver(host, port)

  def upload(self, file:bytes):
    self._client.upload(file)

  def download(self, target:str) -> bytes:
    return self._client.download(target)


class SFTPClient(FTPClient):
  def __init__(self, host, user, password):
    self._client = SFTPDriver(host, username=user, password=password)

  def upload(self, file:bytes):
    with self._client.Connection() as sftp:
      sftp.put(file)

  def download(self, target:str) -> bytes:
    with self._client.Connection() as sftp:
      return sftp.get(target)

One quick change and our code is already feeling much more Pythonic. The code is sparse, and not dense, simple not complex, flat and not nested. If you're not on board yet think about how the original code would look with error handling compared to the code following SRP.
Open Closed Principle (OCP)

Definition: Software Entities (classes, functions, modules) should be open for extension but closed to change.

Relevant Zen: Simple is better than complex. Complex is better than complicated.

Since the definition of change and extension are so similar it is easy to get overwhelmed by the Open Closed Principle. I've found the most intuitive way to decide if I'm making a change or extension is to think about function signatures. A change is anything that forces calling code to be updated. This could be changing the function name, swapping the order of parameters, or adding a non-default parameter. Any code that calls the function would be forced to change in accordance with the new signature. An extension, on the other hand, allows for new functionality, without having to change the calling code. This could be renaming a parameter, adding a new parameter with a default value, or adding the *arg, or **kwargs parameters. Any code that calls the function would still work as originally written. The same rules apply to classes as well.

Here is an example of adding support for bulk operations.

Your gut reaction is probably to add a upload_bulk and download_bulk functions to the FTPClient class. Fortunately, that is also a SOLID way to handle this use case.

class FTPClient:
  def __init__(self, host, port):
      ... # For this example the __init__ implementation is not significant

  def upload(self, file:bytes):
      ... # For this example the upload implementation is not significant

  def download(self, target:str) -> bytes:
      ... # For this example the download implementation is not significant

  def upload_bulk(self, files:List[str]):
    for file in files:
      self.upload(file)

  def download_bulk(self, targets:List[str]) -> List[bytes]:
    files = []
    for target in targets:
      files.append(self.download(target))

    return files

In this case, it's better to extend the class with functions than extend through inheritance, because a BulkFTPClient child class would have to change the function signature for download reflecting it returns a list of bytes rather than just bytes, violating the Open Closed Principle as well as Liskov's Substituitability Principle.
Liskov's Substituitability Principle (LSP)

Definition: If S is a subtype of T, then objects of type T may be replaced with objects of Type S.

Relevant Zen: Special cases aren’t special enough to break the rules.

Liskov's Substituitablity Principle was the first of the SOLID design principles I learned of and the only one I learned at University. Maybe that's why this one is so intuitive to me. A plain English way of saying this is, "Any child class can replace its parent class without breaking functionality."

You may have noticed all of the FTP client classes so far have the same function signatures. That was done purposefully so they would follow Liskov's Substituitability Principle. An SFTPClient object can replace an FTPClient object and whatever code is calling upload, or download, is blissfully unaware.

Another specialized case of FTP file transfers is supporting FTPS (yes FTPS and SFTP are different). Solving this can be tricky because we have choices. They are:
1. Add upload_secure, and download_secure functions.
2. Add a secure flag through **kwargs.
3. Create a new class, FTPSClient, that extends FTPClient.

For reasons that we will get into during the Interface Segregation, and Dependency Inversion principles the new FTPSClient class is the way to go.

class FTPClient:
  def __init__(self, host, port):
    ...

  def upload(self, file:bytes):
    ...

  def download(self, target:str) -> bytes:
    ...

class FTPSClient(FTPClient):
    def __init__(self, host, port, username, password):
        self._client = FTPSDriver(host, port, user=username, password=password)

This is exactly the kind of edge case inheritance is meant for and following Liskov's makes for effective polymorphism. You'll note than now FTPClient's can be replaced by an FTPSClient or SFTPClient. In fact, all 3 are interchangeable which brings us to interface segregation.
Interface Segregation Principle (ISP)

Definition: A client should not depend on methods it does not use.

Relevant Zen: Readability Counts && complicated is better than complex.

Unlike Liskov's, The Interface Segregation Principle was the last and most difficult principle for me to understand. I always equated it to the interface keyword, and most explanations for SOLID design don't do much to dispel that confusion. additionally, most guides I've found try to break everything up into tiny interfaces most often with a single function per-interface because "too many interfaces are better than too few".

There are 2 issues here, first Python doesn't have interfaces, and second languages like C# and Java that do have interfaces, breaking them up too much always ends up with interfaces implementing interfaces which can get complex and complex is not Pythonic.

First I want to explore the too small of interfaces problem by looking at some C# code, then we'll cover a Pythonic approach to ISP. If you agree or are just choosing to trust me that super small interfaces are not the best way to segregate your interfaces feel free to skip to the Pythonic Solution below.

# Warning here be C# code
public interface ICanUpload {
  void upload(Byte[] file);
}

public interface ICanDownload {
  Byte[] download();
}

class FTPClient : ICanUpload, ICanDownload {
  public void upload(Byte[] file) {
    ...
  }

  public Byte[] download(string target) {
    ...
  }
}

The trouble starts when you need to specify the type of a parameter that implements both the ICanDownload and ICanUpload interfaces. The code snippet below demonstrates the problem.

class ReportGenerator {
  public Byte[] doStuff(Byte[] raw) {
    ...
  } 

  public void generateReport(/*What type should go here?*/ client) {
    raw_data = client.download('client_rundown.csv');
    report = this.doStuff(raw_data);
    client.upload(report);
  }
}

In the generateReport function signature you either have to specify the concrete FTPClient class as the parameter type, which violates the Dependency Inversion Principle or create an interface that implements both ICanUpload, and ICanDownload interfaces. Otherwise, an object that just implements ICanUpload could be passed in but would fail the download call and vice-versa with an object only implementing the ICanDownload interface. The normal answer is to create an IFTPClient interface and let the generateReport function depend on that.

public interface IFTPClient: ICanUpload, ICanDownload {
    void upload(Byte[] file);
    Byte[] download(string target);
}

That works, except we are still depending on FTP clients. What if we want to start storing our reports in S3?
The Pythonic Solution

To me, ISP is about making reasonable choices for how other developers will interface with your code. That's right it's more related to the I in API and CLI than it is the interface keyword. This is also where the "Readability Counts" from the Zen of Python is a driving force. A good interface will follow the semantics of the abstraction and match the terminology making the code more readable.

Let's look at how we can add an S3Client since it has the same upload/download semantics as the FTPClients. We want to keep the S3Clients signature for upload and download consistent, but it would be nonsense for the new S3Client to inherit from FTPClient. After all, S3 is not a special case of FTP. What FTP and S3 do have in common is that they are file transfer protocols and these protocols often share a similar interface as seen in this example. So instead of inheriting from FTPClient it would be better to tie these classes together with an abstract base class, the closest thing Python has to an interface.

We create a FileTransferClient which becomes our interface and all of our existing clients now inherit from that rather than inheriting from FTPClient. This forces a common interface and allows us to move bulk operations into their own interface since not every file transfer protocol will support them.

from abc import ABC
class FileTransferClient(ABC):
  def upload(self, file:bytes):
    pass

  def download(self, target:str) -> bytes:
    pass

  def cd(self, target_dir):
    pass


class BulkFileTransferClient(ABC):
  def upload_bulk(self, files:List[bytes]):
    pass

  def download_bulk(self, targets:List[str]):
    pass

What does this afford us though...well this.

class FTPClient(FileTransferClient, BulkFileTransferClient):
  ...

class FTPSClient(FileTransferClient, BulkFileTransferClient):
  ...

class SFTPClient(FileTransferClient, BulkFileTransferClient):
  ...

class S3Client(FileTransferClient):
  ...

class SCPClient(FileTransferClient):
  ...

Oh Man! is that good code or what. We even managed to squeeze in a SCPClient and kept bulk actions as their own mixin. All this ties together nicely with Dependency Injection, a technique used for the Dependency Inversion Principle.
Dependency Inversion Principle (DIP)

Definition: High-level modules should not depend on low-level modules. They should depend on abstractions and abstractions should not depend on details, rather details should depend on abstractions.

Relevant Zen: Explicit is Better than Implicit

This is what ties it all together. Everything we've done with the other SOLID principles was to get to a place where we are no longer dependent on a detail, the underlying file transfer protocol, being used to move files around. We can now write code around our business rules without tying them to a specific implementation. Our code satisfies both requirements of dependency inversion.

Our high-level modules no longer need to depend on a low-level module like FTPClient, SFTPClient, or S3Client, instead, they depend on an abstraction FileTransferClient. We are depending on the abstraction of moving files not the detail of how those files are moved.

Our abstraction FileTransferClient is not dependent on protocol specific details and instead, those details depend on how they will be used through the abstraction (i.e. that files can be uploaded or downloaded).

Here is a example of Dependency Inversion at work.

def exchange(client:FileTransferClient, to_upload:bytes, to_download:str) -> bytes:
    client.upload(to_upload)
    return client.download(to_download)

if __name__ == '__main__':
    ftp = FTPClient('ftp.host.com')
    sftp = FTPSClient('sftp.host.com', 22)
    ftps = SFTPClient('ftps.host.com', 990, 'ftps_user', 'P@ssw0rd1!')
    s3 = S3Client('ftp.host.com')
    scp = SCPClient('ftp.host.com')

    for client in [ftp, sftp, ftps, s3, scp]:
        exchange(client, b'Hello', 'greeting.txt')

Conclusion

There you have it a SOLID implementation that is also very Pythonic. I'm hoping you've at least warmed up to SOLID if you hadn't before, and for those of you that are learning Python and not sure how to continue writing SOLID code this has been helpful. This, of course, was a curated example that I knew would lend itself to my argument, but in writing this I was still surprised how much changed along the way. Not every problem will fit this exact breakdown, but I've tried to include enough reasoning behind
my decisions that you can choose the most SOLID & Pythonic implementation in the future.
***********************************************************************************************************************************************
					    			PREREQUISITES
***********************************************************************************************************************************************

PYCHARM IDE SLOW PROCESS SOLUTION

nano /etc/sysctl.conf
fs.inotify.max_user_watches = 524288



STATIC TYPING PYTHON

Install mypy 
 python3 -m pip install -U mypy'
 mypy example.py

-------
PYTHON
Install python dev    sudo apt-get install build-essential libssl-dev libffi-dev python3-dev
                      python3 -m pip install python-dev-tools --user --upgrade
		      sudo apt install python3-setuptools
		      
		      
Install pip3          sudo apt install python3-pip
                      python -m pip install --upgrade pip


-------
RUST
Install  Rust and Cargo   check online
$ curl https://sh.rustup.rs -sSf | sh
$ source $HOME/.cargo/env
$ export PATH="$HOME/.cargo/bin:$PATH"


***************************

gedit main.rs  - create and edit main.rs file

rustc main.rs  -  compile program

./main    -  run  program
------------
cargo new portfolio  - create "project folder" portfolio 

cd portfolio

cd src

gedit main.rs

cargo run

***************************

        ******DEVELOPMENT ENVIRONMENT******
	
Rustenv
Install _ONCE_            pip install rustenv
Create                    rustenv  renv
Activate                  ./renv/bin/activate
Deactivate                deactivate_rustenv
-------
VIRTUAL ENV  


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
OLD Python env

            _ONCE_ 1st)Install   sudo apt-get install python3-venv 
                   2nd)Create    virtualenv -p /usr/bin/python3.7 venv
Activate env:      source venv/bin/activate 
Install pip/pip3 _ONCE_    curl https://bootstrap.pypa.io/get-pip.py | python
Installation of dep        pip3 install -r requirements.txt
                           pip3 install -r requirements.txt --upgrade
Deactivate                 deactivate
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
NEW Python env

Install pip3 _ONCE_    sudo apt install python3-pip

Install _ONCE_             pip3 install pipenv
*************************
$ which python3.7
*************************
Create                    pipenv --python /usr/bin/python3.7
Activate                  pipenv shell
Installation of dep       pipenv install -r requirements.txt
Upgrade dep               pipenv install -r requirements.txt --upgrade
Deactivate                deactivate
       


Effect changes:            python3 manage.py makemigrations
                           python3 manage.py migrate
                           python3 manage.py runserver
			   
			   
			   ********NOTE**********
			   
			  -> import cv2 error
			   pip install opencv-contrib-python
			   
			  -> import dlib error (fedora)
			   sudo dnf install python3-dlib
			   
			  -> import gi error(sound)
			   sudo apt-get install python3-gi
                           sudo apt-get install pkg-config libcairo2-dev gcc python3-dev libgirepository1.0-dev
			  
 			   cd /usr/lib/python3/dist-packages/gi
			   sudo ln -s _.cpython-{36m,37m}-x86_64-linux-gnu.so
			   
			   pip install gobject PyGObject -> run pycharm to create sound when drowsy
                           pip uninstall gobject PyGObject -> open kivy window then redo step one
--------------------------------------------------------------------------
KIVY

buildozer init

######Edit spec file########
# (str) Title of your application
title = Driver-Drowsiness-Detection
# (str) Package name
package.name = Driver-Drowsiness-Detection package
# (str) Package domain (needed for android/ios packaging)
package.domain = org.dancun
# (list) Source files to include (let empty to include all the files)
source.include_exts = py,png,jpg,kv,atlas
# comma separated e.g. requirements = sqlite3,kivy
requirements = python3,kivy,kivymd,cv2,dlib,playsound,scipy,imutils,pygame
# (str) Android logcat filters to use
android.logcat_filters = *:S python:D

buildozer android deploy run

--------------------------------------------------------------------------
 DOCKER
 
 INITIAL DOCKER SETUP
 sudo dnf remove docker-*
 sudo dnf config-manager --disable docker-*
 sudo grubby --update-kernel=ALL --args="systemd.unified_cgroup_hierarchy=0"sudo firewall-cmd --permanent --zone=trusted --  add-interface=docker0
 sudo firewall-cmd --permanent --zone=FedoraWorkstation --add-masquerade
 sudo dnf install moby-engine docker-compose
 sudo systemctl enable docker
 
 
 KUBERNETES
 @@@@@@@@@@@@@@@@@@
kubectl, the command line tool for interacting with Kubernetes

minikube, a Kubernetes cluster manager, for small development and testing clusters

A single-node Kubernetes cluster, running in a VM.

The Kubernetes Dashboard and a simple Pod, to test out the cluster
@@@@@@@@@@@@@@@@@@@
 
 INITIAL KUBERNETES SETUP
 curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-latest.x86_64.rpm
 sudo rpm -ivh minikube-latest.x86_64.rpm
 sudo dnf install @virtualization
 sudo systemctl start libvirtd
 sudo systemctl enable libvirtd
 sudo usermod --append --groups libvirt $(whoami)
 minikube start
 minikube kubectl -- get pods
 alias kubectl="minikube kubectl --" 
 kubectl get nodes
 minikube dashboard    ****--> OPEN DASHBOARD****
  
 sudo dnf install snapd
 sudo ln -s /var/lib/snapd/snap /snap
 sudo snap install kubectl --classic




------------------
Personal github 4f41ea34f379e4e0dc151e6964c6468f4807e3c5
------------------
DEMONSTRATION

sudo apt install kazam

On how to use Kazam Screencaster https://www.youtube.com/watch?v=ADPPpY6ZEI8
------------------

GIT FIRST ATTEMPT

git config --global user.name "DancunManyinsa"
git config --global user.email "dancunmanyinsait@gmail.com"


HEROKU  ((( H - Conardmomanyi@1 ))) GITHUB  ->  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 


web: gunicorn waweru.wsgi --log-file -

*********************************************************************
sudo snap install --classic heroku

wget -qO- https://toolbelt.heroku.com/install-ubuntu.sh | sh


******CLONE FROM HEROKU*******
heroku git:clone -a mathematician/your_app_name


Collectstatic error while deploying Django app to Heroku

1 disable the collectstatic during a deploy

$ heroku config:set DISABLE_COLLECTSTATIC=1

2 deploy

$ git push heroku master

3 run migrations (django 1.10 added at least one)

$ heroku run python3 manage.py migrate

4 run collectstatic using bower

$ heroku run 'bower install --config.interactive=false;grunt prep;python3 manage.py collectstatic --noinput'

5 enable collecstatic for future deploys

$ heroku config:unset DISABLE_COLLECTSTATIC

6 try it on your own (optional)

$ heroku run python manage.py collectstatic


---------------------------------------------------------------------------------------------------------
Pyinstaller

pyinstaller --onedir --onefile --name=passwordlocker --windowed "/home/dan/PycharmProjects/dancunmanyinsa/manage.py"


---------------------------------------------------------------------------------------------------------
GIT COLLABORATION Link http://adzumi.co.ke/blog/github_contribution

As a new developer, contributing to a project can be scary. I get it,  I was there too. It took me way too long to make my first Pull Request.

Contributing is also a great way to learn more about social coding on Github, new technologies and their ecosystems and how to make constructive, helpful bug reports, feature requests and the noblest of all contributions.

STEP 1: SET UP A WORKING COPY ON YOUR COMPUTER
First of all, you need a local fork of the project, so go ahead and press the âforkâ button on GitHub. This will create a copy of the repository in your own GitHub account and youâll see a note that itâs been forked underneath the project name:



Now you need a copy locally, so find the clone URL in the right-hand column and use that to clone locally using a terminal:

$ git clone https://github.com/lawrence254/StudentEngagement.git
Which will do something like this:



Now navigate to the project's directory:

$ cd StudentEngagement
Finally, in this stage, you need to set up a new remote that points to the original project so that you can grab any changes and bring them into your local copy. Firstly click on the link to the original repository, itâs labeled âForked fromâ at the top of the GitHub page. This takes you back to the projects main GitHub page, so you can find the Clone URL and use it to create the new remote, which weâll call upstream.

$ git remote add upstream https://github.com/lawrence254/StudentEngagement.git
You now have two remotes for this project on disk:

origin which points to your GitHub fork of the project. You can read and write to this remote.
upstream which points to the main projectâs GitHub repository. You can only read from this remote.
STEP 2: MAKE SOME CHANGES
This is the fun bit where you get to contribute to the project. The number one rule is to put each piece of work on its own branch. If the project is using git-flow, then it will have both a master and a development branch. The general rule is that if you are adding a new feature then branch from development. If the project only has a master branch, the branch from that. 

For this example, the forked repository had a number of branches already, one of them called 'lawrence'. This is the branch the owner of the repository has been working on. Weâll assume weâre adding a feature in StudentEngagement, so we branch to that branch:

$ git checkout lawrence
$ git pull upstream lawrence && git push origin lawrence
Firstly we ensure weâre on the master branch. Then the git pull command will sync our local copy with the upstream project and the git push syncs it to our forked GitHub project. Finally, we checkout to the 'lawrence' branch. 

Now you can add a feature(Or fix a bug).

If the project has tests, run them to ensure you havenât broken anything. You may also add a new test to show that your change fixes the original problem.

STEP 3: CREATE A PULL REQUEST
To create a Pull Request you need to push your branch to the origin remote and then press some buttons on GitHub.

To push the new branch:

$ git push origin lawrence
Now swap back to the browser and navigate to your fork of the project (https://github.com/YomZsamora/StudentEngagement in my case) and youâll see that the branch is listed at the top with a handy âCompare & pull requestâ button:



Go ahead and press the button! 

On this page, ensure that the âbase forkâ points to the correct repository and branch. Then ensure that you provide a good, succinct title for your pull request and explain why you have created it in the description box. Add any relevant issue numbers if you have them.



If you scroll down a bit, youâll see a diff of your changes. Double check that it contains what you expect.

Once you are happy, press the âCreate pull requestâ button and youâre done.

For your work to be integrated into the project, the maintainers will review your work and either request changes or merge it.

To Summarize
Thatâs all there is to it. The fundamentals are:

Fork the project & clone locally.
Create an upstream remote and sync your local copy.
Ensure you're working on the correct branch.
Do the work, write good commit messages and read the CONTRIBUTING file if there is one.
Push to your origin repository.
Create a new Pull Request in GitHub.

------------------------------------------------------------------------------------------------------------


*********************************************************************
						AI COMPUTATION

*********************************************************************
++++++++++++++++++++++
WEKA DATA SCIENCE SOFTWARE
 cd weka-3-8-3/
 java -jar weka.jar
 

INSTALLING ANACONDA


cd /tmp
sudo apt install curl
curl -O https://repo.anaconda.com/archive/Anaconda3-2019.03-Linux-x86_64.sh
sha256sum Anaconda3-2019.03-Linux-x86_64.sh
bash Anaconda3-2019.03-Linux-x86_64.sh
conda list
conda update conda
conda update anaconda

+++++++++++++++++++++

cd anaconda3/
source $HOME/anaconda3/bin/activate
conda list
conda update conda

+++++++++++++++++++++
SET UP JUPYTER NOTEBOOK 
conda install -c anaconda ipykernel

INSTALL DEBUGGER
pip install nbdev conda install nbdev
conda install xeus-python -c conda-forge
Enable  -extension manager
        -debugger

+++++++++++++++++++++

 package cache : /home/dan/anaconda3/pkgs
                          /home/dan/.conda/pkgs
			  
			  
			  
       envs directories : /home/dan/anaconda3/envs
                          /home/dan/.conda/envs
			  
			  source $HOME/anaconda3/bin/activate
			  
			  conda create --name Daniel_projects
			  conda activate Daniel_projects
			  conda deactivate



++++++++++++++++++++++++


IMPORT FILES FROM DRIVE INTO GOOGLE-COLAB:

STEP-1: Import Libraries

# Code to read csv file into colaboratory:
!pip install -U -q PyDrive
from pydrive.auth import GoogleAuth
from pydrive.drive import GoogleDrive
from google.colab import auth
from oauth2client.client import GoogleCredentials

STEP-2: Autheticate E-Mail ID

auth.authenticate_user()
gauth = GoogleAuth()
gauth.credentials = GoogleCredentials.get_application_default()
drive = GoogleDrive(gauth)

STEP-3: Get File from Drive using file-ID

#2.1 Get the file
downloaded = drive.CreateFile({'id':'1R9vW5dmox7i8OGOoDql_r9yUrvAJgvhD'}) # replace the id with id of file you want to access
downloaded.GetContentFile('resources.csv') 

STEP-4: Read File

#3.1 Read file as panda dataframe
import pandas as pd
xyz = pd.read_csv('resources.csv') 
print(xyz.head(1))

#Repeat STEPs 3 & 4 to load as many files as you require.


++++++++++++++++++++++++



FEATURE ENGINEERING  https://towardsdatascience.com/feature-engineering-for-machine-learning-3a5e293a5114



List of Techniques
1.Imputation
2.Handling Outliers
3.Binning
4.Log Transform
5.One-Hot Encoding
6.Grouping Operations
7.Feature Split
8.Scaling
9.Extracting Date
1.Imputation
Image for post
Missing values are one of the most common problems you can encounter when you try to prepare your data for machine learning. The reason for the missing values might be human errors, interruptions in the data flow, privacy concerns, and so on. Whatever is the reason, missing values affect the performance of the machine learning models.
Some machine learning platforms automatically drop the rows which include missing values in the model training phase and it decreases the model performance because of the reduced training size. On the other hand, most of the algorithms do not accept datasets with missing values and gives an error.
The most simple solution to the missing values is to drop the rows or the entire column. There is not an optimum threshold for dropping but you can use 70% as an example value and try to drop the rows and columns which have missing values with higher than this threshold.
threshold = 0.7
#Dropping columns with missing value rate higher than threshold
data = data[data.columns[data.isnull().mean() < threshold]]

#Dropping rows with missing value rate higher than threshold
data = data.loc[data.isnull().mean(axis=1) < threshold]
Numerical Imputation
Imputation is a more preferable option rather than dropping because it preserves the data size. However, there is an important selection of what you impute to the missing values. I suggest beginning with considering a possible default value of missing values in the column. For example, if you have a column that only has 1 and NA, then it is likely that the NA rows correspond to 0. For another example, if you have a column that shows the “customer visit count in last month”, the missing values might be replaced with 0 as long as you think it is a sensible solution.
Another reason for the missing values is joining tables with different sizes and in this case, imputing 0 might be reasonable as well.
Except for the case of having a default value for missing values, I think the best imputation way is to use the medians of the columns. As the averages of the columns are sensitive to the outlier values, while medians are more solid in this respect.
#Filling all missing values with 0
data = data.fillna(0)
#Filling missing values with medians of the columns
data = data.fillna(data.median())
Categorical Imputation
Replacing the missing values with the maximum occurred value in a column is a good option for handling categorical columns. But if you think the values in the column are distributed uniformly and there is not a dominant value, imputing a category like “Other” might be more sensible, because in such a case, your imputation is likely to converge a random selection.
#Max fill function for categorical columns
data['column_name'].fillna(data['column_name'].value_counts()
.idxmax(), inplace=True)
2.Handling Outliers
Before mentioning how outliers can be handled, I want to state that the best way to detect the outliers is to demonstrate the data visually. All other statistical methodologies are open to making mistakes, whereas visualizing the outliers gives a chance to take a decision with high precision. Anyway, I am planning to focus visualization deeply in another article and let’s continue with statistical methodologies.
Statistical methodologies are less precise as I mentioned, but on the other hand, they have a superiority, they are fast. Here I will list two different ways of handling outliers. These will detect them using standard deviation, and percentiles.
Outlier Detection with Standard Deviation
If a value has a distance to the average higher than x * standard deviation, it can be assumed as an outlier. Then what x should be?
There is no trivial solution for x, but usually, a value between 2 and 4 seems practical.
#Dropping the outlier rows with standard deviation
factor = 3
upper_lim = data['column'].mean () + data['column'].std () * factor
lower_lim = data['column'].mean () - data['column'].std () * factor

data = data[(data['column'] < upper_lim) & (data['column'] > lower_lim)]
In addition, z-score can be used instead of the formula above. Z-score (or standard score) standardizes the distance between a value and the mean using the standard deviation.
Outlier Detection with Percentiles
Another mathematical method to detect outliers is to use percentiles. You can assume a certain percent of the value from the top or the bottom as an outlier. The key point is here to set the percentage value once again, and this depends on the distribution of your data as mentioned earlier.
Additionally, a common mistake is using the percentiles according to the range of the data. In other words, if your data ranges from 0 to 100, your top 5% is not the values between 96 and 100. Top 5% means here the values that are out of the 95th percentile of data.
#Dropping the outlier rows with Percentiles
upper_lim = data['column'].quantile(.95)
lower_lim = data['column'].quantile(.05)

data = data[(data['column'] < upper_lim) & (data['column'] > lower_lim)]
An Outlier Dilemma: Drop or Cap
Another option for handling outliers is to cap them instead of dropping. So you can keep your data size and at the end of the day, it might be better for the final model performance.
On the other hand, capping can affect the distribution of the data, thus it better not to exaggerate it.
#Capping the outlier rows with Percentiles
upper_lim = data['column'].quantile(.95)
lower_lim = data['column'].quantile(.05)
data.loc[(df[column] > upper_lim),column] = upper_lim
data.loc[(df[column] < lower_lim),column] = lower_lim
3.Binning
Image for post
Binning illustration of numerical data
Binning can be applied on both categorical and numerical data:
#Numerical Binning Example
Value      Bin       
0-30   ->  Low       
31-70  ->  Mid       
71-100 ->  High
#Categorical Binning Example
Value      Bin       
Spain  ->  Europe      
Italy  ->  Europe       
Chile  ->  South America
Brazil ->  South America
The main motivation of binning is to make the model more robust and prevent overfitting, however, it has a cost to the performance. Every time you bin something, you sacrifice information and make your data more regularized. (Please see regularization in machine learning)
The trade-off between performance and overfitting is the key point of the binning process. In my opinion, for numerical columns, except for some obvious overfitting cases, binning might be redundant for some kind of algorithms, due to its effect on model performance.
However, for categorical columns, the labels with low frequencies probably affect the robustness of statistical models negatively. Thus, assigning a general category to these less frequent values helps to keep the robustness of the model. For example, if your data size is 100,000 rows, it might be a good option to unite the labels with a count less than 100 to a new category like “Other”.
#Numerical Binning Example
data['bin'] = pd.cut(data['value'], bins=[0,30,70,100], labels=["Low", "Mid", "High"])
   value   bin
0      2   Low
1     45   Mid
2      7   Low
3     85  High
4     28   Low
#Categorical Binning Example
     Country
0      Spain
1      Chile
2  Australia
3      Italy
4     Brazil
conditions = [
    data['Country'].str.contains('Spain'),
    data['Country'].str.contains('Italy'),
    data['Country'].str.contains('Chile'),
    data['Country'].str.contains('Brazil')]

choices = ['Europe', 'Europe', 'South America', 'South America']

data['Continent'] = np.select(conditions, choices, default='Other')
     Country      Continent
0      Spain         Europe
1      Chile  South America
2  Australia          Other
3      Italy         Europe
4     Brazil  South America
4.Log Transform
Logarithm transformation (or log transform) is one of the most commonly used mathematical transformations in feature engineering. What are the benefits of log transform:
It helps to handle skewed data and after transformation, the distribution becomes more approximate to normal.
In most of the cases the magnitude order of the data changes within the range of the data. For instance, the difference between ages 15 and 20 is not equal to the ages 65 and 70. In terms of years, yes, they are identical, but for all other aspects, 5 years of difference in young ages mean a higher magnitude difference. This type of data comes from a multiplicative process and log transform normalizes the magnitude differences like that.
It also decreases the effect of the outliers, due to the normalization of magnitude differences and the model become more robust.
A critical note: The data you apply log transform must have only positive values, otherwise you receive an error. Also, you can add 1 to your data before transform it. Thus, you ensure the output of the transformation to be positive.
Log(x+1)
#Log Transform Example
data = pd.DataFrame({'value':[2,45, -23, 85, 28, 2, 35, -12]})
data['log+1'] = (data['value']+1).transform(np.log)
#Negative Values Handling
#Note that the values are different
data['log'] = (data['value']-data['value'].min()+1) .transform(np.log)
   value  log(x+1)  log(x-min(x)+1)
0      2   1.09861          3.25810
1     45   3.82864          4.23411
2    -23       nan          0.00000
3     85   4.45435          4.69135
4     28   3.36730          3.95124
5      2   1.09861          3.25810
6     35   3.58352          4.07754
7    -12       nan          2.48491
5.One-hot encoding
One-hot encoding is one of the most common encoding methods in machine learning. This method spreads the values in a column to multiple flag columns and assigns 0 or 1 to them. These binary values express the relationship between grouped and encoded column.
This method changes your categorical data, which is challenging to understand for algorithms, to a numerical format and enables you to group your categorical data without losing any information. (For details please see the last part of Categorical Column Grouping)
Image for post
One hot encoding example on City column
Why One-Hot?: If you have N distinct values in the column, it is enough to map them to N-1 binary columns, because the missing value can be deducted from other columns. If all the columns in our hand are equal to 0, the missing value must be equal to 1. This is the reason why it is called as one-hot encoding. However, I will give an example using the get_dummies function of Pandas. This function maps all values in a column to multiple columns.
encoded_columns = pd.get_dummies(data['column'])
data = data.join(encoded_columns).drop('column', axis=1)
6.Grouping Operations
In most machine learning algorithms, every instance is represented by a row in the training dataset, where every column show a different feature of the instance. This kind of data called “Tidy”.
Tidy datasets are easy to manipulate, model and visualise, and have a specific structure: each variable is a column, each observation is a row, and each type of observational unit is a table.
— Hadley Wickham
Datasets such as transactions rarely fit the definition of tidy data above, because of the multiple rows of an instance. In such a case, we group the data by the instances and then every instance is represented by only one row.
The key point of group by operations is to decide the aggregation functions of the features. For numerical features, average and sum functions are usually convenient options, whereas for categorical features it more complicated.
Categorical Column Grouping
I suggest three different ways for aggregating categorical columns:
The first option is to select the label with the highest frequency. In other words, this is the max operation for categorical columns, but ordinary max functions generally do not return this value, you need to use a lambda function for this purpose.
data.groupby('id').agg(lambda x: x.value_counts().index[0])
Second option is to make a pivot table. This approach resembles the encoding method in the preceding step with a difference. Instead of binary notation, it can be defined as aggregated functions for the values between grouped and encoded columns. This would be a good option if you aim to go beyond binary flag columns and merge multiple features into aggregated features, which are more informative.
Image for post
Pivot table example: Sum of Visit Days grouped by Users
#Pivot table Pandas Example
data.pivot_table(index='column_to_group', columns='column_to_encode', values='aggregation_column', aggfunc=np.sum, fill_value = 0)
Last categorical grouping option is to apply a group by function after applying one-hot encoding. This method preserves all the data -in the first option you lose some-, and in addition, you transform the encoded column from categorical to numerical in the meantime. You can check the next section for the explanation of numerical column grouping.
Numerical Column Grouping
Numerical columns are grouped using sum and mean functions in most of the cases. Both can be preferable according to the meaning of the feature. For example, if you want to obtain ratio columns, you can use the average of binary columns. In the same example, sum function can be used to obtain the total count either.
#sum_cols: List of columns to sum
#mean_cols: List of columns to average
grouped = data.groupby('column_to_group')

sums = grouped[sum_cols].sum().add_suffix('_sum')
avgs = grouped[mean_cols].mean().add_suffix('_avg')

new_df = pd.concat([sums, avgs], axis=1)
7.Feature Split
Image for postImage for post
Photo by Jaxon Lott on Unsplash
Splitting features is a good way to make them useful in terms of machine learning. Most of the time the dataset contains string columns that violates tidy data principles. By extracting the utilizable parts of a column into new features:
We enable machine learning algorithms to comprehend them.
Make possible to bin and group them.
Improve model performance by uncovering potential information.
Split function is a good option, however, there is no one way of splitting features. It depends on the characteristics of the column, how to split it. Let’s introduce it with two examples. First, a simple split function for an ordinary name column:
data.name
0  Luther N. Gonzalez
1    Charles M. Young
2        Terry Lawson
3       Kristen White
4      Thomas Logsdon
#Extracting first names
data.name.str.split(" ").map(lambda x: x[0])
0     Luther
1    Charles
2      Terry
3    Kristen
4     Thomas
#Extracting last names
data.name.str.split(" ").map(lambda x: x[-1])
0    Gonzalez
1       Young
2      Lawson
3       White
4     Logsdon
The example above handles the names longer than two words by taking only the first and last elements and it makes the function robust for corner cases, which should be regarded when manipulating strings like that.
Another case for split function is to extract a string part between two chars. The following example shows an implementation of this case by using two split functions in a row.
#String extraction example
data.title.head()
0                      Toy Story (1995)
1                        Jumanji (1995)
2               Grumpier Old Men (1995)
3              Waiting to Exhale (1995)
4    Father of the Bride Part II (1995)
data.title.str.split("(", n=1, expand=True)[1].str.split(")", n=1, expand=True)[0]
0    1995
1    1995
2    1995
3    1995
4    1995
8.Scaling
In most cases, the numerical features of the dataset do not have a certain range and they differ from each other. In real life, it is nonsense to expect age and income columns to have the same range. But from the machine learning point of view, how these two columns can be compared?
Scaling solves this problem. The continuous features become identical in terms of the range, after a scaling process. This process is not mandatory for many algorithms, but it might be still nice to apply. However, the algorithms based on distance calculations such as k-NN or k-Means need to have scaled continuous features as model input.
Basically, there are two common ways of scaling:
Normalization
Image for post
Normalization (or min-max normalization) scale all values in a fixed range between 0 and 1. This transformation does not change the distribution of the feature and due to the decreased standard deviations, the effects of the outliers increases. Therefore, before normalization, it is recommended to handle the outliers.
data = pd.DataFrame({'value':[2,45, -23, 85, 28, 2, 35, -12]})

data['normalized'] = (data['value'] - data['value'].min()) / (data['value'].max() - data['value'].min())
   value  normalized
0      2        0.23
1     45        0.63
2    -23        0.00
3     85        1.00
4     28        0.47
5      2        0.23
6     35        0.54
7    -12        0.10
Standardization
Standardization (or z-score normalization) scales the values while taking into account standard deviation. If the standard deviation of features is different, their range also would differ from each other. This reduces the effect of the outliers in the features.
In the following formula of standardization, the mean is shown as μ and the standard deviation is shown as σ.
Image for post
data = pd.DataFrame({'value':[2,45, -23, 85, 28, 2, 35, -12]})

data['standardized'] = (data['value'] - data['value'].mean()) / data['value'].std()
   value  standardized
0      2         -0.52
1     45          0.70
2    -23         -1.23
3     85          1.84
4     28          0.22
5      2         -0.52
6     35          0.42
7    -12         -0.92
9.Extracting Date
Though date columns usually provide valuable information about the model target, they are neglected as an input or used nonsensically for the machine learning algorithms. It might be the reason for this, that dates can be present in numerous formats, which make it hard to understand by algorithms, even they are simplified to a format like "01–01–2017".
Building an ordinal relationship between the values is very challenging for a machine learning algorithm if you leave the date columns without manipulation. Here, I suggest three types of preprocessing for dates:
Extracting the parts of the date into different columns: Year, month, day, etc.
Extracting the time period between the current date and columns in terms of years, months, days, etc.
Extracting some specific features from the date: Name of the weekday, Weekend or not, holiday or not, etc.
If you transform the date column into the extracted columns like above, the information of them become disclosed and machine learning algorithms can easily understand them.
from datetime import date

data = pd.DataFrame({'date':
['01-01-2017',
'04-12-2008',
'23-06-1988',
'25-08-1999',
'20-02-1993',
]})

#Transform string to date
data['date'] = pd.to_datetime(data.date, format="%d-%m-%Y")

#Extracting Year
data['year'] = data['date'].dt.year

#Extracting Month
data['month'] = data['date'].dt.month

#Extracting passed years since the date
data['passed_years'] = date.today().year - data['date'].dt.year

#Extracting passed months since the date
data['passed_months'] = (date.today().year - data['date'].dt.year) * 12 + date.today().month - data['date'].dt.month

#Extracting the weekday name of the date
data['day_name'] = data['date'].dt.day_name()
        date  year  month  passed_years  passed_months   day_name
0 2017-01-01  2017      1             2             26     Sunday
1 2008-12-04  2008     12            11            123   Thursday
2 1988-06-23  1988      6            31            369   Thursday
3 1999-08-25  1999      8            20            235  Wednesday
4 1993-02-20  1993      2            26            313   Saturday
Conclusion
Image for post
============================================================================================
Stock Price Prediction – Machine Learning Project in Python

Stock Price Machine learning has significant applications in the stock price prediction. In this machine learning project, we will be talking about predicting the returns on stocks. This is a very complex task and has uncertainties. We will develop this project into two parts:

First, we will learn how to predict stock price using the LSTM neural network.
Then we will build a dashboard using Plotly dash for stock analysis.


https://data-flair.training/blogs/stock-price-prediction-machine-learning-project-in-python/
Stock Price Prediction Project
Datasets
To build the stock price prediction model, we will use the NSE TATA GLOBAL dataset. This is a dataset of Tata Beverages from Tata Global Beverages Limited, National Stock Exchange of India: Tata Global Dataset
To develop the dashboard for stock analysis we will use another stock dataset with multiple stocks like Apple, Microsoft, Facebook: Stocks Dataset
Source Code
Before proceeding ahead, please download the source code: Stock Price Prediction Project

Stock price prediction using LSTM step by step explanation

1. Imports:

import pandas as pd
import numpy as np

import matplotlib.pyplot as plt
%matplotlib inline

from matplotlib.pylab import rcParams
rcParams['figure.figsize']=20,10
from keras.models import Sequential
from keras.layers import LSTM,Dropout,Dense


from sklearn.preprocessing import MinMaxScaler


2. Read the dataset:

df=pd.read_csv("NSE-TATA.csv")
df.head()


3. Analyze the closing prices from dataframe:

df["Date"]=pd.to_datetime(df.Date,format="%Y-%m-%d")
df.index=df['Date']

plt.figure(figsize=(16,8))
plt.plot(df["Close"],label='Close Price history')


4. Sort the dataset on date time and filter “Date” and “Close” columns:

data=df.sort_index(ascending=True,axis=0)
new_dataset=pd.DataFrame(index=range(0,len(df)),columns=['Date','Close'])

for i in range(0,len(data)):
    new_dataset["Date"][i]=data['Date'][i]
    new_dataset["Close"][i]=data["Close"][i]


5. Normalize the new filtered dataset:

scaler=MinMaxScaler(feature_range=(0,1))
final_dataset=new_dataset.values

train_data=final_dataset[0:987,:]
valid_data=final_dataset[987:,:]

new_dataset.index=new_dataset.Date
new_dataset.drop("Date",axis=1,inplace=True)
scaler=MinMaxScaler(feature_range=(0,1))
scaled_data=scaler.fit_transform(final_dataset)

x_train_data,y_train_data=[],[]

for i in range(60,len(train_data)):
    x_train_data.append(scaled_data[i-60:i,0])
    y_train_data.append(scaled_data[i,0])
    
x_train_data,y_train_data=np.array(x_train_data),np.array(y_train_data)

x_train_data=np.reshape(x_train_data,(x_train_data.shape[0],x_train_data.shape[1],1))


6. Build and train the LSTM model:

lstm_model=Sequential()
lstm_model.add(LSTM(units=50,return_sequences=True,input_shape=(x_train_data.shape[1],1)))
lstm_model.add(LSTM(units=50))
lstm_model.add(Dense(1))

inputs_data=new_dataset[len(new_dataset)-len(valid_data)-60:].values
inputs_data=inputs_data.reshape(-1,1)
inputs_data=scaler.transform(inputs_data)

lstm_model.compile(loss='mean_squared_error',optimizer='adam')
lstm_model.fit(x_train_data,y_train_data,epochs=1,batch_size=1,verbose=2)


7. Take a sample of a dataset to make stock price predictions using the LSTM model:

X_test=[]
for i in range(60,inputs_data.shape[0]):
    X_test.append(inputs_data[i-60:i,0])
X_test=np.array(X_test)

X_test=np.reshape(X_test,(X_test.shape[0],X_test.shape[1],1))
predicted_closing_price=lstm_model.predict(X_test)
predicted_closing_price=scaler.inverse_transform(predicted_closing_price)


8. Save the LSTM model:

lstm_model.save("saved_model.h5")


9. Visualize the predicted stock costs with actual stock costs:

train_data=new_dataset[:987]
valid_data=new_dataset[987:]
valid_data['Predictions']=predicted_closing_price
plt.plot(train_data["Close"])
plt.plot(valid_data[['Close',"Predictions"]])


You can observe that LSTM has predicted stocks almost similar to actual stocks.

Build the dashboard using Plotly dash
In this section, we will build a dashboard to analyze stocks. Dash is a python framework that provides an abstraction over flask and react.js to build analytical web applications.
Before moving ahead, you need to install dash. Run the below command in the terminal.

pip3 install dash
pip3 install dash-html-components
pip3 install dash-core-components


Now make a new python file stock_app.py and paste the below script:

import dash
import dash_core_components as dcc
import dash_html_components as html
import pandas as pd
import plotly.graph_objs as go
from dash.dependencies import Input, Output
from keras.models import load_model
from sklearn.preprocessing import MinMaxScaler
import numpy as np


app = dash.Dash()
server = app.server

scaler=MinMaxScaler(feature_range=(0,1))

df_nse = pd.read_csv("./NSE-TATA.csv")

df_nse["Date"]=pd.to_datetime(df_nse.Date,format="%Y-%m-%d")
df_nse.index=df_nse['Date']


data=df_nse.sort_index(ascending=True,axis=0)
new_data=pd.DataFrame(index=range(0,len(df_nse)),columns=['Date','Close'])

for i in range(0,len(data)):
    new_data["Date"][i]=data['Date'][i]
    new_data["Close"][i]=data["Close"][i]

new_data.index=new_data.Date
new_data.drop("Date",axis=1,inplace=True)

dataset=new_data.values

train=dataset[0:987,:]
valid=dataset[987:,:]

scaler=MinMaxScaler(feature_range=(0,1))
scaled_data=scaler.fit_transform(dataset)

x_train,y_train=[],[]

for i in range(60,len(train)):
    x_train.append(scaled_data[i-60:i,0])
    y_train.append(scaled_data[i,0])
    
x_train,y_train=np.array(x_train),np.array(y_train)

x_train=np.reshape(x_train,(x_train.shape[0],x_train.shape[1],1))

model=load_model("saved_model.h5")

inputs=new_data[len(new_data)-len(valid)-60:].values
inputs=inputs.reshape(-1,1)
inputs=scaler.transform(inputs)

X_test=[]
for i in range(60,inputs.shape[0]):
    X_test.append(inputs[i-60:i,0])
X_test=np.array(X_test)

X_test=np.reshape(X_test,(X_test.shape[0],X_test.shape[1],1))
closing_price=model.predict(X_test)
closing_price=scaler.inverse_transform(closing_price)

train=new_data[:987]
valid=new_data[987:]
valid['Predictions']=closing_price



df= pd.read_csv("./stock_data.csv")

app.layout = html.Div([
   
    html.H1("Stock Price Analysis Dashboard", style={"textAlign": "center"}),
   
    dcc.Tabs(id="tabs", children=[
       
        dcc.Tab(label='NSE-TATAGLOBAL Stock Data',children=[
            html.Div([
                html.H2("Actual closing price",style={"textAlign": "center"}),
                dcc.Graph(
                    id="Actual Data",
                    figure={
                        "data":[
                            go.Scatter(
                                x=train.index,
                                y=valid["Close"],
                                mode='markers'
                            )

                        ],
                        "layout":go.Layout(
                            title='scatter plot',
                            xaxis={'title':'Date'},
                            yaxis={'title':'Closing Rate'}
                        )
                    }

                ),
                html.H2("LSTM Predicted closing price",style={"textAlign": "center"}),
                dcc.Graph(
                    id="Predicted Data",
                    figure={
                        "data":[
                            go.Scatter(
                                x=valid.index,
                                y=valid["Predictions"],
                                mode='markers'
                            )

                        ],
                        "layout":go.Layout(
                            title='scatter plot',
                            xaxis={'title':'Date'},
                            yaxis={'title':'Closing Rate'}
                        )
                    }

                )                
            ])                


        ]),
        dcc.Tab(label='Facebook Stock Data', children=[
            html.Div([
                html.H1("Facebook Stocks High vs Lows", 
                        style={'textAlign': 'center'}),
              
                dcc.Dropdown(id='my-dropdown',
                             options=[{'label': 'Tesla', 'value': 'TSLA'},
                                      {'label': 'Apple','value': 'AAPL'}, 
                                      {'label': 'Facebook', 'value': 'FB'}, 
                                      {'label': 'Microsoft','value': 'MSFT'}], 
                             multi=True,value=['FB'],
                             style={"display": "block", "margin-left": "auto", 
                                    "margin-right": "auto", "width": "60%"}),
                dcc.Graph(id='highlow'),
                html.H1("Facebook Market Volume", style={'textAlign': 'center'}),
         
                dcc.Dropdown(id='my-dropdown2',
                             options=[{'label': 'Tesla', 'value': 'TSLA'},
                                      {'label': 'Apple','value': 'AAPL'}, 
                                      {'label': 'Facebook', 'value': 'FB'},
                                      {'label': 'Microsoft','value': 'MSFT'}], 
                             multi=True,value=['FB'],
                             style={"display": "block", "margin-left": "auto", 
                                    "margin-right": "auto", "width": "60%"}),
                dcc.Graph(id='volume')
            ], className="container"),
        ])


    ])
])


@app.callback(Output('highlow', 'figure'),
              [Input('my-dropdown', 'value')])
def update_graph(selected_dropdown):
    dropdown = {"TSLA": "Tesla","AAPL": "Apple","FB": "Facebook","MSFT": "Microsoft",}
    trace1 = []
    trace2 = []
    for stock in selected_dropdown:
        trace1.append(
          go.Scatter(x=df[df["Stock"] == stock]["Date"],
                     y=df[df["Stock"] == stock]["High"],
                     mode='lines', opacity=0.7, 
                     name=f'High {dropdown[stock]}',textposition='bottom center'))
        trace2.append(
          go.Scatter(x=df[df["Stock"] == stock]["Date"],
                     y=df[df["Stock"] == stock]["Low"],
                     mode='lines', opacity=0.6,
                     name=f'Low {dropdown[stock]}',textposition='bottom center'))
    traces = [trace1, trace2]
    data = [val for sublist in traces for val in sublist]
    figure = {'data': data,
              'layout': go.Layout(colorway=["#5E0DAC", '#FF4F00', '#375CB1', 
                                            '#FF7400', '#FFF400', '#FF0056'],
            height=600,
            title=f"High and Low Prices for {', '.join(str(dropdown[i]) for i in selected_dropdown)} Over Time",
            xaxis={"title":"Date",
                   'rangeselector': {'buttons': list([{'count': 1, 'label': '1M', 
                                                       'step': 'month', 
                                                       'stepmode': 'backward'},
                                                      {'count': 6, 'label': '6M', 
                                                       'step': 'month', 
                                                       'stepmode': 'backward'},
                                                      {'step': 'all'}])},
                   'rangeslider': {'visible': True}, 'type': 'date'},
             yaxis={"title":"Price (USD)"})}
    return figure


@app.callback(Output('volume', 'figure'),
              [Input('my-dropdown2', 'value')])
def update_graph(selected_dropdown_value):
    dropdown = {"TSLA": "Tesla","AAPL": "Apple","FB": "Facebook","MSFT": "Microsoft",}
    trace1 = []
    for stock in selected_dropdown_value:
        trace1.append(
          go.Scatter(x=df[df["Stock"] == stock]["Date"],
                     y=df[df["Stock"] == stock]["Volume"],
                     mode='lines', opacity=0.7,
                     name=f'Volume {dropdown[stock]}', textposition='bottom center'))
    traces = [trace1]
    data = [val for sublist in traces for val in sublist]
    figure = {'data': data, 
              'layout': go.Layout(colorway=["#5E0DAC", '#FF4F00', '#375CB1', 
                                            '#FF7400', '#FFF400', '#FF0056'],
            height=600,
            title=f"Market Volume for {', '.join(str(dropdown[i]) for i in selected_dropdown_value)} Over Time",
            xaxis={"title":"Date",
                   'rangeselector': {'buttons': list([{'count': 1, 'label': '1M', 
                                                       'step': 'month', 
                                                       'stepmode': 'backward'},
                                                      {'count': 6, 'label': '6M',
                                                       'step': 'month', 
                                                       'stepmode': 'backward'},
                                                      {'step': 'all'}])},
                   'rangeslider': {'visible': True}, 'type': 'date'},
             yaxis={"title":"Transactions Volume"})}
    return figure


if __name__=='__main__':
    app.run_server(debug=True)


Now run this file and open the app in the browser:

python3 stock_app.py

Summary
Stock price prediction is a machine learning project for beginners; in this tutorial we learned how to develop a stock cost prediction model and how to build an interactive dashboard for stock analysis. We implemented stock market prediction using the LSTM model. OTOH, Plotly dash python framework for building dashboards.

*********************************************************************
						DIGITAL COMPUTATION

*********************************************************************



DJANGO
‐-------------------
$django-admin startproject travel_project
(NOT SURE)$django-admin startapp travel_app 
(NOT SURE)$django startproject travel_project (wsgi, setting)
$ python3 manage.py startapp travel_app  (view, models, templates)

---------------------
$ python3 manage.py createsuperuser 
---------------------

$pip3 install pillow #image library
$pip3 install psycopg2 #connector to db

Include this in settings.py
#app definition
INSTALLED APP=[
'travel.apps.Travel.config',
]

Adding image in models.py
class Destination(models.Model):
img=models.ImageField(upload_to='pics')


@@@@@@@@@
Making random migrations
$ python3 manage.py makemigrations
$ python3 manage.py migrate

Making specific migrations
$ python3 manage.py makemigrations
$ python3 manage.py migrate name_ data 0001_initial
@@@@@@@@@





django-admin startproject heyapp (wsgi, setting)
django-admin startproject heyapp . (view, models, templates)
 


DJANGO && SERVICE WORKER
from django.views.generic import TemplateView

urlpatterns = [
  url(r'^sw.js', (TemplateView.as_view(template_name="sw.js", content_type='application/javascript', )), name='sw.js'),
]


DJANGO && MONGODB CONNECTION

1)django_mongodb_engine
2)djongo -> transpiler you write sql queries and it transpiles to mongo nosql queries

1)django_mongodb_engine ->check https://django-mongodb-engine.readthedocs.io/en/latest/topics/setup.html
Django-nonrel, a fork of Django that adds support for non-relational databases
Djangotoolbox, a bunch of utilities for non-relational Django applications and backends
Django-nonrel
pip install git+https://github.com/django-nonrel/django@nonrel-1.5
Djangotoolbox
pip install git+https://github.com/django-nonrel/djangotoolbox
Django MongoDB Engine
You should use the latest Git revision.

pip install git+https://github.com/django-nonrel/mongodb-engine
Configuration
Database setup is easy (see also the Django database setup docs):

DATABASES = {
   'default' : {
      'ENGINE' : 'django_mongodb_engine',
      'NAME' : 'my_database'
   }
}
Django MongoDB Engine also takes into account the HOST, PORT, USER, PASSWORD and OPTIONS settings.

Possible values of OPTIONS are described in the settings reference.



2)djongo ->check https://pypi.org/project/djongo/
Install djongo:

pip install djongo
Into settings.py file of your project, add:

DATABASES = {
     'default': {
         'ENGINE': 'djongo',
         'NAME': 'your-db-name',
     }
 }
Run (ONLY the first time to create collections in mongoDB):

manage.py makemigrations
manage.py migrate
YOUR ARE SET! HAVE FUN!

Requirements
Djongo requires python 3.6 or above.
How it works
Djongo is a SQL to mongodb query transpiler. It translates a SQL query string into a mongoDB query document. As a result, all Django features, models etc work as is.

Django contrib modules:

'django.contrib.admin',
'django.contrib.auth',
'django.contrib.sessions',
and othersâŠ fully supported.

Important links
Full Documentation
Source code


DJANGO && POGRESQL CONNECTION 
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'portfolio',
        'USER':'dan',
        'PASSWORD':'phoenix',
		'HOST':'127.0.0.1',
        'PORT':'5432',
    }
}

     SMTP IN DJANGO 

	 SETTINGS.PY

EMAIL_BACKEND = âdjango.core.mail.backends.smtp.EmailBackendâ
EMAIL_HOST = âsmtp.gmail.comâ
EMAIL_USE_TLS = True
EMAIL_PORT = 587
EMAIL_HOST_USER = âyour_account@gmail.comâ
EMAIL_HOST_PASSWORD = âyour accountâs passwordâ

        ((( OR )))
		
EMAIL_BACKEND = "django.core.mail.backends.smtp.EmailBackend"
EMAIL_HOST = "smtp.gmail.com"
EMAIL_USE_SSL = True
EMAIL_PORT = 465
EMAIL_HOST_USER = "your_account@gmail.com"
EMAIL_HOST_PASSWORD = "your accountâs password"
  
  VIEWS.PY

import django
from django.core.mail import send_mail
from django.conf import settings

def email(request):
    subject = 'Thank you for registering to our site'
    message = ' It is great choosing to work with a team of perfectionists'
    email_from = settings.EMAIL_HOST_USER
    recipient_list = ['receiver@gmail.com',]
    send_mail( subject, message, email_from, recipient_list )
    return redirect('redirect to a new page')



%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&
===========================================================
WINDOWS AND UBUNTU

sudo apt install postgresql postgresql-contrib -> UBUNTU
sudo dnf install postgresql postgresql-contrib -> FEDORA
 


sudo systemctl start postgresql
sudo systemctl enable postgresql

sudo systemctl enable postgresql
sudo service postgresql restart

Connect to postgres:                  sudo -i -u postgres

-------------------------------------------------

psql

CREATE DATABASE myproject;

CREATE USER myprojectuser WITH PASSWORD 'password';

ALTER ROLE myprojectuser SET client_encoding TO 'utf8';
ALTER ROLE myprojectuser SET default_transaction_isolation TO 'read committed';
ALTER ROLE myprojectuser SET timezone TO 'UTC';

GRANT ALL PRIVILEGES ON DATABASE myproject TO myprojectuser;

--------------------------------------------------

Get current info:                     \conninfo


Postgresql commands
List all databases: \l.
Exit out of help menu: \q
Connect to database: \c database_name
List tables in current database: \dt
List columns in a table: \d table_name
See a list of all psql commands: \? (Press the down arrow to scroll through, or q to exit list.)
exit

######################################################## 
FORGOTTEN PASSWD/ SET NEW PASSWD ON POSTGRES
sudo -i -u postgres 
could not change directory to "/root"
psql (9.1.11)
Type "help" for help.

postgres=# \password
Enter new password:
Enter it again:
postgres=# \q
#########################################################

-------------------------------------------------------------------

INSTALL POSTGRESQL  -> https://linuxconfig.org/install-postgresql-on-ubuntu-18-04-bionic-beaver


sudo apt install postgresql-client
sudo apt install postgresql
 * Restart my pc then on the terminal *
sudo systemctl enable postgresql
sudo service postgresql restart

WINDOWS FIX FORPOSTGRES CONFIGURATION 

By default the PostgreSQL server will listen only on a local loop-back interface 127.0.0.1. If you need to configure your PostreSQL server to listen on all networks you will need to configure its main configuration file /etc/postgresql/10/main/postgresql.conf:
$ sudo nano /etc/postgresql/10/main/postgresql.conf
and add the following line somewhere to the CONNECTIONS AND AUTHENTICATION section:
listen_addresses = '*'

sudo service postgresql restart

&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&

PGADMIN INSTALLATION
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
sudo apt-get install virtualenv python3-pip libpq-dev python3-dev

cd
Create env:   virtualenv -p python3 pgadmin4
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
cd pgadmin4
source bin/activate
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
pip3 install https://ftp.postgresql.org/pub/pgadmin/pgadmin4/v4.2/pip/pgadmin4-4.2-py2.py3-none-any.whl

Configure
Override default paths and set it to single-user mode in the local configuration file:

For Python2.x
nano lib/python2.7/site-packages/pgadmin4/config_local.py

For Python3.x
nano lib/python3.6/site-packages/pgadmin4/config_local.py

Write:

import os
DATA_DIR = os.path.realpath(os.path.expanduser(u'~/.pgadmin/'))
LOG_FILE = os.path.join(DATA_DIR, 'pgadmin4.log')
SQLITE_PATH = os.path.join(DATA_DIR, 'pgadmin4.db')
SESSION_DB_PATH = os.path.join(DATA_DIR, 'sessions')
STORAGE_DIR = os.path.join(DATA_DIR, 'storage')
SERVER_MODE = False
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
python3 lib/python3.6/site-packages/pgadmin4/pgAdmin4.py
,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,
(Browser URL + PORT)
name                            DB1
connection(host name/addrress)  127.0.0.1
username                        postgres
passwd                          phoenix
,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,,
deactivate

----------------------------------------------------------------------------------------------------------
Flask Application structure

|-Watchlist
    |-app/
        |-main/
            |-__init__.py
            |-errors.py
            |-forms.py
            |-views.py
        |-static/
        |-templates/
        |-__init__.py
        |-models.py
        |-requests.py
    |-tests/
        |-test_movie.py
        |-test_review.py
    |-virtual/
    |-config.py
    |-.gitignore
    |-manage.py
    |-start.sh
 
-----------------------------------------------------------------------------------------------------------
FLASK 
pip3 install -r requirements.txt
pip3 freeze > requirements.txt

 Application 
  
  pip install flask
  curl https://bootstrap.pypa.io/get-pip.py | python
  pip install flask-bootstrap
  python3.6 -m  pip install gunicorn
  sudo apt-get update
  sudo apt-get install postgresql postgresql-contrib libpq-dev
  pip install flask-migrate
  pip install flask-login
  pip install flask-uploads
  pip install flask-mail
  pip install flask-simplemde markdown2


API

--aniso8601==8.0.0
click==7.1.2
Flask==1.1.2
Flask-RESTful==0.3.8
Flask-SQLAlchemy==2.4.3
itsdangerous==1.1.0
Jinja2==2.11.2
MarkupSafe==1.1.1
pytz==2020.1
six==1.15.0
SQLAlchemy==1.3.18
Werkzeug==1.0.1
---------------------------------------
DJANGO
pip3 install -r requirements.txt
pip3 freeze > requirements.txt

Application

 pip install django==1.11
 pip install django-bootstrap4
 pip install psycopg2
 pip install python-decouple
 pip install django-registration==2.4.1
 pip install djangorestframework
 pip install django-progressive-web-app

 API 
pip install djangorestframework
--------------------------------------------------------------------------------------------------------


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%


WINDOWS OFFICE SETUP https://getintopc.com/?s=Office+2016&submit=Search

WINDOWS (UBUNTU TERMINAL)
+++++++++++++++++++++++++++++++++++++++ 
cd /mnt/c/Users/Dan/
cd /mnt/c/Users/Dan/Desktop/Projects/


&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&




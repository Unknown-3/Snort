# Snort
As we know snort is not installed in Kali Linux 

We can use this commands on any Linux Distro and install snort or update sources.list

Download the sources.list from the Snort repository

The commands are:-

mv /etc/apt/sources.list /etc/apt/sources.list.bak

Copy the sources list file to Desktop

cd Desktop

cp sources.list /etc/apt

cd /var/lib/apt/lists

ls

sudo rm *  -  this command delete's all the files and keep the pre installed files

cd ~

sudo apt update

sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 3B4FE6ACC0B21F32


sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 40976EAF437D05B5

sudo apt update

sudo apt snort

snort --version

cd /var/lib/apt/lists

sudo rm *

rm /etc/apt/sources.list

mv /etc/apt/sources.list.bak /etc/apt/sources.list

sudo apt update

Now u can install applications or software

----------------------------------------------------Thank u very much Have fun!-------------------------------------------------







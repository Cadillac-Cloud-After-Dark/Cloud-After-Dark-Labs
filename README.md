# Welcome to Cloud After Dark ⛅️ Labs!
  _Powered by www.cloudafterdark.com_ 💪🏾⛅️🤓
  
 

## History of Linux

The goal of this readme is to give you a brief high level overview of Linux.

Linux was initially created as an open source alternative to Unix. You’re probably asking now.. Well what is Unix? Good question. Unix is a proprietary operating system created by a small team employed by Bell Labs (owned by AT&T) led by Ken Thompson and Dennis Ritchie in the 1970s. Unix was derived from an operations system called [Multics]. Unix was considered as the first "portable" operating system mainly due to the fact it was written in the C programming language. Prior to Unix many operating systems were tied to physical hardware. 

In 1983, [Richard Stallman] started the [GNU] project with the goal of creating a free open source UNIX-like operating system. It wasn't until 1991 when [Linus Torvalds] started a project that later became Linux. 

## Unix vs Linux

It's easy to get confused between UNIX and Linux because in a way they look and feel similar. UNIX is a proprietary operating system, while LINUX is open source. For example many people think that MACOS is Linux, but it's actually a UNIX based OS. You can run bash shell scripts almost unchanged on both MacOS and Linux based systems. 

## Debian vs RPM

When using Linux you can choose to install your applications with mainly 2 different package managers. A package manager keeps track of what software is installed on your machine. You can use a package manager to update/delete/add software on your machine. It's like the windows app store, but for Linux. The 2 most popular package managers are RPM (Redhat package manager) and Debian. 

Which one should you use? Well that depends. Different flavors of Linux are already preconfigured to use different package managers. 



Most popular Debian supported flavors 💽: 

👨🏾‍💻 Ubuntu

👨🏾‍💻 Linux Mint

👨🏾‍💻 KaliLinux

👨🏾‍💻 MX Linux

👨🏾‍💻 Deepin

👨🏾‍💻 Fedora Linux

👨🏾‍💻 Parrot OS

👨🏾‍💻 Arch Linux







Most popular RPM supported flavors 💽:

👨🏾‍💻 Redhat

👨🏾‍💻 Fedora

👨🏾‍💻 CentOS

👨🏾‍💻 OpenSUSE

👨🏾‍💻 OpenMandriva

👨🏾‍💻 Oracle Linux

## Linux boot process

Every operating system starts with a boot process. A boot process can be defined as a sequence of events that occur in order for the operating system to be available. Linux is no different. There are 6 stages in the Linux boot process. 

👉🏾 BIOS - Basic Input/Output System. The BIOS is responsible for running the boot loader program and checking the hard drive. Once the boot loader program is identified and loaded into the system memory the BIOS defers to the boot loader program.

👉🏾 Master Boot Record - MBR stands for Master Boot Record. The MBR is responsible for loading and starting the GRUB boot loader.

👉🏾 GRUB - Stands for GNU GRand Unified Bootloader. This is the standard boot loader for all Linux systems. You can find the GRUB configuration file  here /boot/grub/grub.conf or /etc/grub.conf

👉🏾 Kernel -  This is the brains of your operating system. The kernel executes the /sbin/init program.

👉🏾 Init - Init reads the initialization file, /etc/inittab. This tells init to read the initial configuration script.

👉🏾 Runlevel programs - Runlevels determine which programs can execute after the OS boots up.





## Why Linux is important

Most of the tools that you are going to learn in these labs live on top of Linux. It's important to know basic commands because they bleed over into the commands you will need to know to use these "additional" tools. Also from an automation standpoint it is easy to pick up bash scripting if you already know some bash commands. In theory you are just adding some computer science concepts on top of these shell commands in order to automate certain tasks. 

If you are going the DevOps route, automating various processes will be a part of your job. Although Bash scripting isn't an OOP (Object-oriented programming language) it is still useful and powerful when it comes to automating in Linux/Unix.


## Setting up your machine 🖥

For these labs we will be using Ubuntu which is a Debian flavor of Linux (using an EC2 on AWS).

If you don't have access to a command line system (mac) the easiest way to get started is:

🔥Windows - Install Ubuntu [WSL] 

OR:

🔥Spin up a Ubuntu VM in [AWS]/[GCP]/[AZURE]

OR:

🔥If you have [Docker] spin up a Ubuntu container


Happy learning!



[Multics]: <https://en.wikipedia.org/wiki/Multics>
[Linus Torvalds]: <https://en.wikipedia.org/wiki/Linus_Torvalds>
[Richard Stallman]: <https://en.wikipedia.org/wiki/Linus_Torvalds](https://en.wikipedia.org/wiki/Richard_Stallman>
[GNU]: <https://en.wikipedia.org/wiki/GNU_Project>
[WSL]: <https://docs.microsoft.com/en-us/windows/wsl/install>
[AWS]: <https://aws.amazon.com/account/>
[GCP]: <https://console.cloud.google.com/>
[AZURE]: <https://azure.microsoft.com/en-us/get-started/azure-portal/>
[Docker]: ,https://hub.docker.com/_/ubuntu.

 



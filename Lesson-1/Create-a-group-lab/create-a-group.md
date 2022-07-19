## Overview

In this lab you will create a group in Linux.

## What is a group ?



🏠 A group is like a container. You can put mulitple users in groups who have need similar  permissions.

🏠 Groups remove the burden of having to set permssions for each seperate user. 

🏠 Each group gets assigned a unique ID.

## Group types

There are 2 types of groups in Linux

👉🏾 Primary group - Automatically created while creating a user with a unique user ID. When a new user is created a group with the same ID as the user ID is created.

👉🏾 Secondary group - Can be created separately. Grant certain privileges to a set of users.


## Create a Group
Let's create a group!

Command: 

sudo groupadd "GroupName"


A closer look 👀:

⭐️ sudo - Allows you to run a single command as root

⭐️ groupadd - creates a user

⭐️ GroupName - Name of your group

![groupadd](https://user-images.githubusercontent.com/109482212/179641969-af90d302-4df9-4f66-ac92-17003038d57c.jpg)

## Verify your created Group

Congrats! In the step above you created a new group using the groupadd command. Now let's verify that we can see 👀 your group in your system. In Ubuntu you can see all groups by typing:

💁🏾‍♂️ cat /etc/group

As you can see all groups live in the /etc/group directory (in Linux a directory is the equivelent to a folder 🗂 in windows...but you know this already 🤓).


☞ "cat" 🙀 - The cat command reads data from the file and outputs the contents to your terminal.

☞ /etc - is a directory. the /etc directory is where a Linux system's configuration files live.

☞ /group - is the directory that holds information about system groups.

As you can see I just ran the cat /etc/group command, however there are several groups that are created by default.

![variousgroups](https://user-images.githubusercontent.com/109482212/179643342-a2f5d384-2d54-430b-b7a1-793ee6f5286f.jpg)

If you scroll down to the bottom you can see your newly created group at the end, HOWEVER there is an easier way to search through large files.

## 🎺 Introducing the grep command 🎺


The grep command can be used to search for patterns in a file or output.

In front of the grep command you see "|" this is referred to as a "pipe". The pipe command lets you sends the output of one command to another

![grepgroupadd](https://user-images.githubusercontent.com/109482212/179643598-06a52e4e-66a5-4356-a4b6-bcb43cc749e1.jpg)

## Group entry format

Let's look at the format of the group entry above:

✅ Cloudafterdark - Groupname

✅ :x - Usually the space for the password. In this case it is not used

✅ :1002 - Group ID 

## Deleting groups 🗑

You can use the delgroup command to delete a group in Linux


![delgroup](https://user-images.githubusercontent.com/109482212/179644885-c5e13b25-453d-48c7-bd26-0eefe3c2fa95.jpg)

Let's take a closer look at the format of this command:

👉🏾 sudo - allows us to run this command with root privileges
👉🏾 delgroup - command to delete group
👉🏾 CloudAfteDark - the group name we want to delete





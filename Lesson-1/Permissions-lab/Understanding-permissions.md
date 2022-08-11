## Overview

In this lab you will get familiar with permissions. 

## What are permissions?

Linux is a multi-user operating system. Permissions act as a security mechanism to prevent people from accessing each other’s confidential files. 

## How to see file permissions

We can view file permissions a couple different ways. The "ls" command is used to list files or directories. 

![LSCOMMAND](https://user-images.githubusercontent.com/109482212/179658382-b8fb47b7-8c87-42c8-9bfe-f3ae86d2ad54.jpg)

As you can see 👀 from the ls command the terminal prints out the file and directory names, but not any permissions information.

We can use the ls -l command to invoke the long list format. This is a fancy way of saying, we want more robust information about this directory and the files in it.

![ll](https://user-images.githubusercontent.com/109482212/179658714-8e3d016f-ac25-49c8-b494-add314888810.jpg)


## A closer look at permissions


![image](https://user-images.githubusercontent.com/109482212/179657964-be2d9f70-a0bf-42c4-b203-4e65bbabafc8.png)

## Changing permissions

The chmod command allows a user to change the permissions on a file using either a symbolic or numeric mode.

There are 2 ways to change permissions in Linux you can use numbers or letters.... What do I mean??

 
![chmod](https://user-images.githubusercontent.com/109482212/179661249-56c4c68a-2b10-4e89-add6-2eeaf1921d92.png)

From the chart we can see we can use letters or numbers to change permissions.

## You try

✅ Use the chmod 777 "filename" to change permissions on a file.

✅ Now do a ls -l

Notice the permissions change?

✅ Next use the chmod +rwxrwxrwx "filename".

Notice the permissions stayed the same.

We can use either format to change the permissions on a file.




![numbersandletters](https://user-images.githubusercontent.com/109482212/179662107-86bbc2bc-228b-4420-82f1-e5d79eab4a1f.jpg)


Let's take a closer look 🕵🏾‍♂️ shall we???


👉🏾 chmod - allows a user to change the permissions on a file

👉🏾 777 - tells the system I want to be able to read/write/execute for the permissions classes: Users groups other.

👉🏾 filename - name of file or directory you want to change permissions on

![777](https://user-images.githubusercontent.com/109482212/179662784-2720dc00-2a55-46cf-b31d-35ead79a2f15.jpg)






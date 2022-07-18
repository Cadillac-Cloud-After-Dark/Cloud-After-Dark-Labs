## Overview

In this lab you will create a user. 

## What is a user?

👨🏾‍💻 A user can be defined as an entity. 

👨🏾‍💻 This entity can manipulate files and do other operations. 

👨🏾‍💻 Each user gets assigned an unique ID.


## Create a User
Let's create a user!

Command: 

sudo useradd "UserName"



![ubuntuuseradd](https://user-images.githubusercontent.com/109482212/179629117-5ff73760-8dca-42bd-831b-2100201fc7aa.jpg)


## Verify your created User

Congrats! In the step above you created a new user using the useradd command. Now let's verify that we can see your user in your system.
In Ubuntu you can see all users by typing cat /etc/passwd. As you can see all users live in the /etc/passwd directory (in Linux a directory is the equivelent to a folder in windows).

Let's break this command down:
"cat" - The cat command reads data from the file and outputs the contents to your terminal. 
/etc - is a directory. the /etc directory is where a Linux system's configuration files live.
/passwd - is the directory that holds information about system users.

![listuserscat](https://user-images.githubusercontent.com/109482212/179630472-cb65bc96-941d-4f3a-b2f6-36068a580228.jpg)


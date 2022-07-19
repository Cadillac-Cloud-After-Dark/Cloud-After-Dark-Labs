## Overview

In this lab you will create a group in Linux 

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



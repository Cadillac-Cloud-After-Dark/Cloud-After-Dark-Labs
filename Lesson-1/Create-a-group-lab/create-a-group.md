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

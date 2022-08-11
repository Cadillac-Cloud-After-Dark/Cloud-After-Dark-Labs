## Creating text with the vi command

Vi is regarded as the most popular text editor program ✍🏽 in Linux/Unix. This is mainly because it's included by default with every UNIX
and the linux system. You can think of vi as Windows notepad on Linux.

In this lab we are going to cover using Vi to create a text file.

&nbsp;
&nbsp;

## Creating a file with Vi
We are going to use the vi command to create a file. 

Let's look 👀 at the command below:

![vicreate](https://user-images.githubusercontent.com/109482212/183311283-c639fff2-3dab-42ed-b802-fe5cdd5f4764.jpg)


👉🏾 vi Sleep.txt

👉🏾 vi - Tells the system that you want to create/edit a file

👉🏾 Sleep.txt - Is the name of the file you want to create. 

🚨 If the file already exists the system will open that existing file and you will be able to view/edit the contents. If the file does not exist already in that directory the system will create a new empty file for you in the editor.


## Common vi commands
Vi is a great tool for creating text files 📝 with multiple lines.

To inset text in vi press the "i" key. This will put you in INSERT mode. INSERT mode will allow you to add lines of text to a file. There will be an indicator at the bottom of the screen to confirm you are in insert mode.

![image](https://user-images.githubusercontent.com/109482212/183311467-cf3993b2-2354-4ff6-b024-e522a52693b6.png)

🚨 Please not you cannot use your mouse in INSERT mode. You will have to move around with the arrow keys.

## Saving your text in Vi
Now that you have added some text to your file press the "esc" key. This will take you out of INSERT mode. You will notice that INSERT is no longer at the bottom of the screen. 

No press shift + : . This will allow you to now tell Vi what you want to do with this file. You have a couple of options:

👉🏾 q! + enter - will quit this vi session and not save the file

👉🏾 wq! + enter - Will save or "write" the file and quit the editor

![image](https://user-images.githubusercontent.com/109482212/183311745-59fe85b4-a9eb-4f6d-b4a2-234abb37bda5.png)

Congrats! Now you know the basics of vi. Go try it for yourself. 💨




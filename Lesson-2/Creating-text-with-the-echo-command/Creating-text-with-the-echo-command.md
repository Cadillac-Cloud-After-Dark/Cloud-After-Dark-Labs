## The "echo" command


The echo command in Linux is a built in command that prints out text to a terminal. You can think of the echo command like a parrot 🦜. 
If you say something to a parrot it has the ability to repeat it back to you.


&nbsp;
&nbsp;

![echocommand1](https://user-images.githubusercontent.com/109482212/179850336-5925a8cb-596b-4fd7-b295-7e7bf272d9d2.jpg)

&nbsp;
&nbsp;

As you can see from the command above echo will take anything that is between "" and print it out to the terminal.

## Using the echo command to create a text file

The echo command can also be used as a handy tool to quickly create or modify a text file that only needs a couple of lines added.

&nbsp;
&nbsp;

![echofilecreate](https://user-images.githubusercontent.com/109482212/179851661-f806dc45-bd9f-4295-bb6a-e1f5a33edd1f.jpg)

&nbsp;
&nbsp;

Let's take a closer look 🧐 at this command:

👉🏾 echo "Today is a great day" > today.txt

👉🏾 echo - Prints out text to the terminal

👉🏾 "" - Text we want to print or add to a file

👉🏾 ">" - this symbol allows us to redirect the output of the echo command to a file. The system will create a new file or overwrite an existing file

👉🏾 today.txt - Name of the file we want to create

&nbsp;

🚨🚨 Also note that only using 1 redirect symbol ">" will either create a new file OR overwrite an exsisting file. If you already have a file created and you use the echo command along with only 1 ">" symbol, the contents of the file will get replaced with whatever the output of the echo command is. 🚨🚨

&nbsp;

## Using the echo command to add a line to an existing file

We can also use the echo command to append/add a line to an existing file.

&nbsp;
&nbsp;

![echoappend](https://user-images.githubusercontent.com/109482212/179852746-7e07e201-7ef3-4813-b132-62c255dac53b.jpg)

&nbsp;
&nbsp;

Let's take a closer look 🧐 at this command:

👉🏾 echo "Friday will be a great day" >> today.txt

👉🏾 echo - Prints out text to the terminal

👉🏾 "" - Text we want to print or add to a file

👉🏾 ">>" - this symbol allows us to redirect the output of the echo command to a file and adds the ouput to the end of the file.

👉🏾 today.txt - Name of the file we want to create

&nbsp;

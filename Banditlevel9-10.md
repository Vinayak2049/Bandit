#Bandit level 9-10 write-up

##Objective: Find the password for next level from a file called "data.txt" followed by many "="

##Steps taken: 1.Connecting to server

Used the SSH command to login to the server with the provided password

Command: ssh bandit9@bandit.labs.overthewire.org -p 2220

2.Finding the file

Using ls command found the file data.txt

Command:ls

3.Finding password

Using grep,strings commands and found the password

Command:strings data.txt |grep '=='

# Solution

## ssh into app server 2:  

`` ssh steve@stapp02 ``  
`` sudo su - ``  

## List the files and folders:  

`` ll /home/usersdata/ ``  

## Find the file names by user as per the task and copy with folder structure:  

`` find /home/usersdata/ -type f -user james -exec cp --parents {} /media \; ``  

## List the files copied in the destination folder:  

``  ll /home/usersdata ``  

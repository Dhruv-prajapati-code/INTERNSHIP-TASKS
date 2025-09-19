#TASK-1
##Explore the Default Bridge Network 
 
●  Run one nginx container and one alpine container (default bridge). 
 
●  From inside the alpine container, install curl: 
 
Try to access with curl nginx → it should fail in the default bridge. 
👉 Lesson: Default bridge uses IP-based communication, not container names.

![filters image](https://github.com/Dhruv-prajapati-code/INTERNSHIP-TASKS/blob/b1420ffba8625f46ed30da35d86f22d3d29c719f/1.png)

##Run a Container With No Network 
 
●  Start a container with no network 
●  Enter the container and try ping google.com. 
👉 It should fail, because the container has no network access

![filters image](https://github.com/Dhruv-prajapati-code/INTERNSHIP-TASKS/blob/b1420ffba8625f46ed30da35d86f22d3d29c719f/2.png)

##Use a Custom Bridge Network 
 
●  Create a network: 
●  Run a MySQL container and a WordPress container in this network. 
 
●  Test: WordPress should connect to the database using the hostname db 
instead of an IP. 
 👉 Lesson: Custom bridge allows DNS-based service discovery
 
![filters image](https://github.com/Dhruv-prajapati-code/INTERNSHIP-TASKS/blob/b1420ffba8625f46ed30da35d86f22d3d29c719f/3.png)

##Attach a Container to Multiple Networks 
 
●  Start a container in one network. 
●  Then attach it to another 
●  Inspect the container → it should have two different IPs (one for each 
network). 
 
👉 Lesson: Containers can be part of multiple networks at the same time

![filters image](https://github.com/Dhruv-prajapati-code/INTERNSHIP-TASKS/blob/b1420ffba8625f46ed30da35d86f22d3d29c719f/4-2.png)

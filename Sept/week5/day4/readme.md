# AZURE VM TAKS
1 Create a VM with azure , Download SSH pem key with some user name  
2 Copy Public key from Overview after VM creation  
3 Do SSH to terminal with SSH -i pem_key_location username@pulic_IP
4 After that apt update && apt install nginx  
5 systemctl status nginx (Running)   
6 Now add inbound rule for html pot 80   
![filters image](https://github.com/Dhruv-prajapati-code/INTERNSHIP-TASKS/blob/0158ad668bd68dfd169167fc073f328bf34163dc/Sept/week5/day4/Screenshot%20(183).png)  
![filters image](https://github.com/Dhruv-prajapati-code/INTERNSHIP-TASKS/blob/0158ad668bd68dfd169167fc073f328bf34163dc/Sept/week5/day4/Screenshot%20(184).png)   

### Assessment  
## Task1 
1) Created acr and log in to it :-az acr create --resource-group Assessment --name myacrdhruvlab --sku Basic, az acr login --name myacrdhruvlab
2) Build and Pushed image on Acr:- docker push myacrdhruvlab.azurecr.io/my-web-app:v1.0

![filters image](https://github.com/Dhruv-prajapati-code/INTERNSHIP-TASKS/blob/5cd577d468b6c43ff3c3a05c96782866da7db25d/Oct/Assessment1/Screenshot%20(195).png)
![filters image](https://github.com/Dhruv-prajapati-code/INTERNSHIP-TASKS/blob/5cd577d468b6c43ff3c3a05c96782866da7db25d/Oct/Assessment1/Screenshot%20(196).png)

## Task2 
1) Created Aks cluster& connected to Acr:- az aks create \ 
  --resource-group myResourceGroup \ 
  --name aks-dhruv-cluster \ 
  --node-count 2 \ 
  --enable-addons monitoring \ 
  --generate-ssh-keys \ 
  --attach-acr myacrdhruv lab
2) Created deployment.yml and service.yml and open the export ip on browser
3) Then scaled the replicas :-kubectl scale deployment mywebapp --replicas=5

![filters image](https://github.com/Dhruv-prajapati-code/INTERNSHIP-TASKS/blob/5cd577d468b6c43ff3c3a05c96782866da7db25d/Oct/Assessment1/Screenshot%20(197).png)
![filters image](https://github.com/Dhruv-prajapati-code/INTERNSHIP-TASKS/blob/5cd577d468b6c43ff3c3a05c96782866da7db25d/Oct/Assessment1/Screenshot%20(198).png)
![filters image](https://github.com/Dhruv-prajapati-code/INTERNSHIP-TASKS/blob/5cd577d468b6c43ff3c3a05c96782866da7db25d/Oct/Assessment1/Screenshot%20(199).png)
![filters image](https://github.com/Dhruv-prajapati-code/INTERNSHIP-TASKS/blob/5cd577d468b6c43ff3c3a05c96782866da7db25d/Oct/Assessment1/Screenshot%20(200).png)
![filters image](https://github.com/Dhruv-prajapati-code/INTERNSHIP-TASKS/blob/5cd577d468b6c43ff3c3a05c96782866da7db25d/Oct/Assessment1/Screenshot%20(202).png)
![filters image](https://github.com/Dhruv-prajapati-code/INTERNSHIP-TASKS/blob/5cd577d468b6c43ff3c3a05c96782866da7db25d/Oct/Assessment1/Screenshot%20(203).png)
![filters image]()

## Task 3 

![filters image]()
![filters image]()
![filters image]()
![filters image]()
![filters image]()
![filters image]()
![filters image]()


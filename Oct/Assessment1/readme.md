### Assessment  
## Task1 
1) Created acr and log in to it :-az acr create --resource-group Assessment --name myacrdhruvlab --sku Basic, az acr login --name myacrdhruvlab
2) Build and Pushed image on Acr:- docker push myacrdhruvlab.azurecr.io/my-web-app:v1.0


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

## Task 3 

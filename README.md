# Kubernetes-Summary-Task

###### Please use your last homework assignments:
###### - The Bitcoin app
###### 1- Dockerize your Bitcoin applications
###### 2- Create Kubernetes manifests (Deployment and service)
###### 3- Deploy on your minikube
###### 4- Deploy/Enable Ingress Controller on your cluster
###### 5- Create an ingress that directs the traffic to the correct service:
###### http://…/bitcoin → bitcoin service

------------


### Dockerized and Published on dockerhub
![Screenshot_3](https://user-images.githubusercontent.com/40535130/205516387-3a4b1f7c-626d-4115-984b-5e3089cf3755.png)



------------


## Run 

### Clone the project
###### git clone https://github.com/Eyad-Amer/Kubernetes-Summary-Task.git

------------

### Go to the project directory
###### cd Kubernetes-Summary-Task

------------

### Start Minikube
###### minikube start

------------

### Apply the yml Files
###### kubectl apply -f .

------------

### Enagle ingress plugin
######   minikube addons enable ingress
  
------------


  ### Servers status
######   kubectl get po,svc

  ![Screenshot_2](https://user-images.githubusercontent.com/40535130/205506651-e469f05f-4040-4b85-8676-b78c9d738b95.png)

![Screenshot_1](https://user-images.githubusercontent.com/40535130/205506689-13cbe88e-9617-4c3b-8f96-09ff5673ccad.png)


------------

### Start minikube tunnel
###### minikube tunnel


------------

### BitCoin LocalHost
###### localhost:8000
![browser app](https://user-images.githubusercontent.com/40535130/205506994-e83033aa-d265-4277-a3cd-d76aef072aa6.jpg)

------------

### Stop minikube
###### minikube stop

------------

### Delete minikube
###### minikube delete

------------

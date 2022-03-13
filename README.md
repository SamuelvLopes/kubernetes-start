# kubernetes-start

### minikube start --driver=docker
### minikube status
### minikube stop
### minikube dashboard
### minikube dashboard --url

### kubectl create deployment <nome> --image=<nome da imagem>

### kubectl get deployments
### kubectl get pods
### kubectl describe deployments
### kubectl describe pods
### kubectl config view


### kubectl expose deployment <NOME> --type=<tipo> --port=<port>
### kubectl expose deployment kubtest --type=LoadBalancer --port=5000


### minikube service kubtest

### kubectl create deployment testekube --image=samuellopes123/pykub
### kubectl expose deployment testekube --type=LoadBalancer --port=5000
### minikube service testekube
### minikube tunnel


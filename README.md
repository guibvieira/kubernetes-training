# kubernetes-training
Repo to play around with Kubernetes 

The following instructions were done on MacOS

Make sure you have brew and Docker installed

To install kubectl
- brew install kubectl

To install VirtualBox go on virtualbox.org

To install minikube run:
- brew install minikube

To start it up 
- minikube start

Once you have minikube running, deploy the multi-app container into the cluster by running:
- kubectl apply -f k8s 
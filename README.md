# multik8s-pythonwebapp-skaffold

Python+Flask web application running locally in Kubernetes cluster using Skaffold

Steps to run Python Application using Skaffold:

- Install Kubectl.
- Install skaffold.
- Install Virtual Machine.
- Then do *skaffold dev* from the route directory of the project.
- BOOM its ready.


Commands

- kubectl get pods - To get list of Pods
- kubectl get nodes - To get list of Nodes
- kubect get services - To get list of Services
- kubectl get pvc - To get list of Persistent Volume Claims
- kubectl get pv - To get list of Persistent Volumes

# Advantages of using Skaffold over minikube 
Code will update the running pod. Then we don't have to manually update pod-template in Imperative way by tagging appropriate DOCKER_IMAGE with TAG_ID.

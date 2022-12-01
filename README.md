Example Voting App
=========

A simple distributed application running across multiple Pod  in K8S .

Getting started
---------------

### prerequisite

####### - AWS account 
####### - Install eksctl
####### - Install kubectl


### run 

```diff 
eksctl create cluster -f ./eks/create_eks.yaml

# after your cluster be ready

sudo chmod +x ./deploy_voting_app.sh

# then
sudo ./deploy_voting_app

# the 
kubectl get svc

```
## App Architecture.png
<img src="/architecture.png" alt="Permissions" />


1. `minikube start`
2. `kubectl create -f replicaset-definiton.yml`

To update a replicaset:  
1. Update the replicaset .yml file
2. `kubectl replace -f replicaset-definition.yml`
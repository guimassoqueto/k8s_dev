1. `minikube start`
2. `kubectl create -f pod-definition.yml`
3. `kubectl get pods`

Without the definition file, you can run/start a pod with:  
`kubectl run <custom_pod_name> --image=<image_name>`

Where:  
* <custom_pod_name>: the name you are giving to the pod
* <image_name>: the image of the container (from a container registry, like DockerHub for example)

Deleting a pod:  
`kubectl delete pod <pod_name>`

Editing a running/wrong pod:  
`kubectl edit pod <pod_name>`
### Imperative form
In the command line: `kubectl create configmap <configmap_name> --from-literal=<KEY1>=<VALUE1> --from-literal=<KEY2>=<VALUE2>`  

where:  
<configmap_name> is the custom name of the configMap
<KEY> is the env variable key you want to specify
<VALUE> is the value of the env var you want to specify

from file: `kubectl create configmap <configmap_name> --from-file=<path_to_env_file>`  

where:
<configmap_name> is the custom name of the configMap
<path_to_env_file> is the absolute path to the env file

### Declarative form
`kubectl create -f config-map.yaml`
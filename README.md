# loki-cluster

To add repository in Helm:
  `helm repo add loki-cluster https://sophiakorginska.github.io/loki-cluster/`  
  `helm update`  
 
Then install loki:  
  `helm install --name loki --namespace loki loki-cluster/loki`  
  `helm install --name loki --namespace loki loki-cluster/loki-with-authentication`  

  

$ kubectl get pods <pod-name> -o=jsonpath='{.metadata.ownerReferences[0].name}' **finding a ReplicaSet from a Pod**  
$ kubectl get pods -l app=kuard,version=2 **finding a set of Pods for a ReplicaSet**  
$ kubectl scale replicasets kuard --replicas=4 **imperative scaling with kubectl scale**  


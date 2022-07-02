$ kubectl get pods <pod-name> -o=jsonpath='{.metadata.ownerReferences[0].name}' **finding a ReplicaSet from a Pod**  
$ kubectl get pods -l app=kuard,version=2 **finding a set of Pods for a ReplicaSet**  
$ kubectl scale replicasets kuard --replicas=4 **imperative scaling with kubectl scale** 
$ kubectl autoscale rs kuard --min=2 --max=5 --cpu-percent=80 **autoscaling based on CPU**  
$ kubectl delete rs kuard --cascade=false **delete the ReplicaSet object without the managed Pods**  
 


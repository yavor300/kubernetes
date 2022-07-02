$ kubectl get pods <pod-name> -o=jsonpath='{.metadata.ownerReferences[0].name}' **finding a ReplicaSet from a Pod**


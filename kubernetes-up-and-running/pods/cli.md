$ kubectl run kuard --generator=run-pod/v1 --image=gcr.io/kuar-demo/kuard-amd64:blue **creating a Pod**  
$ kubectl delete pods/kuard **deleting a Pod**  
$ kubectl apply -f kuard-pod.yaml **running Pods**  
$ kubectl get pods **listing Pods**  
$ kubectl describe pods kuard **Pod details**  
$ kubectl delete -f kuard-pod.yaml **deleting a Pod using the manifest**  
$ kubectl logs kuard **getting more info with logs**  
$ kubectl exec -it kuard -- ash **running commands in your Container with exec**  
$ kubectl port-forward kuard 8080:8080 **port-forward to the Pod**  


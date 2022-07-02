$ kubectl run alpaca-prod \  
  --image=gcr.io/kuar-demo/kuard-amd64:blue \  
  --replicas=2 \  
  --labels="ver=1,app=alpaca,env=prod"  
**applying Labels**  
$ kubectl label deployments alpaca-test "canary=true" **modifying Label**  
$ kubectl label deployments alpaca-test "canary=true" **remove Label**  
$ kubectl get pods --selector="ver=2" **list Pods that have certain Label values**  


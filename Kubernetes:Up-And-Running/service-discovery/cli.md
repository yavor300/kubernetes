$ kubectl label deployments alpaca-test "canary=true" **create a Service**  
$ kubectl get endpoints alpaca-prod --watch **view Service enpoints**  
$ kubectl describe service alpaca-prod **describe Service**  
$ kubectl describe endpoints alpaca-prod **describe Endpoint**  


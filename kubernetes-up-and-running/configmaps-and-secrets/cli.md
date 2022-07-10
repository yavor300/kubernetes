$ kubectl create configmap my-config \  
  --from-file=my-config.txt \  
  --from-literal=extra-param=extra-value \  
  --from-literal=another-param=another-value  
**imperative way to create a ConfigMap**  
$ kubectl create secret generic kuard-tls \  
  --from-file=kuard.crt \  
  --from-file=kuard.key  
**imperative way to create a Secret**  
$ kubectl create secret docker-registry my-image-pull-secret \  
  --docker-username=<username> \  
  --docker-password=<password> \  
  --docker-email=<email-address>  
**create image pull secret**  
$ kubectl get secret <secret_name> -o yaml **show the secrets values**  



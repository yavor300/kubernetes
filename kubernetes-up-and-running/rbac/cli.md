$ kubectl auth can-i get pods --subresource=logs
$ kubectl get clusterroles **get built-in cluster roles**  
$ kubectl get clusterrolebindings **get cluster role bindings**  
$ kubectl auth can-i create pods **check if the currently authorized kubectl user is allowed to create pods**  
$ kubectl auth can-i get pods --subresource=logs **check with --subresources argument**  
$ kubectl auth reconcile -f some-rbac-config.yaml **reconcile a set of roles and role bindings with the current state of the cluster.**  



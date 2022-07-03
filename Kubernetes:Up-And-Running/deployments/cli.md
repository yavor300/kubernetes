$ kubectl scale deployments kuard --replicas=2 **resize the Deployment**  
$ kubectl rollout status deployments kuard **monitor triggered Deployment rollout**  
$ kubectl rollout pause deployments kuard **temporarily pause a rollout**  
$ kubectl rollout resume deployments kuard  **resume paused rollout** 
$ kubectl rollout history deployment kuard **rollout history**  
$ kubectl rollout history deployment kuard --revision=2 **more details about a particular revision**  
$ kubectl rollout undo deployments kuard **roll back to the previous rollout**  
$ kubectl rollout undo deployments kuard --to-revision=3 **roll back to a specific revision in the history**  
 

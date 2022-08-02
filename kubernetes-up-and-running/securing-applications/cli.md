$ kubectl label --dry-run=server --overwrite ns --all pod-security.kubernetes.io/enforce=baseline **The command evaluates all Pods on a Kubernetes cluster agains the baseline Pod Security Standard and reports violations as warning messages in the output.**  
$ kubectl apply -f https://raw.githubusercontent.com/aquasecurity/kube-bench/main/job.yaml **benchmark security kubernetes tool**  
$ kubectl logs job/kube-bench **view job security logs**  


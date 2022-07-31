$ kubectl label --dry-run=server --overwrite ns --all pod-security.kubernetes.io/enforce=baseline **The command evaluates all Pods on a Kubernetes cluster agains the baseline Pod Security Standard and reports violations as warning messages in the output.**  


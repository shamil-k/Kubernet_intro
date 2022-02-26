# Kubernet_intro

# Reference 

https://www.vmware.com/topics/glossary/content/kubernetes.html

# comands to build a sample container on the pod
```
kubeclt get po
kubeclt get pod
kubectl describe pod nginx
kubectl run nginx --image=nginx --dry-run=client output-spec.yaml
kubectl run nginx --image=nginx --dry-run=client -o yaml > pod-spec.yaml

```

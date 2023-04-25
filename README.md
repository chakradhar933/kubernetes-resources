### kubernetes-resources
- Kubernetes resources are created with YAML files. Basic syntax is
```YAML
---
apiVersion:
kind:
metadata:
    name:
spec:
```
To apply resourses:
Create:
```bash
kubectl apply -f [file-name].yaml
```
Delete
```bash
kubectl delete -f [file-name].yaml
```




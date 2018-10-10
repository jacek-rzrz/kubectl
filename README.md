# kubectl

## Pods are crashing
Get the id of the failed pod with `kubectl get pod`, then check logs of the previous instance:

```
kubectl logs POD_ID --previous
```

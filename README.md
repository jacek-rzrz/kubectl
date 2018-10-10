# kubectl

## Pods are crashing
Get the id of the failed pod with `kubectl get pod`, then check logs of the previous instance:

```
kubectl logs POD_ID --previous
```

## Pods are down but there are no errors in the app logs
Check if the cluster has enough resources:
```
kubectl describe deployment SERVICE_NAME
```

## Edit deployment temporarily
```
kubectl edit deployment APP_NAME
```


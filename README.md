## example-apps

### Deploy

```
kubectl create -f back1.yaml
kubectl create -f back2.yaml
```

### Destroy

```
kubectl delete ingress back1 back2
kubectl delete service back1 back2
kubectl delete deploy  back1 back2
```

## example-apps

### Deploy

```
kubectl create -f namespaces.yaml
kubectl create -f public.yaml
kubectl create -f secure.yaml
```

### Destroy

```
kubectl delete ns public
kubectl delete ns secure
```

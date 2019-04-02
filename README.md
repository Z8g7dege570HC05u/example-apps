## example-apps

#### Deploy simple apps

```
k8s-handle deploy -s secure
k8s-handle deploy -s public
```

#### Deploy apps with certs


```
k8s-handle deploy -s secure_cert
k8s-handle deploy -s public_cert
```

Next: uncomment `025_certificate.yaml.j2`, render and `kubectl apply`:
```
k8s-handle render -s secure_cert && kubectl apply -f /tmp/k8s-handle/025_certificate.yaml
k8s-handle render -s public_cert && kubectl apply -f /tmp/k8s-handle/025_certificate.yaml
```

# kubernetes-mongodb
Working mongodb replica sets with kubernetes.

```
kubectl create -f mongodb.yaml
```

This will create a mongodb replica set across three nodes with an admin account that has credentials you define with environment variables.

Other useful things:
If you are having trouble deleting statefulsets while setting things up / testing (don't do this in production)
```
# Note you wouldn't want to do this normally.
kubectl delete -f mongodb.yaml
```

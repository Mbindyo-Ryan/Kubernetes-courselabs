Delete the database that was bei used before by using:
```bash
kubectl delete deploy products-db
kubectl delete svc products-db
kubectl delete pvc -l app=products-db
```
Deploy the changes using:
```bash
kubectl apply -f < name-of-the-file >.yaml
```



Run commands:

```bash
# Create Namespace
kubectl apply -f 00-namespaces.yml

kubectl get namespaces

# Create Storage
kubectl apply -f 01-storage_v4.yml

# Create Claims 
kubectl apply -f 02-claims_v4.yml

# Create Config
kubectl apply -f 03-config_v6.yml

# Create Deployment
kubectl apply -f 04-deployment_v9.yml
```

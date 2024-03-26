# ArgoCD-App-Of-Apps
Deploy Kubernetes Plugins with ArgoCD App-Of-Apps

### Preparations
clone the repository to local machine:
```
git clone https://github.com/danielyaba/argocd-app-of-apps.git && cd argocd-app-of-apps
```


Modify values files  or alternativly insert them under application file for each plugin depending on your needs

### Deployment
```
kubectl apply -f devops-apps.yaml
```



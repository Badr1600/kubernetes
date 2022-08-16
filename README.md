"# kubernetes" 

Get ArgoCD default password
kubectl get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | echo
# Helm Playground

## Building Helm Charts

```bash
helm install demo-guestbook guestbook

kubectl get pods

helm list

helm upgrade demo-guestbook guestbook

kubectl describe pod -l app=frontend

helm status demo-guestbook

helm rollback demo-guestbook 1

helm history demo-guestbook

helm uninstall demo-guestbook
```

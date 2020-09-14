# Helm Playground

Setup minikube

```bash
minikube start
minikube addons enable ingress

minikube ip
sudo vim /etc/hosts #YOUR_MINIKUBE_IP frontend.minikube.local backend.minikube.local

minikube status
```

Add Helm repos

```bash
helm repo add stable https://kubernetes-charts.storage.googleapis.com/
```

Example

```bash
helm install demo-mysql stable/mysql

kubectl get all | grep mysql

helm uninstall demo-mysql
```

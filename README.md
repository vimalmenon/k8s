# k8s

### Todo List
- [ ] Find the name for App
- [ ] Check memory usage
- [ ] Set Kube Config file
- [ ] Checking ISTIO
- [ ] Set up CI CD
- [ ] Argo CD


### Useful CMDdocker
Start Minikube Cluster
```sh
minikube start -n 2 -p local
```
Stop Minikube Cluster
```sh
minikube stop -p local
```
Delete Minikube Cluster
```sh
minikube delete -p local
```
Check Helm lint
```sh
helm lint
```
Helm Install 
```sh
helm install local ./
```
Change Kubeconfig file
```sh
export KUBECONFIG=/path/to/admin.conf
```

### Useful link
[Add metrics in CIVO](https://www.civo.com/marketplace/metrics-server)

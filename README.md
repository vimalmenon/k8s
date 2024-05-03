# k8s

### Todo List
- [ ] Find the name for App
- [ ] Check memory usage
- [ ] Set Kube Config file
- [ ] Checking ISTIO
- [ ] Set up CI CD
- [ ] Argo CD


### Useful link
[Add metrics in CIVO](https://www.civo.com/marketplace/metrics-server)

Start Minikube Cluster
```sh
minikube start -n 2 -p local-cluster
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

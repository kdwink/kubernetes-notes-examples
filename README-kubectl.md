
### all

`kubectl get all`

### config

```
kubectl config view

kubectl config set-context --current --namespace <ns-name>
```

### nodes
       
`kubectl get nodes`
                                      
### namespaces

```
kubectl get namespaces
kubectl create namespace <ns-name>
kubectl delete namespace <ns-name>
```

### services

```
kubectl get service
kubectl describe service <service-name>
```
  

### pods

```
kubectl get pod <pod-name>
kubectl get pod -o wide <pod-name>
kubectl get pods
kubectl get pods --watch
```

### deployments

```
kubectl get deployment <deployment-name>
kubectl get deployment -o yaml <deployment-name>

kubectl describe deployment <deployment-name>
```

```
kubectl create deployment nginx-depl --image=nginx
kubectl delete deployment <deployment-name>

kubectl edit-deployment <deployment-name>
```

```
kubectl apply -f <some>-deployment.yaml
kubectl delete -f <some>-deployment.yaml
```

            
### logs

```
kubectl logs <deployment-name>
kubectl logs <pod-name>
kubectl logs <pod-name> --follow
kubectl logs <pod-name> --follow --container <container-name> 
```

### exec
                  
`kubectl exec -it <pod name> -- bash`

### other

`kubectl get replicaset`
`kubectl get secret`


## Reference 

* Main site https://kubernetes.io/
* microk8s: https://microk8s.io/
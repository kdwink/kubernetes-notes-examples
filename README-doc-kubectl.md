
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
kubectl get services --all-namespaces

kubectl get service
kubectl describe service <service-name>
```

### ingress

```
kubectl get ingressclass
kubeclt get ingress

kubectl describe ingress <ingress-name>
```


### pods

```
kubectl get pods
kubectl get pods --all-namespaces

kubectl get pod <pod-name>
kubectl get pod -o wide <pod-name>
kubectl get pods --watch
```
      
### statefulset

```
kubectl scale -n default statefulset postgresql-db --replicas=0
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
     
### storage classes

```
kubectl get storageclasses
kubectl get sc

kubectl describe storageclasses <storage-class-name>
```

### persistent volume claims

```
kubectl get pvc 
kubectl get pvc -o wide

kubectl describe pvc <pvc-name>
```
                               
### physical volumes

```
kubectl get pv
```
 
### config maps

``` 
kubectl get configmaps
kubectl get cm
kubectl get cm <config-map-name> -o yaml

kubectl describe cm <config-map>
```

### logs

```
kubectl logs <deployment-name>
kubectl logs <pod-name>
kubectl logs <pod-name> --follow
kubectl logs <pod-name> --follow --container <container-name> 
```
  
### events

``` 
kubectl get events
```

### exec
                  
`kubectl exec -it <pod name> -- bash`

### other

`kubectl get replicaset`
`kubectl get secret`

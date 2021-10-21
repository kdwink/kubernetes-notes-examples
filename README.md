    # kubernetes

                                     
## kubectl
 
### config

`kubectl config view`
      
### pods

```
kubectl get pod <pod-name>
kubectl get pod -o wide <pod-name>
kubectl get pods
kubectl get pods --watch
```

### get / status
                        
`kubectl get all`

`kubectl get nodes`


```
kubectl get deployment
kubectl get deployment -o yaml
```

`kubectl get service`

`kubectl get replicaset`

`kubectl get secret`

        
### create / edit / delete deployment

`kubectl create deployment nginx-depl --image=nginx`

`kubectl edit-deployment <deployment-name>`

```
kubectl apply -f <some>-deployment.yaml
kubectl delete -f <some>-deployment.yaml
```

`kubectl delete-deployment <deployment-name>`
            
### services

`kubectl describe service <service-name>`
                     
### logs

```
kubectl logs <deployment-name>
kubectl logs <pod-name>
kubectl logs <pod-name> --follow
kubectl logs <pod-name> --follow --container <container-name> 
```

### exec
                  
`kubectl exec -it <pod name> -- bash`


## Reference 

* Main site https://kubernetes.io/
* microk8s: https://microk8s.io/
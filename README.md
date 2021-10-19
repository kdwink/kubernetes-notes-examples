# kubernetes

                                     
## kubectl
 
### config

`kubectl config view`
    
### get / status
                        
`kubectl get all`

`kubectl get nodes`

```
kubectl get pod
kubectl get pod -o wide
```

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

`kubectl logs <deployment-name>`

### exec
                  
`kubectl exec -it <pod name> -- bash`


## Reference 

* Main site https://kubernetes.io/
* microk8s: https://microk8s.io/
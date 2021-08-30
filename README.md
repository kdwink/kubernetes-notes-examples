# kubernetes

                                     
## kubectl
     
### get / status

`kubectl get nodes`

```
kubectl get pod
kubectl get pod -o wide
```

`kubectl get deployment`

`kubectl get service`

`kubectl get replicaset`
        
### create / edit / delete deployment

`kubectl create deployment nginx-depl --image=nginx`

`kubectl edit-deployment <deployment-name>`

`kubectl delete-deployment <deployment-name>`
            
### services

`kubectl describe service <service-name>`
                     
### logs / exec

`kubectl logs <deployment-name>`
                     
`kubectl exec -it <pod name> -- bin/bash`


## Reference 

* Main site https://kubernetes.io/
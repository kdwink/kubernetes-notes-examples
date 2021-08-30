# kubernetes

                                     
## kubectl
     
### get / status

`kubectl get nodes`

`kubectl get pods`

`kubectl get deployment`

`kubectl get service`

`kubectl get replicaset`
        
### create / edit / delete deployment

`kubectl create deployment nginx-depl --image=nginx`

`kubectl edit-deployment <deployment-name>`

`kubectl delete-deployment <deployment-name>`
                                 
### logs / exec

`kubectl logs <deployment-name>`
                     
`kubectl exec -it <pod name> -- bin/bash`


## Reference 

* Main site https://kubernetes.io/
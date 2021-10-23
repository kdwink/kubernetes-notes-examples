# Services
        
## Internal

* **ClusterIP**: Oly accessible from within the cluster.  Cluster DNS resolves the service name to the IP.
                   
## External

* **NodePort**:  Like ClusterIP but ALSO exposes a port (on every node) for access from outside the cluster.
* **LoadBalancer**:  Integrates with external load balancer to provide a single IP or port that proxies to all nodes running the target pods.

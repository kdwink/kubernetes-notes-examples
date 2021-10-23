# Services
        
## Internal

* **ClusterIP**: Oly accessible from within the cluster.  Cluster DNS resolves the service name to the IP.
                   
## External

* **NodePort**:  Like ClusterIP but ALSO exposes a port for access from outside the cluster.
* **LoadBalancer**:

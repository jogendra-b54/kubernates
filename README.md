# kubernates



# Agenda


### Resources :
```
        1) POS
        2) ENV
        3) CMD
        4) ConfigMap
        5) Secret

        6) SETS
            a) ReplicaSets
            b) Deployments
            c) DaemonSets
            d) Stateful Sets

        7) Health Checks
            a) Readiness probe
            b) Liveliness probe
            c) Startup probe
        8) Resouce Utilization ( CPU , Memory , Page)
            a) Requests
            b) Limits
        9) NameSpace    

        10) Services
            a) ClusterIP    ( Limits the visibility of the service only with in the cluster)
            b) LoadBalancer ( Gives the visibility to public , outside of the cluster )
            c) NodePort     ( Opens the port directly on the NODE )
            d) External     ( It's just like a CNAME to long Name to service in the KB Cluster )

       11) Pod Priority & Pre-emption     
 ```

 ### Kubernetes commands    

 Most used Kubernetes commands :

 ```
 * kubectl get nodes  
* kubectl get nodes -o wide
* kubectl cluster-info 
* kubectl api-versions
* kubectl api-resources 
* kubectl --help 
* kubectl describe resource resourceName
* kubectl logs -f podName                   [ when you have a single container in pod ] 
* kubectl logs -f podName -c containerName  [ when you have multiple containers in a pod ] 
 
 ```
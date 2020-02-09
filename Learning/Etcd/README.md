Learning about Etcd.    

https://medium.com/better-programming/a-closer-look-at-etcd-the-brain-of-a-kubernetes-cluster-788c8ea759a5    
Etcd is a crucial component for Kubernetes as it stores the entire state of the cluster: its configuration, specifications, and the statuses of the running workloads.    
Etcd is defined as a distributed, reliable key-value store for the most critical data of a distributed system.       
Etcd is deployed as a cluster, several nodes whose communications are handled by the Raft algorithm.     

<strong> http://thesecretlivesofdata.com/ you can find a great animation explaining how this algorithm operates. </strong>     
<b> the leader election </b>       


<b> the log replications </b>    


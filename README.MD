Cluster delete command

eksctl delete cluster --config-file=eks-config-spot.yaml

kubectl get pods -o wide

kubectl exec -i stress -- bash

Limits and requests 

Service:
----------------------
1. Cluster IP ---> Internal to k8 cluster
2. NodePort ----> 

User --> NODE1:<NODE PORT> --> Cluster IP ---> Container
         NODE2:<NODE PORT> --> Cluster IP ---> Container

3. Load Balancer


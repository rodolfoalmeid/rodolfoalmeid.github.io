## kubctl common commands

export KUBECONFIG=~/.kube/nv-rodolfo-lab1.yaml

kubectl get nodes

kubectl get nodes -o wide

kubectl get pods

kubectl get pods -o wide

kubectl get services

kubectl apply -f <arquivo>

kubectl delete -f <arquivo>

kubectl top <pods>
**requires Metric Server installed to work.

kubectl get service
kubectl edit service <service name>

kubectl version --short
kubectl logs -f <pod name>

change the number of replicas running
kubectl scale deploy neuvector-controller-pod --replicas 0
  
  
   ```tsql
 SELECT *
 FROM sys.tables
 WHERE [name] = 'SomeTable'
 ```

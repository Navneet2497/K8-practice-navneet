$$Pod.yaml$$

81  kubectl create -f pod.yaml (create pods using yaml)

   82  kubectl get pods (to get pods )
   
   83  kubectl delete pod nginx-pod (to delete pod using pod name)
   
   84  kubectl create -f pod.yaml
   
   85  kubectl get pods
   
   86  kubectl describe pod nginx-pod (This is to describe the pod)
   
   87  kubectl edit pod nginx-pod
   
   88  kubectl create -f pod.yaml
   
   89  kubectl delete pod nginx-pod
   
   90  kubectl create -f pod.yaml
   
   91  kubectl get pods

   
   92  cat pod.yaml
   
   93  vi pod.yaml
   
   94  cat pod.yaml
   
   95  kubectl delete pod nginx-pod
   
   96  kubectl create -f pod.yaml
   
   97  kubectl get pods
   
   99  kubectl exec -it nginx-pod -- sh (To get inside the exixting pod)
   
  100  history
  
  101  kubectl run pod --image=nginx --dry-run= -o
  
  102  kubectl run nginx --image=nginx --dry-run=client -o yaml (To dry run the pod with format yaml)
  
  103  kubectl get pod nginx-pod --show-labels (To see the labels in the pods)



  $$Replication_controller$$

  vi replication_controller.yaml
  
  113  kubectl create -f replication_controller.yaml
  
  114  kubectl get pods
  
  115  kubectl get rc
  
 
  118  kubectl get pods --show-labels (To see Labels)
  
  104  kubectl get pods -o wide (To get the details of the pods widely)

  $$Replicaset$$
  
  kubectl create pod replica_set.yaml
  
  121  vi replica_set.yaml
  
  122  kubectl create pod replica_set.yaml
  
  123  kubectl descibe rs
  
  124  kubectl describe rs
  
  125  kubectl explain rs
  
  126  vi replica_set.yaml

  
  127  kubectl create pod replica_set.yaml
  
  128  vi replica_set.yaml
  
  129  kubectl apply -f replica_set.yaml
  
  130  vi replica_set.yaml
  
  131  kubectl apply -f replica_set.yaml
  
  132  vi replica_set.yaml
  
  133  kubectl apply -f replica_set.yaml
  
  134  kubectl get pods
  
  135  kubectl get pods --show-labels
  
 
  139  kubectl get pods -o wide
  
  140  kubectl delete pod rc/nginx-rc
  
  141  kubectl delete rc/nginx-rc
  
  142  kubectl get pods
  
  143  kubectl scale --replicas=4 rs/nginx-rs (to scale the rplicas through commnd)
  
  144  kubectl get pods
  
  145  kubectl delete rs/nginx-rs

  $$deployment$$

  kubectl apply -f deployment.yaml
  151  kubectl get pods
  
  152  kubectl get all
  
  153  kubectl get pods -o wide
  
  154  kuubectl set image deployment/nginx-deploy nginx=nginx:1.9.1
  

  156  kubectl get pods
  
  157  kubectl describe pods
  
  158  kubectl describe pod
  
  159  kubectl describe deploy/nginx-deploy
  
  160  kubectl rollout history deploy/nginx-deploy (History of the changes )
  

  
  162  kubectl rollout undo  deploy/nginx-deploy (changing back to previous version)
  
  163  kubectl describe deploy/nginx-deploy


  

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
  104  kubectl get pods -o wide (To get the details of the pods widely)

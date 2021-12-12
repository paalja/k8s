# k8s
´´´
minikube start --driver=docker
  minikube status

  kubectl --help

  kubectl apply -f config.yaml

  kubectl cluster-info  
  kubectl create -h  
  kubectl create deployment mongo-depl --image=mongo  
  kubectl create deployment nginx-depl --image=nginx  
  kubectl delete deployment nginx-depl  
  kubectl describe pod mongo-depl-5fd6b7d4b4-mwtf6  
  kubectl edit deployment nginx-depl  
  kubectl exec  
  kubectl exec -it mongo-depl-5fd6b7d4b4-mwtf6 -- bin/bash  
  kubectl get deployment  
  kubectl get deployment nginx-deployment -o yaml  
  kubectl get nodes  
  kubectl get pod  
  kubectl get pod -o wide  
  kubectl get replicaset  
  kubectl get services  
  kubectl logs mongo-depl-5fd6b7d4b4-mwtf6  
  kubectl logs nginx-depl-7fc44fc5d4-fgqqq  
  kubectl version  
´´´

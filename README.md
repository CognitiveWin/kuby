# kuby

## Commands

kubectl version
kubectl config get-contexts
kubectl cluster-info
kubectl get nodes
kubectl create -f https://raw.githubusercontent.com/kubernetes/dashboard/master/src/deploy/recommended/kubernetes-dashboard.yaml
kubectl get pod --namespace=kube-system | grep dashboard
kubectl run hello-nginx --image=nginx --port=80
kubectl describe pod hello-nginx-6f9f4fc7dd-ks2gc
kubectl get deployments
kubectl expose deployment hello-nginx --type=NodePort
kubectl get services

## References

https://developer.ibm.com/patterns/deploy-a-react-application-on-kubernetes/

https://matthewpalmer.net/kubernetes-app-developer/articles/guide-install-kubernetes-mac.html
https://docs.docker.com/docker-for-mac/#kubernetes
https://rominirani.com/tutorial-getting-started-with-kubernetes-with-docker-on-mac-7f58467203fd
https://medium.com/@thms.hmm/docker-for-mac-with-kubernetes-enable-k8s-dashboard-62fe036b7480

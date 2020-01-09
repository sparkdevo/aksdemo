# aksdemo
$ kubectl apply -f nick-aks-disk.yaml    
$ kubectl apply -f nick-aks-nginx.yaml    

对于 nick-aks-gowebdemo2.yaml，需要先执行下面的命令：    
kubectl create configmap nginx-config --from-file=./nginx.conf    
# kubectl delete configmap nginx-config
kubectl create configmap test-config --from-file=./nginx.conf    
kubectl create configmap test1-config --from-file=./conf.d/    
kubectl create configmap test2-config --from-file=./conf.crt/    

kubectl create -f .\docker-spring-boot-v2-d.yml
kubectl create -f .\docker-spring-boot-v2-s.yml



--------------------------------------------------------

kubectl create -f .\docker-spring-boot-v1-d.yml
kubectl create -f .\docker-spring-boot-v1-s.yml

kubectl delete -f .\docker-spring-boot-v1-d.yml
kubectl delete -f .\docker-spring-boot-v1-s.yml

-------------------------------------------------------

kubectl delete -f .\mongo-deployment.yml
kubectl delete -f .\mongo-service.yml
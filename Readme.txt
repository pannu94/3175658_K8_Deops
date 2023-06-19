Name: Omprakash Singh Tomar
Id: 3175658
----------------------------------------------------------------------

YAML's file and API code url
URL: 
https://github.com/pannu94/3175658_K8_Deops
----------------------------------------------------------------------

Docker hub image url
https://hub.docker.com/repository/docker/pannu94/node/general
----------------------------------------------------------------------

API endpoints
Get data                 (get operation): /list
First time / create data (get operation): /create
----------------------------------------------------------------------

YAML's file, please execute in same sequence

kubectl apply -f storageClass.yaml

kubectl apply -f mongodb.pvc.yaml

kubectl apply -f mongodb.secret.yaml

kubectl apply -f nodejs.configmap.yaml

kubectl apply -f mongodb.statefulset.yaml

kubectl apply -f mongodb.service.yaml

kubectl apply -f nodejs.deployment.yaml

kubectl apply -f nodejs.service.yaml

# conversao-temperatura



Devido ao meu CI e minha imagem está pública, você consegue utilizar esse container com docker run ou pull.

#Docker

$  docker container run -d --name conversao-temperatura --restart=always -p 8000:8080 ghcr.io/claudi0s0uza/conversao-temperatura

#Kubernetes

$  kubectl create -f pod-convTemp.yaml 

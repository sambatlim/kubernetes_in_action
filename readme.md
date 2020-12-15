## to apply to kubernetes

```
kubectl apply -f node-app-deployment.yaml -f node-app-service.yaml

```

## delete serevice or deployment

```

kubectl delete service node-app-service
kubectl delete deployment node-app-deployment

```

## get deployment or service

```
kubectl get service
kubectl get deployment

```

## get service expose port

```

minikube service node-app-service

```

## to check docker env

```

minikube docker-env

```

## to build docker

```

docker build . -t username/repo:1.0

```

## to login to docker hub

```

docker login

```

## to push to docker hub

```

docker push

```
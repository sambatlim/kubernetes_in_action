## To apply to kubernetes

```

kubectl apply -f node-app-deployment.yaml -f node-app-service.yaml

```

## To delete service or deployment

```

kubectl delete service node-app-service
kubectl delete deployment node-app-deployment

```

## To get deployment or service

```
kubectl get service
kubectl get deployment

```

## To expose service port

```

minikube service node-app-service

```

## To check docker env

```

minikube docker-env

```

## To build docker

```

docker build . -t username/repo:1.0

```

## To login to docker hub

```

docker login

```

## To push to docker hub

```

docker push

```

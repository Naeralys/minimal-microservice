# User Api service

### Build and update minikube

First you have to set the docker environment for minikube vm.

```
eval $(minikube docker-env)
```

Building the docker image locally will now make it available for minikube vm to pull it.

```
docker build . --tag user-api
```

You can now update with kubectl apply command. Make sure you set a unique tag so that it will recognize the new image and pull it.

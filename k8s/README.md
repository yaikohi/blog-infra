# Commands

Make sure that minikube uses the docker-daemon by running:

```bash
eval $(minikube docker-env)
```

Build the image:
```bash
docker build -t USERNAME/REPO:VERSION
```

Run:
```bash
kubectl apply -f infra/k8s
```



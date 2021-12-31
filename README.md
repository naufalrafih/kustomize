# kustomize
Getting started with kustomize <br>
Step by step:

1. Check manifest for each environment <br>
```kustomize build base``` <br>
```kustomize build overlays/dev``` <br>
```kustomize build overlays/prod``` <br>

2. Apply manifest to the Kubernetes cluster <br>
```kubectl apply -k base``` <br>
```kubectl apply -k overlays/dev``` <br>
```kubectl apply -k overlays/prod```

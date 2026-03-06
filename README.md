# Kubernetes Manifests

Kubernetes YAML configurations for deploying and managing containerized applications.

## Structure
├── pods/
│ └── pod.yaml
├── replicasets/
│ └── replicaset.yaml
├── deployments/
│ └── deployment.yaml
├── services/
│ ├── clusterip-service.yaml
│ ├── nodeport-service.yaml
│ └── loadbalancer-service.yaml
└── README.md

## Usage

### Pods
```bash
kubectl apply -f pods/pod.yaml
kubectl get pods
ReplicaSets
bash
kubectl apply -f replicasets/replicaset.yaml
kubectl get replicaset
Deployments
bash
kubectl apply -f deployments/deployment.yaml
kubectl get deployments
kubectl rollout status deployment/nginx-deployment
Services
bash
kubectl apply -f services/
kubectl get services
Access NodePort
bash
minikube service nginx-nodeport --url

Author
Sagar

License
MIT License - feel free to use and modify.

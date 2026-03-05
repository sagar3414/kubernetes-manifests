# Kubernetes Manifests

Kubernetes YAML configurations for learning K8s concepts.

## Structure
├── pods/
│ └── pod.yaml
├── replicasets/
│ └── replicaset.yaml
└── README.md

## Usage

```bash
kubectl apply -f pods/pod.yaml
kubectl apply -f replicasets/replicaset.yaml
kubectl get pods
Cleanup
bash
kubectl delete -f pods/
kubectl delete -f replicasets/
Author
Sagar 

License
MIT License - feel free to use and modify

kubectl apply -f .\configmap.yaml
kubectl apply -f .\deployment.yaml
kubectl apply -f .\svc.yaml

docker compose up -d

localhost
localhost:30007
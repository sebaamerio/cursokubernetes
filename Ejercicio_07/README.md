kubectl create namespace ejercicio7

kubectl -n ejercicio7 apply -f configmap-env.yaml
kubectl -n ejercicio7 apply -f deployment.yaml

kubectl -n ejercicio7 describe configmaps
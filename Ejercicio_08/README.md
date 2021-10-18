kubectl create namespace cursokubernetes

kubectl -n cursokubernetes apply -f configmap.yaml

kubectl -n cursokubernetes apply -f deployment.yaml

#To Deploy Prometheus using helm chart
helm install my-prometheus ./prometheus

#To access the prometehus on local system
kubectl port-forward svc/prometheus-server 9090:9090 -n <namespace>


# GrafanaKuber
This Project explains the Grafana setup on a Kubernetes cluster. You can create dashboards on Grafana for all the Kubernetes metrics through prometheus.
#Create the configmap using the following command.
kubectl create -f grafana-datasource-config.yaml
#Create the deployment
kubectl create -f deployment.yaml
#Create the service.
kubectl create -f service.yaml
##Setup Kubernetes Dashbaords
import 
https://grafana.com/grafana/dashboards/8588

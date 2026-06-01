# Healthcare DevOps CI/CD Project

## Project Overview

This project demonstrates an end-to-end DevOps CI/CD pipeline for deploying a healthcare application using Jenkins, Docker, Kubernetes, Prometheus, Grafana, Ansible and AWS.

## Tools Used

* Jenkins
* Docker
* Kubernetes
* AWS EC2
* Ansible
* Prometheus
* Grafana
* GitHub
* Maven

## Architecture

GitHub → Jenkins → Maven Build → Docker → Docker Hub → Kubernetes → Prometheus → Grafana

## Workflow

1. Source code pushed to GitHub
2. Jenkins pipeline triggered
3. Maven builds the application
4. Docker image created and pushed to Docker Hub
5. Kubernetes deploys application
6. Prometheus collects metrics
7. Grafana visualizes monitoring dashboards

## Screenshots
### Architecture
![Healthcare Architecture](Healthcare_Architecture.png)

### Jenkins Pipeline

![Jenkins Pipeline](Jenkins-Build-Success.png)

### Kubernetes Deployment

![Kubernetes Pods](kubernetes-pod.png)

### Prometheus Monitoring

![Prometheus](Prometheus_Monitor.png)

### Grafana Dashboard

![Grafana](Grafana_Monitor.png)

## Troubleshooting

### Jenkins Build Failure

* Checked Jenkins console logs
* Verified Maven dependencies
* Fixed configuration issues

### Kubernetes Pod Failure

Commands used:

kubectl get pods

kubectl describe pod <pod-name>

kubectl logs <pod-name>

### Monitoring Issue

* Verified Prometheus targets
* Verified node_exporter running
* Checked Grafana datasource configuration

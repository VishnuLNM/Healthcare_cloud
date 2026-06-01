# Healthcare_cloud

## Project Overview

This project demonstrates an end-to-end DevOps CI/CD pipeline for deploying a healthcare application using Terraform, Ansible, Jenkins, Docker, Kubernetes, Prometheus and Grafana.

## Tools Used

- Terraform
- AWS EC2
- Ansible
- Jenkins
- Docker
- Kubernetes
- Prometheus
- Grafana

## Architecture

GitHub → Jenkins → Maven → Docker → Docker Hub → Kubernetes → Monitoring

## Workflow

1. Terraform provisions infrastructure
2. Ansible installs dependencies
3. Jenkins pipeline builds application
4. Docker image created and pushed
5. Kubernetes deploys containerized app
6. Prometheus monitors infrastructure
7. Grafana dashboards visualize metrics

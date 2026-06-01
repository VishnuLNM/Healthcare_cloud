# Troubleshooting

## Jenkins Build Failure
- Checked Jenkins console logs
- Verified Maven dependencies
- Fixed syntax/configuration issues

## Docker Container Issue
- Checked container logs
- Verified image build
- Checked exposed ports

## Kubernetes Pod Failure
Commands used:

kubectl get pods
kubectl describe pod <pod_name>
kubectl logs <pod_name>

## Monitoring Issue
- Checked Prometheus targets
- Verified node exporter running
- Verified Grafana datasource

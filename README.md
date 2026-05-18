# EMS Helm Chart

Helm chart for Employee Management System (EMS) application.

## Installation

```bash
helm install ems ./ems-helm-chart
```

## Configuration

Key configuration values in `values.yaml`:

- `replicaCount`: Number of EMS application replicas
- `image.repository`: Docker image repository
- `image.tag`: Docker image tag
- `service.type`: Kubernetes service type
- `postgres.enabled`: Enable/disable PostgreSQL deployment

## Uninstall

```bash
helm uninstall ems
```

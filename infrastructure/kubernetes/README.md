# Kubernetes

Manifiestos y configuración de despliegue en Kubernetes.

## Ejemplo de estructura

```
kubernetes/
├── base/
│   ├── deployment.yaml
│   ├── service.yaml
│   └── ingress.yaml
└── overlays/
    ├── dev/
    ├── staging/
    └── prod/
```

## Principios

- Configuración gestionada con Kustomize u Helm.
- Health checks (`liveness`/`readiness`) obligatorios en cada despliegue.
- Autoescalado horizontal basado en CPU/memoria.

> Placeholder de ejemplo. Los manifiestos reales se agregarán conforme se despliegue cada servicio.

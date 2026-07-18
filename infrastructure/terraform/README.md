# Terraform

Infraestructura como código para el aprovisionamiento en la nube.

## Ejemplo de recursos gestionados

- Redes (VPC, subredes).
- Clusters de Kubernetes.
- Bases de datos gestionadas.
- Buckets de almacenamiento.

## Estructura sugerida (ejemplo)

```
terraform/
├── modules/
│   ├── network/
│   ├── database/
│   └── kubernetes/
├── environments/
│   ├── dev/
│   ├── staging/
│   └── prod/
└── main.tf
```

> Placeholder de ejemplo. Los módulos reales se agregarán conforme se defina la infraestructura.

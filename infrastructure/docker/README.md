# Docker

Definiciones de contenedores para desarrollo local y despliegue.

## Ejemplo

```
docker/
├── Dockerfile.backend
├── Dockerfile.frontend
└── docker-compose.yml
```

## docker-compose.yml (ejemplo)

```yaml
version: "3.9"
services:
  api:
    build: ./backend
    ports:
      - "3000:3000"
  web:
    build: ./frontend
    ports:
      - "3001:3000"
  db:
    image: postgres:16
    environment:
      POSTGRES_PASSWORD: example
```

> Placeholder de ejemplo. Los Dockerfiles reales se agregarán conforme se implementen los servicios.

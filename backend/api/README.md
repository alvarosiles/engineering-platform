# API

Capa de exposición pública de los servicios del backend (API Gateway / BFF).

## Ejemplo de endpoints

| Método | Ruta | Descripción |
|---|---|---|
| POST | `/api/v1/auth/login` | Autenticación de usuarios |
| GET | `/api/v1/users/me` | Obtiene el perfil del usuario autenticado |
| GET | `/api/v1/services` | Lista los servicios disponibles |
| POST | `/api/v1/contact` | Envía un formulario de contacto |

## Stack propuesto

- Node.js / Express o .NET
- Autenticación con JWT
- Documentación con OpenAPI/Swagger

> Placeholder de ejemplo. La implementación real se agregará en próximas iteraciones.

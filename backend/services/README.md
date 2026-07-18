# Services

Servicios internos de negocio (microservicios), consumidos a través de la [API](../api).

## Servicios de ejemplo

- `users-service` — gestión de usuarios y autenticación.
- `payments-service` — procesamiento de pagos y facturación.
- `notifications-service` — envío de emails y notificaciones.

## Principios

- Cada servicio es independiente y tiene su propia base de datos lógica.
- Comunicación entre servicios vía eventos o llamadas HTTP internas.
- Cada servicio expone métricas y health checks.

> Placeholder de ejemplo. Los servicios reales se agregarán conforme avance el desarrollo.

# Guía de Seguridad

## Principios

- Seguridad desde el diseño ("Security by design"), no como paso final.
- Principio de mínimo privilegio en accesos y credenciales.
- Nunca almacenar secretos en el código fuente (usar variables de entorno o vaults).

## Prácticas obligatorias

- Validar y sanear toda entrada de usuario (prevención de XSS, SQL Injection).
- Usar HTTPS en todos los entornos, incluido desarrollo cuando sea posible.
- Autenticación con tokens de vida corta y renovación segura (refresh tokens).
- Cifrado de datos sensibles en tránsito y en reposo.

## Revisión y auditoría

- Escaneo de dependencias vulnerables en cada Pull Request.
- Auditorías de seguridad periódicas (ver [security/audits](../../security/audits)).
- Pruebas de penetración antes de lanzamientos mayores.

## Cumplimiento

- Alineado con OWASP Top 10.
- Buenas prácticas de manejo de datos personales (privacidad por diseño).

# Architecture Decision Records (ADR)

Registro histórico de decisiones arquitectónicas importantes del proyecto.

---

## ADR-001: Uso de arquitectura de microservicios

**Estado:** Aceptado
**Fecha:** 2026-01-15

**Contexto:** Necesitamos que cada equipo (backend, mobile, data) pueda desplegar de forma independiente.

**Decisión:** Adoptar una arquitectura de microservicios con un API Gateway como punto de entrada único.

**Consecuencias:** Mayor complejidad operativa, pero mejor escalabilidad y autonomía por equipo.

---

## ADR-002: Next.js como framework de frontend

**Estado:** Aceptado
**Fecha:** 2026-02-03

**Contexto:** Se requiere buen SEO, rendimiento y developer experience para el sitio corporativo y el web-app.

**Decisión:** Usar Next.js + TypeScript + Tailwind CSS.

**Consecuencias:** Curva de aprendizaje moderada, pero renderizado híbrido (SSR/SSG) mejora SEO y performance.

---

## ADR-003: Infraestructura como código con Terraform

**Estado:** Aceptado
**Fecha:** 2026-02-20

**Contexto:** Se necesita reproducibilidad y control de versiones sobre la infraestructura cloud.

**Decisión:** Toda la infraestructura se define en Terraform, versionada en `infrastructure/terraform`.

**Consecuencias:** Cambios de infraestructura pasan por revisión de código, igual que el software.

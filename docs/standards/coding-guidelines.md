# Guía de Estándares de Código

## Principios generales

- Código legible antes que código "inteligente".
- Nombres de variables y funciones descriptivos, en inglés.
- Funciones pequeñas con una única responsabilidad.
- Evitar duplicación (DRY) sin caer en abstracciones prematuras.

## Frontend

- TypeScript estricto (`strict: true`).
- Componentes funcionales con hooks.
- Estilos con Tailwind CSS, sin CSS inline salvo casos puntuales.

## Backend

- Arquitectura en capas (controller → service → repository).
- Validación de entradas en el borde del sistema.
- Manejo explícito de errores, sin silenciar excepciones.

## Control de versiones

- Commits siguiendo [Conventional Commits](https://www.conventionalcommits.org/).
- Ramas descriptivas: `feature/`, `fix/`, `chore/`.
- Pull Requests pequeños y enfocados en un solo cambio.

## Pruebas

- Cobertura mínima recomendada: 80% en lógica de negocio.
- Pruebas unitarias obligatorias para nuevas funcionalidades.
- Pruebas de integración para flujos críticos.

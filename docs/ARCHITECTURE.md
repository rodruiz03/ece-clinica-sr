# Arquitectura del Sistema — ECE Clínica San Rafael

## Visión general
ECE se implementa como una aplicación web de 3 capas:

1. **Frontend** — React (SPA), consumida por personal médico, recepción y administración.
2. **Backend** — API REST en Node.js/Express, encargada de la lógica de negocio, autenticación
   y acceso a datos.
3. **Base de datos** — PostgreSQL (AWS RDS), almacenamiento relacional de pacientes,
   consultas e historial clínico, con backups automáticos y cifrado en reposo.

## Componentes principales
- `backend/src/controllers` — controladores de las APIs REST.
- `backend/src/models` — esquemas/entidades de la base de datos.
- `backend/src/middleware` — autenticación, autorización y logging.
- `backend/src/routes` — definición de endpoints.
- `frontend/src/pages` y `frontend/src/components` — vistas y componentes reutilizables.

## Infraestructura
- Despliegue en AWS (con alternativa en Azure documentada en `infra/azure/`).
- CI/CD mediante GitHub Actions: tests → build → despliegue a staging → producción.
- Monitoreo con CloudWatch (logs, métricas, alertas).

## Referencia
Ver detalle completo de decisiones de arquitectura y planificación en el
Laboratorio 2 del curso.

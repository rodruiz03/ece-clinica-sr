# ECE - Expediente Clínico Electrónico | Clínica San Rafael

## Nombre del proyecto
Sistema de Expediente Clínico Electrónico (ECE) para Clínica San Rafael

## Descripción
ECE es una plataforma web que digitaliza la gestión médica de la Clínica San Rafael:
expedientes de pacientes, historial clínico, registro de consultas y disponibilidad
de información en tiempo real para el personal médico y administrativo. Reemplaza el
manejo actual en papel/hojas de cálculo, centralizando la información en una base de
datos segura y accesible desde cualquier punto de atención.

## Objetivo
Reducir los tiempos de atención al paciente, permitir la disponibilidad simultánea de
los expedientes para varios usuarios, y garantizar la seguridad y trazabilidad de los
datos médicos, cumpliendo con buenas prácticas de protección de información sensible.

## Integrantes
| Nombre | Carné | Rol |
|---|---|---|
| Rodrigo José Ruiz Juárez | 1037623 | Backend Lead |
| Mario Miguel Arévalo Pérez | 1072123 | DevOps / Infraestructura |
| Diego Alejandro López de Paz | 1136423 | Arquitecto / Project Manager |

## Herramientas principales
| Herramienta | Propósito |
|---|---|
| GitHub | Control de versiones, revisión de código (PRs), CI/CD |
| GitHub Projects | Tablero de tareas y seguimiento del proyecto |
| Figma | Diseño de wireframes e interfaz (UI/UX) |
| VSCode | Entorno de desarrollo (backend y frontend) |
| Jest | Pruebas unitarias |
| Playwright | Pruebas end-to-end |
| AWS RDS PostgreSQL | Base de datos relacional |
| CloudWatch | Monitoreo y observabilidad |
| Slack | Comunicación del equipo |

## Estado del proyecto
🚧 En desarrollo — Fase actual: **Laboratorio 3 (Ecosistema de herramientas)**

- [x] Laboratorio 1 — Oportunidad de software
- [x] Laboratorio 2 — Planificación, análisis y diseño
- [x] Laboratorio 3 — Repositorio, estructura y tablero de trabajo
- [ ] Desarrollo del MVP

## Estructura del repositorio
```
ece-clinica-sr/
├── backend/     # APIs REST (Node.js/Express)
├── frontend/    # Aplicación web (React)
├── infra/       # Infraestructura como código (AWS/Azure)
├── docs/        # Documentación centralizada (arquitectura, requerimientos, ADRs)
└── .github/     # Workflows de CI/CD
```

## Inicio rápido
```bash
git clone https://github.com/rodruiz03/ece-clinica-sr.git
cd ece-clinica-sr

# Backend
cd backend && npm install && npm run dev

# Frontend
cd ../frontend && npm install && npm start
```

## Licencia
Ver [LICENSE](LICENSE).

# Requerimientos — ECE Clínica San Rafael

> Documento base. El detalle completo de requerimientos funcionales (RF) y no
> funcionales (RNF) se definió en el Laboratorio 2 y se irá enlazando a Issues
> de GitHub conforme se implementen.

## Requerimientos funcionales (resumen)
- RF001 — Registrar y consultar el expediente clínico de un paciente.
- RF002 — Búsqueda de pacientes por nombre, documento o número de expediente.
- RF003 — Registro de consultas médicas y diagnóstico.
- RF004 — Gestión de citas y disponibilidad de médicos.
- RF005 — Control de acceso por rol (médico, recepción, administrador).

## Requerimientos no funcionales (resumen)
- RNF-001 — Disponibilidad del sistema 99.5% (SLA).
- RNF-002 — Cifrado de datos sensibles en tránsito y en reposo.
- RNF-003 — Tiempo de respuesta de búsqueda de pacientes < 2 segundos.
- RNF-004 — Trazabilidad (audit trail) de todos los cambios sobre un expediente.
- RNF-005 — Escalabilidad para atender múltiples usuarios simultáneos.

## Trazabilidad
Cada RF/RNF se vinculará a un Issue en GitHub y a las tareas correspondientes
en el tablero del proyecto (GitHub Projects).

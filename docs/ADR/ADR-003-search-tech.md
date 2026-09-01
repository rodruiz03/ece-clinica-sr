# ADR-003: Tecnología de búsqueda de pacientes

**Estado:** Aceptado
**Fecha:** 2026-08-31

## Contexto
RNF-003 exige que la búsqueda de pacientes responda en menos de 2 segundos.

## Decisión
Usar índices nativos de PostgreSQL (B-tree / índices de texto) sobre las
columnas de búsqueda frecuente (nombre, documento, número de expediente),
evaluando en fases posteriores una solución dedicada (p. ej. Elasticsearch)
solo si el volumen de datos lo justifica.

## Consecuencias
- Menor complejidad operativa para el MVP.
- Debe monitorearse el rendimiento de búsqueda en producción (CloudWatch).

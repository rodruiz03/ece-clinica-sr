# ADR-002: Método de autenticación

**Estado:** Aceptado
**Fecha:** 2026-08-31

## Contexto
El sistema maneja datos médicos sensibles y requiere control de acceso por rol
(médico, recepción, administrador).

## Decisión
Autenticación basada en JWT (JSON Web Tokens), con expiración corta y
renovación mediante refresh token. Roles y permisos gestionados en middleware
del backend.

## Consecuencias
- Autenticación sin estado (stateless), escalable horizontalmente.
- Necesario definir política de expiración/revocación de tokens.

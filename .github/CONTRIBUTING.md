# Guía de contribución

## Flujo de trabajo (Git)
1. Crear una rama a partir de `develop`: `git checkout -b feature/nombre-corto`.
2. Realizar commits pequeños y descriptivos.
3. Abrir un Pull Request hacia `develop`, enlazando el Issue correspondiente
   (`Closes #<numero>`).
4. Esperar revisión de al menos un integrante del equipo antes de mergear.

## Estándar de mensajes de commit
Se sigue el formato [Conventional Commits](https://www.conventionalcommits.org/):

```
<tipo>: <descripción corta>

<cuerpo opcional>
```

Tipos usados: `feat`, `fix`, `docs`, `chore`, `test`, `refactor`.

## Checklist de revisión de PR
- [ ] El código compila y pasa los tests (`npm test`).
- [ ] Se agregaron/actualizaron tests para el cambio.
- [ ] La documentación relevante fue actualizada (`docs/`).
- [ ] El PR está vinculado a un Issue.

## Proceso de despliegue
`main` → despliegue automático a producción vía GitHub Actions.
`develop` → despliegue automático a staging vía GitHub Actions.

# Laboratorio CI/CD - Estudiantes

Aplicación JavaScript para calcular el promedio de tres notas (0 a 20) y determinar si el estudiante está APROBADO (promedio >= 11) o DESAPROBADO.

## Requisitos
- Node.js 22
- Git y cuenta de GitHub para ejecutar GitHub Actions

## Ejecutar pruebas
```bash
npm install
npm test
```

## CI/CD
El workflow `.github/workflows/ci.yml` verifica las cinco pruebas al hacer push o pull request a `main`. Tras un push exitoso, genera el artefacto `proyecto-estudiantes` con `src/` y `package.json`.

**Importante:** El artefacto no implica despliegue real en producción.

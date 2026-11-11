# Cómo trabajamos

## Repos

Nombre en minúscula con guiones: `proyecto-componente` (ej. `agendamiento-backend`). La rama principal es `main`. Cada repo lleva un README con lo necesario para levantarlo en local.

## Ramas

- `feature/nombre-corto` para funcionalidades
- `fix/nombre-corto` para errores
- `hotfix/nombre-corto` para urgencias en producción
- `chore/nombre-corto` para dependencias, configuración, etc.

## Commits

Formato `tipo: descripción`, en minúscula:

    feat: filtro de citas por especialidad
    fix: validación de fechas en el agendamiento
    chore: actualiza spring boot a 3.3

Tipos: `feat`, `fix`, `refactor`, `docs`, `chore`, `test`.

## Pull requests

1. Rama desde `main` actualizado.
2. PR hacia `main` con la plantilla llena.
3. Mínimo una aprobación de un líder técnico.
4. Merge y se borra la rama.

## Secretos

Nada de contraseñas, tokens ni archivos `.env` en el repo. Si se sube uno por error, avisar de una vez al líder técnico para cambiarlo; borrarlo en otro commit no es suficiente.

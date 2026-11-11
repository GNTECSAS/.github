# Guía de contribución — GnTec S.A.S.

## Repositorios

- Nombres en minúscula y con guiones: `proyecto-componente` (ej. `agendamiento-backend`, `agendamiento-frontend`).
- La rama principal es siempre `main`.
- Todo repositorio debe tener un `README.md` con descripción, requisitos y cómo ejecutarlo.

## Ramas

| Prefijo     | Uso                                   | Ejemplo                        |
|-------------|---------------------------------------|--------------------------------|
| `feature/`  | Funcionalidad nueva                   | `feature/agenda-por-medico`    |
| `fix/`      | Corrección de errores                 | `fix/validacion-fechas`        |
| `hotfix/`   | Corrección urgente en producción      | `hotfix/caida-login`           |
| `chore/`    | Configuración, dependencias, limpieza | `chore/actualizar-spring-boot` |

## Commits

Usamos [Conventional Commits](https://www.conventionalcommits.org/es/):

```
feat: agrega filtro de citas por especialidad
fix: corrige cálculo de disponibilidad
docs: actualiza instrucciones de despliegue
refactor: separa servicio de notificaciones
chore: actualiza dependencias
```

## Flujo de trabajo

1. Crea tu rama desde `main` actualizada.
2. Haz commits pequeños y descriptivos.
3. Abre un pull request hacia `main` usando la plantilla.
4. Espera la revisión de un líder técnico antes de hacer merge.
5. Borra la rama después del merge.

## Seguridad

- Nunca subas contraseñas, tokens, llaves ni archivos `.env`.
- Usa variables de entorno o los secretos del repositorio.
- Si subiste un secreto por error, avisa de inmediato al líder técnico para rotarlo.

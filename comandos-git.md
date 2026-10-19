# Comandos básicos de Git

- `git pull`: descarga los cambios del repositorio remoto y los integra en la rama local actual. Normalmente combina `fetch` y `merge`; la integración puede usar `rebase` si está configurado así.
- `git push`: publica en el repositorio remoto los commits locales de la rama actual.
- `git status`: muestra la rama actual y qué archivos tienen cambios sin preparar, preparados para commit o todavía sin seguimiento.
- `git branch`: lista las ramas locales. También permite crear ramas, por ejemplo `git branch nombre-de-rama`.
- `git remote`: muestra o gestiona los nombres de los repositorios remotos asociados. `git remote -v` muestra también sus direcciones.

## Flujo practicado

```bash
git status
git add ejemplo.py comandos-git.md
git commit -m "Documentar comandos de Git"
git push
```

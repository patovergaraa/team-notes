# Guía para contribuir

## Flujo de trabajo
- Ramas:
  - `main`: estable
  - `develop`: integración
  - `feature/<id>-<desc>`: desarrollo de issues
  - `release/x.y.z`: preparación de releases

## Commits
Usar prefijos:
- `feat:` nueva funcionalidad
- `fix:` corrección de bug
- `docs:` documentación
- `test:` pruebas
- `chore:` tareas menores
- `refactor:` cambios internos sin modificar comportamiento

## Pull Requests
- Cada issue se desarrolla en su propia rama feature.
- Se abre PR hacia `develop`.
- Se requiere al menos 1 review.
- Merge con **Squash & Merge**.

## Antes de subir cambios
1. Correr los tests:
```bash
python3 -m pytest -q

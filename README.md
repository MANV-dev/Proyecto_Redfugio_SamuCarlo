# Metodología de trabajo

## Ramas
- `main`: rama principal y estable del proyecto. Solo recibe código revisado y validado.
- Cada integrante trabaja en su propia subrama, creada a partir de `main`:
  - `yo`: rama de Samu.
  - `tu`: rama de Carlos.
- `main` no se modifica directamente; todos los cambios pasan por la subrama correspondiente.

## Commits semanales
- Cada integrante realiza **un commit por semana** en su subrama, como mínimo, con los avances realizados durante ese periodo.
- Los mensajes de commit deben describir de forma clara el cambio realizado.

## Integración en main
1. Al final del ciclo de trabajo, ambos integrantes comparan sus subramas (`yo` y `tu`) para revisar el código, detectar conflictos y verificar que todo funciona correctamente.
2. Una vez revisadas y resueltas las diferencias, las dos subramas se fusionan (*merge*) en `main`.

## Reparto del trabajo
- El trabajo se reparte de forma equitativa entre los dos integrantes.
- Para el reparto se tienen en cuenta las fortalezas y debilidades de cada uno, asignando las tareas según la experiencia y los puntos fuertes de cada persona, y apoyándose mutuamente en las áreas de mayor dificultad.

## Organización con GitHub Issues
- Las tareas se gestionan mediante **GitHub Issues**, organizadas en un tablero de trabajo (*GitHub Projects*).
- Cada tarea se crea como un issue y se identifica con las siguientes etiquetas:
  - **Tipo de tarea**: una etiqueta por cada tipo de tarea (por ejemplo, `backend`, `frontend`, `base-de-datos`, `documentación`, `pruebas`).
  - **Responsable**: indica quién está trabajando en la tarea (`samu` o `carlos`).
  - **Esfuerzo**: valoración del 0 al 10 de cuánto trabajo ha costado realizar la tarea.

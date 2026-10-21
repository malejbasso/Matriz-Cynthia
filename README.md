# Matriz de comunicación

Réplica de uso interno del cuestionario de la Communication Matrix (Charity Rowland), por etapas. Genera la matriz en PDF, un dashboard en PDF y exporta a Excel.

## Flujo de datos
- Los datos viven en `matrices.json`, en la raíz de este repositorio.
- **Para registrar o corregir evaluaciones:** clonar el repo, abrir `index.html` con Chrome o Edge, pulsar **Elegir carpeta** y elegir la carpeta clonada. La app escribe en `matrices.json`; después hacer `git commit` y `git push`.
- **Para solo consultar online:** abrir la URL de GitHub Pages; la app carga `matrices.json` del sitio si el navegador aún no tiene datos.
- Una página web no puede escribir en el repositorio por sí sola: el `push` es manual.

## Privacidad
`matrices.json` contiene nombres y diagnósticos de menores. Usar un repositorio **privado** y limitar el acceso.

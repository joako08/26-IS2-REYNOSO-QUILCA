# Préstamos de equipos  Aplicación para Ingeniería de Software II

Miniaplicación estática para la actividad individual de aseguramiento de calidad de software. No usa base de datos ni servidor, guarda los registros en el navegador mediante `localStorage`.

## Funcionalidad inicial

- Registra un préstamo de un equipo disponible.
- Evita registrar datos incompletos, una fecha de devolución anterior a la fecha de préstamo y el préstamo simultáneo del mismo equipo.
- Muestra los préstamos y permite registrar la devolución.
- Conserva los datos del navegador mientras no se restablezcan desde la aplicación.

## Inicio rápido

1. Copie esta carpeta a su repositorio individual o use el repositorio base como plantilla.
2. Abra `index.html` en el navegador para probarla localmente.
3. Implemente únicamente la mejora asignada en su ficha.
4. Registre dos casos de prueba en la sección final de este README.
5. Publique la aplicación en GitHub Pages y proporcione los enlaces solicitados.

## Archivos principales

- `index.html`: estructura y controles de la aplicación.
- `style.css`: diseño visual.
- `app.js`: catálogo, registros, validaciones y almacenamiento local.

## Casos de prueba de mi mejora

Reemplace esta tabla por los dos casos de su asignación. Incluya una captura por caso en el repositorio o muestre ambas pruebas en el video.

| Caso | Datos de entrada / acción | Resultado esperado | Resultado obtenido | Estado |
|---|---|---|---|---|
| CP-01: caso válido | Se registró un préstamo con Solicitante: "Joaquin Reynoso" (equipo y fechas válidas). Acción: clic en "Registrar préstamo", luego recargar la página (F5). | El campo "Solicitante" debe mostrar "Joaquin Reynoso" automáticamente al recargar, sin que el usuario lo escriba de nuevo. | Al recargar la página, el campo "Solicitante" mostró "Joaquin Reynoso" precargado correctamente. | Aprobado |
| CP-02: caso límite o inválido | Se limpió el localStorage del sitio (borrado manual desde DevTools) y se abrió la aplicación. | El campo "Solicitante" debe aparecer vacío, sin errores en consola. | El campo "Solicitante" apareció vacío y la aplicación cargó con normalidad. | Aprobado |

## Entrega

- URL del repositorio individual.
- URL pública de GitHub Pages.
- README actualizado con los dos casos de prueba.

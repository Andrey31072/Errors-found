# Tablero de tareas — Análisis UX (perspectiva de usuario)

**Fecha:** 26 de mayo de 2026

Resumen: tablero Kanban por estados con filtros y formulario de creación de tarea.

Hallazgos (usuario):
- Los bordes y separadores hacen que los estados parezcan tarjetas estáticas; falta affordance para arrastrar/soltar (drag handle claro).
- El formulario de filtros ocupa mucho espacio vertical en pantallas pequeñas; fuerza scroll para ver el tablero.
- Campos de fecha muestran placeholder confuso `dd/mm/aaaa --:-- -----` en lugar de ejemplo claro o formato detectado.
- Botón "Aplicar filtros" poco destacado; al aplicar no hay animación que indique carga.

Recomendaciones:
- Añadir indicación visual de drag-and-drop (handle, sombra al arrastrar) y pruebas de accesibilidad para teclado.
- Colapsar el panel de filtros por defecto en pantallas pequeñas y mostrar un botón "Mostrar filtros".
- Usar placeholders y validaciones claras en campos de fecha; proporcionar selector de fecha accesible.
- Mostrar spinner o skeleton al aplicar filtros.

Prioridad: media.

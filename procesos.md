# Listado de procesos / Expedientes — Análisis UX (perspectiva de usuario)

**Fecha:** 26 de mayo de 2026

Resumen: pantalla que lista expedientes con filtros de búsqueda y tipo de proceso.

Hallazgos (usuario):
- Mensaje "Cargando procesos..." aparece sin indicador adicional; si la carga falla no hay mensaje de error visible.
- Campo de búsqueda y filtros alineados a la derecha, independiente del contenido — provoca recorrido visual desigual.
- Botones "Actualizar" y "Nuevo proceso" en la misma zona; falta confirmación al crear.

Recomendaciones:
- Añadir mensajes de error y opción de reintentar si la carga falla.
- Reubicar filtros cerca del listado y mantener layout consistente para todas las pantallas de listados.
- Confirmación modal al crear procesos y validación de inputs antes de enviar.

Prioridad: media.

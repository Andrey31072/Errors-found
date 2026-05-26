# Ficha de expediente — Análisis UX (perspectiva de usuario)

**Fecha:** 26 de mayo de 2026

Resumen: vista detallada de un expediente (ACME-2026-0002 / ACME-2026-0001) con pestañas (Ficha, Partes, Timeline, Alertas, Actuaciones, Tareas).

Hallazgos (usuario):
- Pestañas con información numerada (p. ej. "Partes 2") pero sin indicación clara de filtrado actual.
- Botones de acción ("Actualizar", "Volver a procesos", "Representacion") están juntos sin prioridad visual.
- Campos en la ficha con etiquetas pequeñas y alto espaciado; en pantallas estrechas puede ocultarse información relevante.
- Falta de confirmaciones o mensajes de éxito visibles tras acciones (por ejemplo al editar datos).
- Algunos estados y etiquetas ("Identificada", "En curso") usan colores suaves, contraste insuficiente para usuarios con baja visión.

Recomendaciones:
- Añadir indicador activo de pestaña y mostrar conteo claro (ej. "Partes (2)").
- Priorizar acciones primarias (colocar CTA principal en la esquina superior derecha) y agrupar acciones secundarias.
- Mostrar banners de feedback tras operaciones (guardado/actualización) con mensajes claros.
- Mejorar contraste de etiquetas de estado y usar íconos además del color.

Prioridad: alta (usabilidad del flujo de trabajo diario).

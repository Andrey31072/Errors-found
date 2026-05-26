# Dashboard operativo — Análisis UX (perspectiva de usuario)

**Fecha:** 26 de mayo de 2026

Resumen: pantalla principal del usuario tras el login. Contiene tarjetas resumen, métricas y paneles de navegación.

Hallazgos (usuario):
- Confusión visual por densidad de tarjetas: muchas tarjetas pequeñas similares sin jerarquía clara (impacto: reconocimiento lento).
- Texto de métricas en mayúsculas y pequeñas inconsistencias de capitalización (ej. "EXPEDIENTES" vs "Expedientes").
- CTA principal "Ver procesos" poco destacado respecto a otras acciones; no queda claro el flujo siguiente.
- Contrastes bajos en textos secundarios (fechas, subtítulos) — difícil lectura en pantallas con brillo alto.
- Elementos clicables pequeños (botones "Actualizar", indicadores) que pueden ser difíciles en pantallas táctiles.

Recomendaciones:
- Unificar jerarquía visual: establecer una tarjeta principal más prominente y agrupar métricas secundarias.
- Mejorar contraste de subtítulos y aumentar tamaño mínimo de texto a 14px para legibilidad.
- Aumentar el target clickable de CTAs y añadir tooltips o microcopy que expliquen la acción.

Prioridad: media (UX) — alta si usuarios reportan dificultades para encontrar información clave.

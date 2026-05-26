# Plataforma / OpenAPI — Análisis UX (perspectiva de usuario)

**Fecha:** 26 de mayo de 2026

Resumen: pantalla de contrato operativo y documentación API (Swagger/OpenAPI). Captura muestra un error de parsing en la definición OpenAPI.

Hallazgos (usuario):
- En la sección "OpenAPI / Swagger" aparece un error rojo: "Parser error on line 1071 — bad indentation of a mapping entry" y mensaje "Unable to render this definition".
- Mensaje técnico expuesto al usuario sin instrucción clara para resolver (qué hacer, a quién reportar).
- Botones "Actualizar", "Swagger", "OpenAPI" están presentes pero sin feedback si la carga falla.

Recomendaciones:
- Mostrar un mensaje amigable para el usuario final: explicar que la especificación no pudo cargarse y proponer acciones (reintentar, contactar soporte, ver raw).
- Registrar el error técnico en logs y proporcionar un ID de incidencia al usuario para soporte.
- Evitar mostrar stack traces o mensajes técnicos crudos en la UI.

Prioridad: alta (documentación y confianza técnica).

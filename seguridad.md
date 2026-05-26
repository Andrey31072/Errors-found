# Seguridad — Usuarios y permisos (IAM) — Análisis UX

**Fecha:** 26 de mayo de 2026

Resumen: pantalla de gestión de usuarios, roles y permisos; lista y formulario de asignación.

Hallazgos (usuario):
- Identificadores de usuario y correos se muestran (ej. `admin@acme-demo.local`) — en entorno demo está bien, pero en producción deben protegerse o enmascararse.
- El selector de roles es una lista grande sin búsqueda eficaz; difícil asignar roles cuando hay muchos.
- Botones "Guardar roles" y "Desactivar" cercanos; riesgo de desactivar por error.
- Falta confirmación de cambios y explicación sobre el alcance de cada permiso.

Recomendaciones:
- Añadir enmascaramiento opcional y modo de auditoría para cambios sensibles.
- Mejorar selector de roles con búsqueda y filtros; mostrar descripción breve del rol al seleccionarlo.
- Pedir confirmación adicional para desactivar usuarios y mostrar historial de cambios.

Prioridad: alta (operacional y seguridad).

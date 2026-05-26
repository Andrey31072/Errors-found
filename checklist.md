# Checklist priorizado de correcciones (Usuario)

**Contexto:** Todas las correcciones deben ser pensadas desde la perspectiva del usuario final: claridad de texto, accesibilidad, feedback y seguridad.

## Críticas (resolver primero)
- Eliminar credenciales expuestas en UI demo o moverlas a una sección segura / modal con confirmación.
- Reemplazar mensajes técnicos visibles (por ejemplo errores de OpenAPI) por mensajes amigables con acción: "No se pudo cargar la documentación. Reintentar / Contactar soporte (ID: 1234)".

## Altas
- Mejorar contraste de textos secundarios y badges (cumplir WCAG AA: 4.5:1 para texto pequeño).
- Añadir feedback visual (banners/toasts) al guardar/actualizar entidades.
- Añadir confirmaciones para acciones destructivas (desactivar usuario, eliminar valor de catálogo).

## Medias
- Optimizar disposición de CTAs (priorizar, separar primario de secundario).
- Añadir validaciones cliente-side en formularios importantes (email, teléfono, fechas).
- Mejorar affordance para drag-and-drop en el tablero de tareas.

## Bajas
- Revisar y corregir ortografía / consistencia de copy en todas las pantallas.
- Ocultar UUIDs y datos técnicos en listados por defecto.
- Añadir tooltips y helper text en campos no obvios (N° Contrato, Resolución habilitada).

## Tareas operativas para el equipo de producto / dev
- Crear ticket por cada item crítico con pasos reproducibles y capturas (asignar prioridad y dueño).
- Añadir tests de accesibilidad básicos (axe-core) en pipeline para evitar regresiones.
- Planificar un hotfix para las correcciones de seguridad y mensajes técnicos en la documentación OpenAPI.

***

Si quieres, genero los tickets de ejemplo (título + descripción + pasos) listos para copiar en tu gestor (Jira/GitHub Issues).
# Cartera de clientes — Análisis UX (perspectiva de usuario)

**Fecha:** 26 de mayo de 2026

Resumen: listado de clientes con vista detallada y formulario de edición en la misma pantalla.

Hallazgos (usuario):
- Información de contacto y NIT mostrada en texto corrido sin truncamiento controlado; puede desbordar en pantallas pequeñas.
- Botones "Gestionar" y "Editar" muy próximos, riesgo de click accidental.
- Falta validación en el formulario (por ejemplo número de teléfono y email aceptan formatos inválidos en UI).
- Campo "N° Contrato" aparece en la ficha pero sin link o acción; el propósito no es explícito.

Recomendaciones:
- Aplicar truncamiento con tooltip para datos largos; mantener layout responsive.
- Separar botones de acción o añadir confirmación para acciones destructivas.
- Añadir validaciones en cliente-side con mensajes inline claros.
- Añadir helper text para campos menos obvios ("N° Contrato").

Prioridad: media.

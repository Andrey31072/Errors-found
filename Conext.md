# Auditoría UX/UI — Login (perspectiva de usuario)

**Fecha:** 26 de mayo de 2026

Este repositorio contiene el resultado de una revisión centrada en los errores observables por un usuario en la página de login localizada en: https://vpnt3lgv-5173.use2.devtunnels.ms/login

Objetivo
- Identificar y documentar todos los errores y problemas que un usuario encontraría al interactuar con cada pantalla del flujo de autenticación.

Alcance
- Solo se audita desde la perspectiva del usuario (texto, interacciones, accesibilidad, mensajes de error visibles, flujos confusos).
- Ignorar la advertencia del "developer tunnel" cuando aparezca — la auditoría se hace sobre las pantallas funcionales posteriores.

Estructura de archivos
- Cada pantalla analizada tiene su propio archivo Markdown en este directorio.
- Pantallas incluidas actualmente:
	- [pantalla_uno.md](pantalla_uno.md) — Análisis de la pantalla de inicio de sesión (login)
	- [dashboard.md](dashboard.md) — Dashboard operativo (pantalla principal)
	- [expediente.md](expediente.md) — Ficha de expediente / Procesos (detalle)
	- [tareas.md](tareas.md) — Tablero de tareas
	- [procesos.md](procesos.md) — Listado de expedientes / procesos
	- [clientes.md](clientes.md) — Cartera de clientes (listado y formulario)
	- [consulta.md](consulta.md) — Buscar expedientes (consulta)
	- [terminos.md](terminos.md) — Alertas / Términos (vencimientos)
	- [conflictos.md](conflictos.md) — Conflictos / Historial
	- [plataforma.md](plataforma.md) — Plataforma / OpenAPI (contrato operativo)
	- [seguridad.md](seguridad.md) — Usuarios y permisos (IAM)
	- [catalogos.md](catalogos.md) — Catálogos (valores)
	- [actuaciones.md](actuaciones.md) — Actuaciones / Timeline

Cómo usar
- Abrir el archivo correspondiente a la pantalla para ver los hallazgos, evidencias y prioridades.
- Cada archivo contiene:
	- Resumen de hallazgos.
	- Errores observados desde la perspectiva del usuario.
	- Impacto y recomendaciones priorizadas.

Siguientes pasos sugeridos
- Revisar las recomendaciones críticas primero (seguridad, mensajes confusos que impidan el login).
- Repetir la auditoría después de las correcciones y añadir nuevos MD por pantalla si el flujo crece (por ejemplo: pantalla de MFA, recuperación de contraseña, error de credenciales).

Contacto
- Si necesitas que amplíe el análisis con capturas de pantalla, HTML o pruebas de accesibilidad automatizadas, añádelas en el repo o compártelas aquí y continúo el trabajo.


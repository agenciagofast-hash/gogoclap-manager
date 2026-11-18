# Claude Code: GOGOCLAP

@AGENTS.md

Particularidades de Claude Code:

- Los roles están en `.claude/agents/` y los procedimientos en `.claude/skills/`. Delegá en un rol cuando la tarea es suya y es grande, por ejemplo el armado del EPK o una lista de 40 salas. Para algo simple, resolvelo vos.
- Para investigar en internet usá WebSearch o WebFetch. Instagram y TikTok sin sesión muestran poco: anotá lo que no se pudo leer.
- Las piezas gráficas y los videos se producen con las herramientas que Alexis tenga en esa PC. Este repo guarda guiones, copies y planes, no los archivos pesados (ver `.gitignore`).

# GOGOCLAP · Oficina de management

Repo **público** de GoFast (desde el 18/11/2026, por decisión de Alexis) para la carrera de **GOGOCLAP** (Rodrigo "Gogo" Castillo, Santa Fe): rap, beatbox y loops en vivo, la banda Grooving Fresh.Co y el disco "Sabe las vece".

Funciona como un **equipo de IA**: manager, productor, booking, contenido y prensa con fondos. Lo opera Alexis con Claude Code o Codex, y Gogo aprueba.

## Cómo seguir en otra PC

1. Cloná el repo. Como es público, no hace falta iniciar sesión para descargarlo:
   ```bash
   git clone https://github.com/agenciagofast-hash/gogoclap-manager.git
   ```
2. Abrí la carpeta con **Claude Code** (o Codex, que lee `AGENTS.md`).
3. Primer pedido: *"leé ESTADO.md y armá el plan de la semana"*. También podés usar `/plan-semanal`.
4. Al terminar cada sesión, guardá y subí los cambios. **Subir sí pide iniciar sesión** en GitHub con `agenciagofast-hash` o con una cuenta invitada como colaboradora:
   ```bash
   git add -A
   git commit -m "qué cambió"
   git push
   ```
   Antes de empezar en la otra PC, traé lo último:
   ```bash
   git pull
   ```

## Qué pedirle al equipo

| Querés… | Pedí | Rol o skill |
|---|---|---|
| Saber qué hacer esta semana | "plan de la semana" | `/plan-semanal` · `gogo-manager` |
| Sacar el single o el disco | "planificá el lanzamiento de [tema] para el [fecha]" | `/lanzamiento` · `gogo-productor` |
| Conseguir fechas | "ronda de booking" / "armá gira por Córdoba" | `/booking` · `gogo-booking` |
| Publicar en redes | "¿qué publicamos?" / "copy para este video" / "plan de grabación" | `/contenido` · `gogo-contenido` |
| Fondos, concursos y derechos | "¿qué convocatorias hay?" / "prepará la postulación a…" | `/convocatorias` · `gogo-prensa-fondos` |
| Ver cómo vamos | "revisión del mes" / "cargá estas estadísticas" | `/metricas` · `gogo-manager` |

## Mapa

```
ESTADO.md                    ← dónde estamos y próximo paso (leer primero)
AGENTS.md / CLAUDE.md        ← instrucciones del equipo de IA
docs/
  01-perfil-artista.md       ← identidad, formatos, bio, posicionamiento
  02-respuestas-brief.md     ← respuestas de Gogo al cuestionario
  03-auditoria.md            ← diagnóstico al 18/11/2026
  04-plan-de-carrera.md      ← plan de 90 días y de 12 meses
  05-oportunidades.md        ← convocatorias, fondos, Cosquín, plataformas
  06-catalogo-y-prensa.md    ← discografía, videos, prensa para el EPK
  07-historial.md            ← lo trabajado con GoFast (copies, auditoría, cuestionario)
operacion/
  metricas.md                ← métricas por fecha
  shows.md                   ← shows, embudo de booking y consultas
  pendientes.md              ← lo que falta que pase Gogo
plantillas/                  ← EPK, rider y mensajes de booking
.claude/agents/              ← los 5 roles
.claude/skills/              ← los 6 procedimientos
_MATERIAL/                   ← audios, videos y fotos (fuera de git; Drive o disco)
```

## Reglas rápidas

- Gogo aprueba todo lo que se publica o se envía.
- No se inventan cifras: cada dato lleva fecha y fuente.
- No se guardan claves, CBU, CUIT ni datos de terceros.

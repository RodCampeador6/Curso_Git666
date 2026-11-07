# Resumen del trabajo en Curso_Git666

Este resumen sale del historial de git del repositorio, no de la memoria de las conversaciones. Cada sesión de Claude es independiente, así que lo que se habló y no llegó a un commit no figura acá.

## Punto de partida

`main` tiene un único commit (`f0ac6c6`, 2021-09-24, "Initial commit"), que crea un `README.md` con solo el título `# Curso_Git666`. Nada de lo que sigue está mergeado en `main`.

## Proyecto de vida saludable (rama `claude/health-wellness-project-f68lar`)

Commit `b7d000a` del 2026-10-17. Arma un proyecto para mejorar alimentación, ejercicio y salud mental, organizado como un proyecto de software para practicar Git al mismo tiempo: el progreso se registra con commits semanales y el historial queda como diario.

| Archivo | Contenido |
|---|---|
| `README.md` | Cómo funciona el proyecto, paso a paso, y tres reglas: lo chico vale más que lo perfecto, registrar sin juzgarse, no fallar dos veces seguidas. Aclara que no es consejo médico. |
| `plan/12-week-plan.md` | Hoja de ruta en tres fases de 4 semanas (v0.1 base, v0.5 construcción, v1.0 subir de nivel), con hábitos por área y un criterio para dar cada fase por terminada. |
| `prompts/00-start-here.md` | Prompt inicial para que Claude arme un plan personal. |
| `prompts/diet.md`, `exercise.md`, `mind.md` | Prompts por área: comidas y compras, rutinas y progresión, concentración, sueño y estrés. |
| `prompts/weekly-review.md` | Prompt para revisar la semana y ajustar la siguiente. |
| `tracking/baseline.md` | Medición inicial, se completa una sola vez. |
| `tracking/weekly-log-template.md` | Plantilla para copiar cada semana. |

## Juego Lantern Run (rama `ccr-db44eb16-bfralp`)

Commit `9cac08d` del 2026-10-31. Un juego de navegador en un solo archivo, `game/index.html` (259 líneas, canvas y JavaScript sin dependencias). Llevás una linterna que se va apagando y la recargás juntando brasas. Aparecen fantasmas cada vez más seguido y más rápido, y se vuelven más agresivos cuanto menos luz tenés. La única defensa es el dash (Espacio o doble toque, 1,6 s de recarga), que elimina al fantasma que atravesás. Se juega con WASD o las flechas, o arrastrando en pantallas táctiles. El puntaje sube con el tiempo, las brasas y los fantasmas eliminados, y el récord se guarda en `localStorage`.

## Estado actual

Las dos ramas están pusheadas pero no hay pull requests ni merges a `main`. Este archivo se agregó en la rama `ccr-019821c5-vaz3fv`.

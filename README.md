# APE 6 · Evaluación y validación — Fase 1: Planificación de la evaluación de usabilidad de CaféU v3

**Universidad Técnica de Ambato · FISEI · Carrera de Software · Interacción Humano-Computador · 5.º «A»**
**Docente:** Ing. José Rubén Caiza Caizabuano, Mg.

## Problema
CaféU v3 es el prototipo navegable que el grupo construyó en el APE 4 para que la comunidad de la FISEI pida en la cafetería antes de llegar: consultar el menú, personalizar la bebida, ajustar el pedido, programar la hora de retiro y confirmar. Ya funciona, pero hace falta un **plan riguroso** para comprobar con personas reales si permite cumplir esos objetivos y qué lo impide.

## Objetivo
Diseñar el plan de evaluación de usabilidad de CaféU v3 aplicando ISO 9241-11, las 10 heurísticas de Nielsen y la prueba con usuarios con pensamiento en voz alta, considerando eficacia, eficiencia, satisfacción y aspectos éticos.

## Pregunta de evaluación
> ¿En qué medida el prototipo CaféU v3 permite a estudiantes y personal de la FISEI consultar el menú, armar y modificar un pedido y programar su retiro con eficacia, eficiencia y satisfacción, y qué problemas de usabilidad lo impiden?

## Métodos
| Método | Tipo | Quién | Instrumento |
|---|---|---|---|
| Evaluación heurística (10 heurísticas de Nielsen, severidad 0–4) | Analítico | 4 integrantes por separado | [Guía heurística](evidencias/05-guia-evaluacion-heuristica.md) |
| Prueba con usuarios con pensamiento en voz alta | Empírico | P1, P2, P3 (ajenos al grupo) | [Tareas](evidencias/03-tareas.md), [hoja y SUS](evidencias/04-hoja-de-observacion.md) |

Los hallazgos de ambos métodos se **triangulan** en la Fase 2.

## Las seis tareas (resumen)
| ID | Tipo | Situación | Meta / Máx. | Respuesta correcta |
|---|---|---|---|---|
| T1 | Consulta | Tiempo de preparación y hora de cierre | 30 s / 60 s | 10 min · hasta las 18:00 |
| T2 | Consulta | ¿Se puede pedir empanada de verde hoy? | 40 s / 80 s | No: agotada, vuelve mañana |
| T3 | Creación | Capuchino mediano con leche de almendra | 75 s / 150 s | $2,70 |
| T4 | Creación | Sumar dos panes de yuca | 60 s / 120 s | Total $3,90 |
| T5 | Modificación | El amigo solo quiere un pan | 40 s / 80 s | Total $3,30 |
| T6 | Creación | Retiro a las 11:15, enviar, número y monto | 90 s / 180 s | N.º 031 · $3,30 al retirar |

Escenarios completos, criterios de éxito, pista única y reinicio en [`evidencias/03-tareas.md`](evidencias/03-tareas.md).

## Métricas
Tasa de éxito (solo «Sí» sin ayuda) · mediana del tiempo por tarea · errores críticos y no críticos · SUS (0–100, referencia 68).

## Roles
| Rol | Integrante |
|---|---|
| Moderador | Mora Beltrán Santiago Sebastián |
| Responsable de métricas | Vinces Cueva Boris Yussef |
| Observador | Acaro Ibujés Pedro Sebastián |
| Soporte técnico | González Álvarez Vladimir Humberto |

## Integrantes y aportes
| Integrante | GitHub | Aporte en el repositorio |
|---|---|---|
| González Álvarez Vladimir Humberto | @VladAlz | README, marco conceptual, prototipo y plan de evaluación |
| Mora Beltrán Santiago Sebastián | @Santio13-code | Consentimiento informado y guion de la sesión |
| Vinces Cueva Boris Yussef | @Yussef2403 | Hoja de observación con SUS y plantillas de resultados |
| Acaro Ibujés Pedro Sebastián | @Sebastianyiyi | Matriz de seis tareas, guía heurística e informe |

## Estructura
```
APE6_IHC/
├── README.md
├── docs/
│   └── investigacion.md                 Marco conceptual (ISO 9241-11, Nielsen, SUS, ética)
├── prototipo/
│   ├── enlace.md                        Enlace público, parámetros y estado inicial
│   └── cafeu-v3.html                    Respaldo local del prototipo
├── evidencias/
│   ├── 01-plan-de-evaluacion.md         Plan completo (qué, pregunta, métodos, participantes, métricas, roles, validación)
│   ├── 02-consentimiento-informado.md
│   ├── 03-tareas.md                     Matriz de seis tareas con respuestas y criterios de éxito
│   ├── 04-hoja-de-observacion.md        Hoja por participante + cuestionario SUS
│   ├── 05-guia-evaluacion-heuristica.md
│   ├── 06-guion-de-la-sesion.md
│   └── imprimibles/                     Consentimiento y hoja en PDF para imprimir
├── resultados/                          Plantillas de registro (se llenan en la Fase 2)
└── informe/
    ├── APE6_Fase1_Informe.pdf           Plan de evaluación en formato UTA
    └── APE6_Fase1_Informe.docx
```

## Enlaces
- **Prototipo evaluado:** https://raw.githack.com/Sebastianyiyi/APE04_IHC/main/APE4-integral/prototipo/cafeu-v3.html
- **Origen del prototipo (APE 4):** https://github.com/Sebastianyiyi/APE04_IHC
- **Repositorio de referencia de la guía:** https://github.com/carlitosgiovanniramos/HCI-2026-G5

## Alcance de la Fase 1
Esta fase **planifica** la evaluación. La aplicación con P1–P3, la evaluación heurística individual, la triangulación y el análisis de resultados corresponden a la Fase 2.

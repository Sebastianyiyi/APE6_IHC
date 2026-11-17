# APE 6 · Evaluación y validación de la usabilidad de CaféU v3

**Universidad Técnica de Ambato · FISEI · Carrera de Software · Interacción Humano-Computador · 5.º «A»**
**Docente:** Ing. José Rubén Caiza Caizabuano, Mg.

## Objetivo
Planificar (Fase 1) y validar mediante un pilotaje (Fase 2) el protocolo de evaluación de usabilidad de **CaféU v3**, el prototipo que el grupo construyó en el APE 4 para pedir en la cafetería de la FISEI antes de llegar. La evaluación usa ISO 9241-11 (eficacia, eficiencia y satisfacción), las 10 heurísticas de Nielsen y la prueba con usuarios con pensamiento en voz alta.

## Integrantes
| Integrante | GitHub | Rol en la evaluación |
|---|---|---|
| Acaro Ibujés Pedro Sebastián | @Sebastianyiyi | Observador |
| González Álvarez Vladimir Humberto | @VladAlz | Soporte técnico |
| Mora Beltrán Santiago Sebastián | @Santio13-code | Moderador |
| Vinces Cueva Boris Yussef | @Yussef2403 | Responsable de métricas |

## Prototipo evaluado
- **Enlace público:** https://raw.githack.com/Sebastianyiyi/APE04_IHC/main/APE4-integral/prototipo/cafeu-v3.html
- **Respaldo local:** [`prototipo/cafeu-v3.html`](prototipo/cafeu-v3.html) · parámetros y estado inicial en [`prototipo/enlace.md`](prototipo/enlace.md)

## Fase 1 · Planificación
Plan de evaluación con la pregunta «¿En qué medida CaféU v3 permite a estudiantes y personal de la FISEI consultar el menú, armar y modificar un pedido y programar su retiro con eficacia, eficiencia y satisfacción, y qué problemas lo impiden?», dos métodos (heurística y prueba con usuarios), tres participantes del perfil, seis tareas con meta, máximo, criterio de éxito y respuesta correcta, métricas (éxito, mediana de tiempo, errores, SUS), consentimiento informado, roles y siete criterios de validación (C1–C7).

## Fase 2 · Pilotaje
> **Nota metodológica.** Por indicación del docente, el ensayo interno y el pilotaje se desarrollaron como ejercicio académico con participantes simulados, construidos a partir de los perfiles P1–P3 definidos en la Fase 1. Las evaluaciones heurísticas fueron realizadas por cada integrante.

Se aplicó el protocolo de la Fase 1 sin cambios a P1, P2 y P3, se transcribió cada hoja, se calcularon las métricas, se compararon los resultados con C1–C7, se ajustó el protocolo (V1 → V2), cada integrante hizo su evaluación heurística y se cruzaron ambos métodos.

### Resultados principales
| Indicador | Resultado | Umbral (Fase 1) |
|---|---|---|
| Tasa de éxito global | 17/18 (94,4 %); 100 % en T1–T5 y 66,7 % en T6 | ≥ 80 % por tarea → no en T6 |
| Errores | 1 crítico (T6) y 5 no críticos | 0 críticos en T3–T6 → no |
| Mediana de tiempo | 6 de 6 tareas bajo la meta | Mediana ≤ meta → sí |
| SUS | P1 82,5 · P2 92,5 · P3 67,5 · **media 80,8** | ≥ 68 → sí |
| Criterios del protocolo | C1, C2, C3, C6 sí · C4 parcial · C5 y C7 no | Generaron 6 ajustes (V2) |

**Hallazgo principal:** el retiro «Lo antes posible» viene preseleccionado y se puede confirmar sin elegir la hora (error crítico de P2 en T6); fue también el único problema marcado por los cuatro evaluadores heurísticos. Le siguen «Quitar», que borra la línea completa (2 de 3 participantes en T5), el campo de hora sin a. m./p. m. y las opciones de leche fuera de la vista.

## Dónde está cada entregable
| Entregable | Ubicación |
|---|---|
| Plan de evaluación | [`Fase1-Planificacion/Plan_Evaluacion.pdf`](Fase1-Planificacion/Plan_Evaluacion.pdf) |
| Consentimiento informado | [`Fase1-Planificacion/Consentimiento_Informado.pdf`](Fase1-Planificacion/Consentimiento_Informado.pdf) |
| Seis tareas | [`Fase1-Planificacion/Seis_Tareas.pdf`](Fase1-Planificacion/Seis_Tareas.pdf) |
| Hoja de observación y SUS | [`Fase1-Planificacion/Hoja_Observacion_SUS.pdf`](Fase1-Planificacion/Hoja_Observacion_SUS.pdf) |
| Informe de la Fase 1 | [`Fase1-Planificacion/Informe_APE6_Fase1.pdf`](Fase1-Planificacion/Informe_APE6_Fase1.pdf) |
| Fuentes editables de la Fase 1 | [`Fase1-Planificacion/fuentes/`](Fase1-Planificacion/fuentes/) |
| Hojas por participante | [`Fase2-Pilotaje/Participantes/`](Fase2-Pilotaje/Participantes/) (P1.md, P2.md, P3.md) |
| Resumen de métricas | [`Fase2-Pilotaje/Resumen_Metricas.pdf`](Fase2-Pilotaje/Resumen_Metricas.pdf) · datos en [`Fase2-Pilotaje/datos/`](Fase2-Pilotaje/datos/) |
| Ajustes del protocolo V1 → V2 | [`Fase2-Pilotaje/Ajustes_Protocolo_V1_V2.pdf`](Fase2-Pilotaje/Ajustes_Protocolo_V1_V2.pdf) |
| Evaluaciones heurísticas individuales y comparación | [`Fase2-Pilotaje/Evaluaciones_Heuristicas/`](Fase2-Pilotaje/Evaluaciones_Heuristicas/) |
| Hallazgos preliminares | [`Fase2-Pilotaje/Hallazgos_Preliminares.pdf`](Fase2-Pilotaje/Hallazgos_Preliminares.pdf) |
| Informe de la Fase 2 (formato UTA) | [`Fase2-Pilotaje/Informe_APE6_Fase2.pdf`](Fase2-Pilotaje/Informe_APE6_Fase2.pdf) |
| Registro de aportes y evidencias | [`Evidencias_Colaboracion/`](Evidencias_Colaboracion/) |

## Estructura
```
APE6_IHC/
├── README.md
├── prototipo/                       Enlace y respaldo de CaféU v3
├── Fase1-Planificacion/
│   ├── Plan_Evaluacion.pdf
│   ├── Consentimiento_Informado.pdf
│   ├── Seis_Tareas.pdf
│   ├── Hoja_Observacion_SUS.pdf
│   ├── Informe_APE6_Fase1.pdf / .docx
│   ├── fuentes/                     Markdown editable de cada documento
│   └── plantillas/                  Plantillas CSV de registro
├── Fase2-Pilotaje/
│   ├── Participantes/               P1.md, P2.md, P3.md
│   ├── datos/                       registro-tareas.csv, sus.csv
│   ├── Resumen_Metricas.pdf
│   ├── Ajustes_Protocolo_V1_V2.pdf
│   ├── Evaluaciones_Heuristicas/    Una evaluación por integrante + comparación
│   ├── Hallazgos_Preliminares.pdf
│   └── Informe_APE6_Fase2.pdf / .docx
└── Evidencias_Colaboracion/
    ├── Registro_Aportes.md
    └── Evidencias_APE6_Fase2.docx
```

En el repositorio no hay nombres, datos personales ni grabaciones de participantes; solo los códigos P1, P2 y P3.

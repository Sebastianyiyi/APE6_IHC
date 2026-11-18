# APE 6 · Evaluación y validación de la usabilidad de CaféU v3

**Universidad Técnica de Ambato · FISEI · Carrera de Software · Interacción Humano-Computador · 5.º «A»**
**Docente:** Ing. José Rubén Caiza Caizabuano, Mg.

## Objetivo
Planificar (Fase 1), pilotear (Fase 2), aplicar y analizar (Fase 3) y priorizar y cerrar (Fase 4) la evaluación de usabilidad de **CaféU v3**, el prototipo que el grupo construyó en el APE 4 para pedir en la cafetería de la FISEI antes de llegar. La evaluación usa ISO 9241-11 (eficacia, eficiencia y satisfacción), las 10 heurísticas de Nielsen y la prueba con usuarios con pensamiento en voz alta para responder la pregunta del laboratorio: **¿Una interfaz que funciona técnicamente puede ser una mala interfaz?** (verificación frente a validación, Boehm, 1984).

## Integrantes
| Integrante | GitHub | Rol en la evaluación |
|---|---|---|
| Acaro Ibujés Pedro Sebastián | @Sebastianyiyi | Observador |
| González Álvarez Vladimir Humberto | @VladAlz | Soporte técnico |
| Mora Beltrán Santiago Sebastián | @Santio13-code | Moderador |
| Vinces Cueva Boris Yussef | @Yussef2403 | Responsable de métricas (cronometrista) |

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

## Fase 3 · Aplicación y análisis

> **Nota metodológica.** Por indicación del docente, las sesiones con usuarios de la Fase 3 se desarrollaron como ejercicio académico con participantes simulados, construidos a partir del perfil definido en la Fase 1 y del comportamiento real del prototipo. Las evaluaciones heurísticas son individuales de cada integrante.

### Ajuste post-pilotaje

Se aplicó el protocolo versión 2 (ajustes de la Fase 2) y se agregaron dos **tareas de refuerzo** para funciones que el pilotaje no probó: **T7** (encontrar un producto escribiendo: buscador) y **T8** (quitar y recuperar sin volver al menú: prevención y recuperación de errores). El estado se reinicia con **F5** entre participantes y entre T6 y T7. Detalle en [`docs/tareas-fase3.md`](docs/tareas-fase3.md).

### Método 1 · Evaluación heurística independiente (severidad 1–4)

Cada integrante inspeccionó el prototipo por separado con las 10 heurísticas de Nielsen y calificó cada problema por Frecuencia, Impacto y Persistencia: [`heuristica-gonzalez.md`](resultados/heuristica-gonzalez.md) · [`heuristica-mora.md`](resultados/heuristica-mora.md) · [`heuristica-vinces.md`](resultados/heuristica-vinces.md) · [`heuristica-acaro.md`](resultados/heuristica-acaro.md).

### Método 2 · Prueba con usuarios (think-aloud)

Tres participantes externos ([`P1`](resultados/P1.md), [`P2`](resultados/P2.md), [`P3`](resultados/P3.md)) con consentimiento anonimizado, roles de moderador, usuario, cronometrista y observador, y SUS al final de cada sesión.

| Código | Perfil | Duración |
|---|---|---|
| P1 | Estudiante de 5.º semestre de otra carrera de la FISEI, 22–25 años; apps de pedidos: ocasionalmente | 21 min |
| P2 | Docente de la FISEI, 40 o más años; apps de pedidos: nunca | 24 min |
| P3 | Estudiante de 1.er semestre de otra carrera de la FISEI, 18–21 años; apps de pedidos: frecuentemente | 18 min |

### Métricas ISO 9241-11 y SUS

| Tarea | Éxito autónomo | E. críticos | E. no críticos | Mediana (s) | Meta (s) |
|---|---|---|---|---|---|
| T1 · Preparación y cierre | 3/3 (100 %) | 0 | 0 | 8 | 30 |
| T2 · Empanada de verde | 3/3 (100 %) | 0 | 1 | 19 | 40 |
| T3 · Capuchino M con almendra | 3/3 (100 %) | 0 | 1 | 38 | 75 |
| T4 · Sumar 2 panes de yuca | 3/3 (100 %) | 0 | 0 | 22 | 60 |
| T5 · Dejar 1 pan de yuca | 3/3 (100 %) | 0 | 2 | 26 | 40 |
| T6 · Retiro 11:15 y confirmar | 2/3 (66,7 %) | 1 | 1 | 55 | 90 |
| T7 · Encontrar escribiendo (buscador) *(refuerzo)* | 3/3 (100 %) | 0 | 0 | 21 | 45 |
| T8 · Quitar y recuperar sin el menú *(refuerzo)* | 2/3 (66,7 %) | 1 | 0 | 18 | 40 |
| **Total** | **22/24 (91,7 %)** | **2** | **5** | 8/8 bajo la meta | |

| Dimensión | Resultado | Referencia |
|---|---|---|
| Eficacia | 91,7 % de éxito autónomo; 2 errores críticos (T6, T8) y 5 no críticos | ≥ 80 % por tarea; 0 críticos |
| Eficiencia | Las 8 medianas por debajo de su meta | Mediana ≤ meta |
| Satisfacción | SUS P1 75 · P2 62,5 · P3 92,5 · **media 76,67** | 68,0 (industria) |

Detalle en [`resultados/metricas-fase3.md`](resultados/metricas-fase3.md) y datos en [`resultados/datos/`](resultados/datos/).

## Fase 4 · Priorización y cierre

### Matriz consolidada de hallazgos

| ID | Heurística | Problema | Severidad (1–4) | Evidencia | Propuesta |
|---|---|---|---|---|---|
| H-01 | H5 | El retiro «Lo antes posible» viene preseleccionado y la hora aparece como texto secundario en la revisión: se puede confirmar sin decidir la hora. | **4** | T6: P3 confirmó con retiro 09:51 (error crítico). En el pilotaje: P2, mismo error. | Sin preselección; hora visible en el botón de confirmar. |
| H-02 | H3 | El aviso con «Deshacer» desaparece a los 6 s y se muestra abajo, lejos de la lista; si no se ve a tiempo no hay forma de recuperar lo quitado. | **3** | T8: P2 no vio el aviso y no pudo recuperar el producto (error crítico). | Aviso persistente hasta la siguiente acción, junto a la lista. |
| H-03 | H3 | «Quitar» está junto al control de cantidad y borra la línea completa; se usa para restar una unidad. | **3** | T5: P1 y P2 pulsaron «Quitar» para restar una unidad (2 errores no críticos). | Renombrar a «Eliminar» y separarlo del contador. |
| H-04 | H9 | Con el equipo en 12 h el campo queda incompleto sin a. m./p. m. y el mensaje «Ingresa la hora…» no dice qué falta. | **3** | T6: P2 escribió la hora sin a. m.; el mensaje no orientó (error no crítico, 132 s). | Selector de franjas de 15 min y mensaje específico. |
| H-05 | H6 | Las opciones de leche quedan bajo el pliegue y la leche entera viene marcada; se agrega sin verlas. | **2** | T3: P2 agregó con leche entera y rehízo el producto (error no crítico, 102 s). | Opciones visibles y resumen junto al botón de agregar. |
| H-06 | H6 | La línea muestra el subtotal ($1,20 por 2 panes) sin precio unitario. | **2** | T4: P2 dudó si $1,20 era el precio de cada pan (duda, sin error). | Mostrar «2 × $0,60 = $1,20». |
| H-07 | H4 | El borde de los filtros no seleccionados tiene un contraste de 1,63:1 con el fondo (WCAG 1.4.11 pide 3:1). | **2** | No se observó con usuarios. | Borde de los filtros con contraste ≥ 3:1. |
| H-08 | H3 | Un pedido confirmado no se puede cancelar ni editar. | **2** | No se observó (ninguna tarea cancela un pedido). | Permitir cancelar en los primeros minutos. |
| H-09 | H7 | El buscador acepta sin tildes y sinónimos («cacao», «cafe»), pero no lo indica. | **1** | No se observó como problema: en T7 los 3 encontraron el producto escribiendo (3/3). | Ejemplos en el marcador de posición del buscador. |
| H-10 | H10 | No hay ayuda sobre pago, cancelación o retraso en el retiro. | **1** | No se observó. | Ayuda breve sobre pago, retiro y cancelación. |
| H-11 | H2 | Las tarjetas muestran «desde $2,00»; el precio final solo aparece al personalizar. | **1** | No se observó (nadie respondió con el precio «desde»). | Etiqueta «desde» en gris y precio final destacado. |
| H-12 | H10 | La última hora de retiro (17:45) solo se informa en el paso 3. | **1** | No se observó. | Mostrar «Último retiro 17:45» en el inicio. |
| H-13 | H2 | Se busca un producto de comida con el filtro «Bebidas». | **1** | T2: P1 buscó la empanada con el filtro «Bebidas» (error no crítico); en el pilotaje le pasó a P3. | Íconos o ejemplos en los filtros de categoría. |

### Triangulación metodológica

| Clasificación | Hallazgos |
|---|---|
| Confirmado por ambos métodos | H-01, H-02, H-03, H-04, H-05, H-06 |
| Solo heurística | H-07, H-08, H-09, H-10, H-11, H-12 |
| Solo usuarios | H-13 |

Matriz completa con las severidades de cada evaluador en [`resultados/heuristica-consolidado.md`](resultados/heuristica-consolidado.md).

### Criterios técnicos de mejora

| ID | Hallazgos | Componente | Cambio específico | Estándar |
|---|---|---|---|---|
| C-01 | H-01 | Hora de retiro / Revisar y confirmar | Ninguna opción de retiro viene marcada; «Revisar y confirmar» se habilita solo después de elegir; el botón final muestra la hora («Confirmar pedido · 11:15»). | Nielsen H5 y H1; WCAG 2.1 3.3.4 Prevención de errores (AA); ISO 9241-11 eficacia |
| C-02 | H-02 | Aviso con «Deshacer» | El aviso permanece hasta la siguiente acción del usuario (sin cierre automático) y aparece encima de la lista, con foco accesible. | WCAG 2.1 2.2.1 Tiempo ajustable (A); Nielsen H3 |
| C-03 | H-03 | Mi pedido · «Quitar» | «Quitar» pasa a «Eliminar», con ícono, separado al menos 24 px del contador y distinto en estilo de − y +. | Nielsen H3 y H4; WCAG 2.1 2.5.5 Tamaño del objetivo (AAA, recomendado) |
| C-04 | H-04 | Hora de retiro · campo de hora | El campo nativo se reemplaza por un selector de franjas de 15 min (09:51–17:45) y, si hay error, el mensaje dice qué falta y cómo corregirlo. | WCAG 2.1 3.3.1 Identificación de errores (A) y 3.3.3 Sugerencias ante errores (AA); Nielsen H9 |
| C-05 | H-05 | Detalle del producto | Las opciones de tamaño y leche caben en la primera vista en 1366 × 657 o el botón de agregar muestra el resumen («Mediano · almendra · $2,70»). | Nielsen H6 y H5; WCAG 2.1 3.3.2 Etiquetas o instrucciones (A) |
| C-06 | H-06 | Mi pedido · línea | Cada línea con más de una unidad muestra «cantidad × precio unitario = subtotal». | Nielsen H6 y H2; ISO 9241-11 eficiencia |
| C-07 | H-07 | Menú · filtros | El borde de los filtros no seleccionados alcanza al menos 3:1 (p. ej. #8D7B73, 4,03:1 sobre blanco). | WCAG 2.1 1.4.11 Contraste de componentes (AA) |
| C-08 | H-08 | Confirmación | Botón «Cancelar pedido» visible durante los 2 primeros minutos tras confirmar, con confirmación. | Nielsen H3; WCAG 2.1 3.3.4 (AA) |
| C-09 | H-09 | Menú · buscador | El marcador de posición muestra ejemplos («Busca: capuchino, cacao, pan…»). | Nielsen H7 y H10 |
| C-10 | H-10, H-12 | Inicio y confirmación · ayuda | El inicio muestra «Último retiro 17:45» y la confirmación incluye ayuda de 2 líneas sobre pago y retraso. | Nielsen H10; ISO 9241-11 satisfacción |
| C-11 | H-11, H-13 | Menú · tarjetas y filtros | «desde» en texto secundario junto al precio y filtros con ícono (taza/plato) además del texto. | Nielsen H2 y H6 |

Criterios con su forma de verificación en [`docs/criterios-tecnicos.md`](docs/criterios-tecnicos.md).

### Backlog priorizado (GitHub Issues)

| Prioridad | Issue | Criterio | Mejora |
|---|---|---|---|
| P1 | [#1](https://github.com/Sebastianyiyi/APE6_IHC/issues/1) | C-01 | Hora de retiro / Revisar y confirmar |
| P1 | [#2](https://github.com/Sebastianyiyi/APE6_IHC/issues/2) | C-02 | Aviso con «Deshacer» |
| P2 | [#3](https://github.com/Sebastianyiyi/APE6_IHC/issues/3) | C-03 | Mi pedido · «Quitar» |
| P2 | [#4](https://github.com/Sebastianyiyi/APE6_IHC/issues/4) | C-04 | Hora de retiro · campo de hora |
| P3 | [#5](https://github.com/Sebastianyiyi/APE6_IHC/issues/5) | C-05 | Detalle del producto |
| P3 | [#6](https://github.com/Sebastianyiyi/APE6_IHC/issues/6) | C-06 | Mi pedido · línea |
| P3 | [#7](https://github.com/Sebastianyiyi/APE6_IHC/issues/7) | C-07 | Menú · filtros |
| P4 | [#8](https://github.com/Sebastianyiyi/APE6_IHC/issues/8) | C-08 | Confirmación |
| P4 | [#9](https://github.com/Sebastianyiyi/APE6_IHC/issues/9) | C-09 | Menú · buscador |
| P4 | [#10](https://github.com/Sebastianyiyi/APE6_IHC/issues/10) | C-10 | Inicio y confirmación · ayuda |
| P4 | [#11](https://github.com/Sebastianyiyi/APE6_IHC/issues/11) | C-11 | Menú · tarjetas y filtros |

**P1** severidad 4 o error crítico confirmado · **P2** severidad 3 · **P3** severidad 2 · **P4** severidad 1.

### Respuesta a la pregunta del laboratorio

**Sí, una interfaz que funciona técnicamente puede ser una mala interfaz.** CaféU v3 pasa la verificación (todo hace lo especificado), pero la validación con usuarios mostró errores críticos silenciosos: confirmar con una hora de retiro no elegida (H-01) y perder lo quitado porque «Deshacer» desaparece a los 6 s (H-02). Conclusiones completas en [`docs/conclusiones.md`](docs/conclusiones.md).

## Dónde está cada entregable
| Entregable | Ubicación |
|---|---|
| Plan, consentimiento, seis tareas y hoja SUS (Fase 1) | [`Fase1-Planificacion/`](Fase1-Planificacion/) |
| Pilotaje, métricas, ajustes V1 → V2 y hallazgos preliminares (Fase 2) | [`Fase2-Pilotaje/`](Fase2-Pilotaje/) |
| Protocolo de la Fase 3 (refuerzos T7–T8 y reinicio F5) | [`docs/tareas-fase3.md`](docs/tareas-fase3.md) |
| Evaluaciones heurísticas individuales (1–4) | [`resultados/heuristica-*.md`](resultados/) |
| Registros de participantes | [`resultados/P1.md`](resultados/P1.md) · [`P2.md`](resultados/P2.md) · [`P3.md`](resultados/P3.md) |
| Métricas ISO/SUS de la Fase 3 | [`resultados/metricas-fase3.md`](resultados/metricas-fase3.md) · [`resultados/datos/`](resultados/datos/) |
| Matriz consolidada y triangulación | [`resultados/heuristica-consolidado.md`](resultados/heuristica-consolidado.md) |
| Criterios técnicos y texto del backlog | [`docs/criterios-tecnicos.md`](docs/criterios-tecnicos.md) · [`docs/backlog-issues.md`](docs/backlog-issues.md) |
| GitHub Issues del backlog | [Issues del repositorio](https://github.com/Sebastianyiyi/APE6_IHC/issues) |
| Conclusiones | [`docs/conclusiones.md`](docs/conclusiones.md) |
| Informe de las Fases 3 y 4 (formato UTA) | [`docs/Informe_APE6_Fase3_4.pdf`](docs/Informe_APE6_Fase3_4.pdf) |
| Registro de aportes y evidencias | [`Evidencias_Colaboracion/`](Evidencias_Colaboracion/) |

## Estructura
```
APE6_IHC/
├── README.md
├── prototipo/                       Enlace y respaldo de CaféU v3
├── Fase1-Planificacion/             Plan, consentimiento, tareas, hoja SUS, informe Fase 1
├── Fase2-Pilotaje/                  P1–P3 del pilotaje, métricas, ajustes V1→V2, heurísticas, hallazgos, informe Fase 2
├── resultados/                      Fase 3: P1–P3, heurística-*.md (1–4), consolidado, métricas y datos
├── docs/                            Protocolo Fase 3, criterios técnicos, backlog, conclusiones, informe Fases 3–4
└── Evidencias_Colaboracion/         Registro de aportes y documentos de evidencias
```

## Trabajo colaborativo
Fases 1 y 2: commits individuales de los cuatro integrantes. Fases 3 y 4: cada integrante trabajó en **su propia rama** y abrió un **Pull Request** hacia `main`; el backlog se registró como **GitHub Issues** (#1–#11). Detalle en [`Evidencias_Colaboracion/Registro_Aportes.md`](Evidencias_Colaboracion/Registro_Aportes.md).

En el repositorio no hay nombres, datos personales ni grabaciones de participantes; solo los códigos P1, P2 y P3.

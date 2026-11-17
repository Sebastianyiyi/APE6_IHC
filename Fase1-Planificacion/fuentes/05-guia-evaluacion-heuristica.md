# Guía de evaluación heurística · CaféU v3

**Responsable de este documento:** Acaro Ibujés Pedro Sebastián
**Método:** evaluación heurística con las 10 heurísticas de Nielsen [Nielsen, 1994], aplicada por los cuatro integrantes de forma **individual** y después consolidada.

## 1. Procedimiento
1. **Recorrido libre (5 min).** Cada evaluador explora el prototipo completo para entender su alcance.
2. **Recorrido guiado (20 min).** Recorre el flujo central (inicio → menú → detalle → pedido → hora de retiro → revisar → confirmación) y los estados de error: búsqueda sin resultados, producto agotado, hora no válida y fallo de envío (con el panel del moderador, parámetro `?prueba=1`).
3. **Registro.** Responde las diez preguntas de la sección 3 y anota cada problema en la tabla de la sección 4, con la pantalla, la evidencia y la severidad.
4. **Sin comentar con los demás** hasta que los cuatro hayan terminado, para no sesgar los hallazgos.
5. **Consolidación (Fase 2).** Se unen los problemas repetidos, se promedia la severidad y se triangula con lo observado en la prueba con usuarios.

## 2. Escala de severidad [Nielsen, 1994]

| Valor | Significado |
|---|---|
| 0 | No es un problema de usabilidad. |
| 1 | Cosmético: se corrige solo si hay tiempo. |
| 2 | Menor: prioridad baja. |
| 3 | Mayor: prioridad alta, conviene corregirlo antes de publicar. |
| 4 | Catastrófico: impide completar una tarea; se corrige obligatoriamente. |

La severidad considera **frecuencia** (¿a cuántos usuarios les pasaría?), **impacto** (¿se puede recuperar?) y **persistencia** (¿se repite cada vez?).

## 3. Preguntas por heurística (una por heurística, adaptadas a CaféU)

| H | Heurística | Pregunta para el evaluador | Dónde mirar | Cumple (Sí / Parcial / No) | Evidencia |
|---|---|---|---|---|---|
| H1 | Visibilidad del estado del sistema | ¿La persona sabe en todo momento en qué paso del pedido está, cuántos productos lleva y si su pedido se está enviando o ya se confirmó? | Indicador «Paso n de 4», contador del pedido, aviso de producto agregado, estado «procesando» y confirmación | | |
| H2 | Relación entre el sistema y el mundo real | ¿Los nombres, precios, tamaños y horas usan el lenguaje y los formatos de la cafetería (dólares con coma, «mediano», «retiro»)? | Tarjetas del menú, detalle, resumen | | |
| H3 | Control y libertad del usuario | ¿Se puede volver atrás, editar o deshacer (por ejemplo, recuperar un producto quitado) sin perder lo ya elegido? | Botones de volver, «Deshacer», «Editar pedido» | | |
| H4 | Consistencia y estándares | ¿Los botones principales, los enlaces de volver y los mensajes tienen la misma forma, posición y redacción en todas las pantallas? | Comparar las siete pantallas | | |
| H5 | Prevención de errores | ¿La interfaz evita errores antes de que ocurran (producto agotado no seleccionable, cantidad limitada a 1–9, rango de horas visible)? | Empanada agotada, selector de cantidad, campo de hora | | |
| H6 | Reconocer antes que recordar | ¿La persona puede ver lo que eligió (tamaño, leche, cantidad, hora) en cada paso sin tener que recordarlo? | Detalle del pedido y resumen final | | |
| H7 | Flexibilidad y eficiencia de uso | ¿Hay atajos para quien ya conoce la aplicación (buscador sin tildes y con sinónimos, filtros, «lo antes posible», teclado)? | Buscador, filtros, opción de retiro, navegación con Tab | | |
| H8 | Diseño estético y minimalista | ¿Cada pantalla muestra solo la información necesaria para el paso actual, sin elementos que distraigan? | Inicio, menú y detalle | | |
| H9 | Ayudar a reconocer, diagnosticar y recuperarse de errores | ¿Los mensajes de error dicen qué pasó y cómo resolverlo, en lenguaje sencillo y junto al campo afectado? | Hora no válida, búsqueda sin resultados, fallo de envío | | |
| H10 | Ayuda y documentación | ¿Hay ayuda breve en el lugar donde se necesita (tiempo de preparación, rango de horas, «pagas al retirar»)? | Textos de apoyo de inicio, hora de retiro y revisión | | |

## 4. Registro de problemas (uno por fila)

| N.º | Heurística | Pantalla o estado | Descripción del problema | Evidencia (qué se ve) | Severidad (0–4) | Recomendación |
|---|---|---|---|---|---|---|
| 1 | | | | | | |
| 2 | | | | | | |
| 3 | | | | | | |
| 4 | | | | | | |
| 5 | | | | | | |

**Evaluador:** __________ **Fecha:** ___/___/2026 **Duración:** ___ min

## 5. Consolidación (plantilla para la Fase 2)

| ID | Problema consolidado | Heurística | Evaluadores que lo encontraron (de 4) | Severidad promedio | ¿Observado con usuarios? (tarea) | Prioridad |
|---|---|---|---|---|---|---|
| HP-01 | | | | | | |

*Prioridad:* **Alta** si la severidad promedio es ≥ 3 o si se confirmó con usuarios; **Media** si es 2 o la encontraron dos o más evaluadores; **Baja** en los demás casos.

# Consolidación heurística y comparación con el pilotaje

**Responsable:** Acaro Ibujés Pedro Sebastián (observador) · **Insumos:** las cuatro evaluaciones individuales de esta carpeta y las hojas P1–P3.

## 1. Resumen de las evaluaciones individuales

| Evaluador | Fecha | Problemas | Severidad promedio | Heurísticas con «No» |
|---|---|---|---|---|
| González Álvarez Vladimir Humberto | 13/11/2026 | 6 | 1,8 | — |
| Mora Beltrán Santiago Sebastián | 13/11/2026 | 5 | 2,2 | H3 |
| Vinces Cueva Boris Yussef | 14/11/2026 | 5 | 2 | H9 |
| Acaro Ibujés Pedro Sebastián | 14/11/2026 | 6 | 1,7 | H5 |

Los cuatro evaluadores registraron 22 problemas que, al unir los repetidos, se reducen a **11 problemas distintos**.

## 2. Problemas consolidados y triangulación

| ID | Heurística | Problema | Evaluadores (de 4) | Severidad promedio | ¿Observado en el pilotaje? | Prioridad |
|---|---|---|---|---|---|---|
| HP-01 | H5 | El retiro «Lo antes posible» viene preseleccionado y en la revisión la hora aparece en texto secundario; se puede confirmar sin decidir la hora. | 4 (Gonzalez, Mora, Vinces, Acaro) | 2,75 | Sí · T6 · P2: Error crítico: confirmó con retiro 09:51 en lugar de 11:15. | Alta |
| HP-02 | H3 | «Quitar» está junto al control de cantidad y borra la línea completa sin confirmación; se confunde con restar una unidad. | 3 (Gonzalez, Mora, Acaro) | 2,33 | Sí · T5 · P1, P3: Error no crítico: pulsaron «Quitar» para restar una unidad. | Alta |
| HP-03 | H9 | El campo de hora depende del formato del equipo (a. m./p. m.); si falta ese dato el mensaje solo dice «Ingresa la hora…», sin explicar qué falta. | 2 (Gonzalez, Vinces) | 2,50 | Sí · T6 · P3: Error no crítico: hora sin a. m./p. m.; mensaje no orientó. | Alta |
| HP-04 | H6 | Las opciones de leche quedan debajo del pliegue y la leche entera viene marcada por defecto; se puede agregar sin verlas. | 2 (Mora, Acaro) | 2,00 | Sí · T3 · P3: Error no crítico: agregó con leche entera y tuvo que rehacer. | Alta |
| HP-05 | H3 | El aviso con «Deshacer» desaparece a los 6 s y aparece en la parte inferior, fuera de la zona donde se está mirando. | 2 (Gonzalez, Vinces) | 2,00 | Sí · T5 · P3: No vio «Deshacer»; volvió al menú a agregar un pan. | Media |
| HP-06 | H6 | La línea del pedido muestra el subtotal (p. ej. $1,20 por 2 panes) sin precio unitario. | 2 (Vinces, Acaro) | 1,50 | Sí · T4 · P1: Duda verbal, sin error. | Media |
| HP-07 | H10 | No hay ayuda sobre cómo se paga, cómo cancelar un pedido o qué pasa si no se retira. | 2 (Gonzalez, Vinces) | 1,00 | No | Media |
| HP-08 | H2 | Las tarjetas muestran «desde $2,00»; el precio final solo se conoce al personalizar. | 2 (Mora, Acaro) | 1,00 | No | Media |
| HP-09 | H3 | Una vez confirmado, el pedido no se puede cancelar ni editar desde la aplicación. | 1 (Mora) | 2,00 | No | Media |
| HP-10 | H10 | La última hora de retiro (17:45) solo se informa en el paso 3; en el inicio solo aparece el cierre (18:00). | 1 (Gonzalez) | 1,00 | No | Baja |
| HP-11 | H7 | El buscador acepta sin tildes y sinónimos, pero no lo indica ni sugiere términos. | 1 (Acaro) | 1,00 | No | Baja |
| HP-12 | H2 | Buscó la empanada con el filtro «Bebidas» antes de «Comida». | 0 | — | Sí · T2 · P3: error no crítico | Baja |

**Regla de prioridad (Fase 1):** *Alta* si se confirmó con usuarios mediante un error o si la severidad promedio es ≥ 3; *Media* si la severidad es 2, si lo encontraron dos o más evaluadores o si en el pilotaje solo apareció como duda; *Baja* en los demás casos.

## 3. Lectura de la comparación

- **Confirmados por ambos métodos (evidencia más fuerte):** HP-01 retiro preseleccionado, HP-02 «Quitar» borra la línea, HP-03 campo de hora y HP-04 leche fuera de la vista. Los cuatro produjeron errores reales en T3, T5 o T6.
- **Solo heurísticos:** búsqueda sin indicaciones, ayuda general, precio «desde», cancelación y última hora de retiro. Ninguna tarea recorre esas zonas (nadie usó el buscador), por lo que la inspección cubre lo que el pilotaje no mide.
- **Solo en el pilotaje:** HP-12 (filtro equivocado en T2). Ningún evaluador lo marcó porque el equipo conoce la categoría de cada producto.
- **Severidad:** el problema con mayor acuerdo (4 de 4) es también el único que generó un error crítico, lo que respalda su severidad promedio de 2,75.

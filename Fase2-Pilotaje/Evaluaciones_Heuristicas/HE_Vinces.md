# Evaluación heurística individual · Vinces Cueva Boris Yussef

**Prototipo:** CaféU v3 · **Fecha:** 14/11/2026 · **Duración:** 35 min · **Método:** 10 heurísticas de Nielsen, severidad 0–4
**Procedimiento:** recorrido libre (5 min) y recorrido guiado del flujo completo y de los estados de error, de forma individual y sin comentar con el resto del grupo hasta la consolidación.

## 1. Cumplimiento por heurística

| H | Heurística | Cumple | Evidencia |
|---|---|---|---|
| H1 | Visibilidad del estado del sistema | Sí | Pasos, contador y avisos visibles. |
| H2 | Relación con el mundo real | Parcial | El formato de hora depende del equipo. |
| H3 | Control y libertad del usuario | Parcial | «Deshacer» existe pero es breve. |
| H4 | Consistencia y estándares | Sí | Consistente. |
| H5 | Prevención de errores | Parcial | Hora por defecto. |
| H6 | Reconocer antes que recordar | Parcial | Subtotales sin precio unitario. |
| H7 | Flexibilidad y eficiencia de uso | Sí | Búsqueda y filtros. |
| H8 | Diseño estético y minimalista | Sí | Sin elementos innecesarios. |
| H9 | Reconocer, diagnosticar y recuperarse de errores | No | El mensaje de hora incompleta no orienta. |
| H10 | Ayuda y documentación | Parcial | Ayuda puntual. |

## 2. Problemas encontrados

| N.º | Heurística | Pantalla | Descripción y evidencia | Severidad | Recomendación |
|---|---|---|---|---|---|
| 1 | H9 · Reconocer, diagnosticar y recuperarse de errores | Hora de retiro | Probé escribir solo «11:15» en la laptop con formato de 12 h: el campo queda incompleto y el mensaje «Ingresa la hora a la que pasarás a retirar» confunde porque la hora ya está escrita. | 3 (Mayor) | Reemplazar el campo nativo por botones de hora o validar el formato con un mensaje específico. |
| 2 | H5 · Prevención de errores | Hora de retiro / Revisar | La opción por defecto es razonable para la mayoría, pero en la revisión el dato de retiro no resalta. | 2 (Menor) | Resaltar la línea «Retiro» con un color o un ícono de reloj. |
| 3 | H6 · Reconocer antes que recordar | Mi pedido | La línea «Pan de yuca $1,20» con cantidad 2 no dice si es el precio por unidad o el subtotal. | 2 (Menor) | Mostrar «2 × $0,60 = $1,20». |
| 4 | H3 · Control y libertad del usuario | Mi pedido | El «Deshacer» se va rápido; en mi prueba lo perdí al mover el mouse a la lista. | 2 (Menor) | Mantener el aviso visible hasta otra acción. |
| 5 | H10 · Ayuda y documentación | Global | No se explica qué pasa si llego tarde a retirar. | 1 (Cosmético) | Agregar una nota en la confirmación. |

**Total de problemas:** 5 · **Severidad promedio:** 2

**Evaluador:** Vinces Cueva Boris Yussef

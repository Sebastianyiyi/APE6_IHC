# Evaluación heurística individual · González Álvarez Vladimir Humberto

**Prototipo:** CaféU v3 · **Fecha:** 13/11/2026 · **Duración:** 32 min · **Método:** 10 heurísticas de Nielsen, severidad 0–4
**Procedimiento:** recorrido libre (5 min) y recorrido guiado del flujo completo y de los estados de error, de forma individual y sin comentar con el resto del grupo hasta la consolidación.

## 1. Cumplimiento por heurística

| H | Heurística | Cumple | Evidencia |
|---|---|---|---|
| H1 | Visibilidad del estado del sistema | Parcial | Indicador de pasos y contador del pedido claros; la hora de retiro en la revisión es poco visible. |
| H2 | Relación con el mundo real | Sí | Precios en dólares con coma, tamaños con onzas, lenguaje de cafetería. |
| H3 | Control y libertad del usuario | Parcial | Hay «Deshacer», pero dura poco. |
| H4 | Consistencia y estándares | Sí | Botón principal y enlace secundario en la misma posición en todas las pantallas. |
| H5 | Prevención de errores | Parcial | Agotado no seleccionable y cantidad 1–9; la hora preseleccionada no previene errores. |
| H6 | Reconocer antes que recordar | Sí | El resumen repite tamaño, leche y cantidad. |
| H7 | Flexibilidad y eficiencia de uso | Sí | Búsqueda tolerante y filtros; retiro rápido. |
| H8 | Diseño estético y minimalista | Sí | Pantallas limpias, una acción principal. |
| H9 | Reconocer, diagnosticar y recuperarse de errores | Parcial | Mensajes de hora claros para rango, no para formato incompleto. |
| H10 | Ayuda y documentación | Parcial | Ayudas puntuales, sin ayuda general. |

## 2. Problemas encontrados

| N.º | Heurística | Pantalla | Descripción y evidencia | Severidad | Recomendación |
|---|---|---|---|---|---|
| 1 | H5 · Prevención de errores | Hora de retiro / Revisar | En el paso 3 la opción «Lo antes posible» ya está marcada y el botón «Revisar y confirmar» queda activo; en la revisión la hora de retiro está en una línea secundaria con la misma fuente que el resto. Un usuario apurado puede confirmar sin decidir la hora. | 3 (Mayor) | No preseleccionar; obligar a elegir entre las dos opciones o destacar la hora en la revisión. |
| 2 | H3 · Control y libertad del usuario | Mi pedido | «Quitar» está a la derecha del botón +, con el mismo peso visual, y elimina todas las unidades de la línea. | 2 (Menor) | Separar «Quitar» del control de cantidad o usar un ícono de papelera con confirmación. |
| 3 | H9 · Reconocer, diagnosticar y recuperarse de errores | Hora de retiro | Con Windows en formato de 12 horas el campo pide a. m./p. m.; si no se completa, el mensaje no dice qué falta. | 2 (Menor) | Usar un selector de horas en intervalos de 15 min o un mensaje específico. |
| 4 | H3 · Control y libertad del usuario | Mi pedido | El aviso «Deshacer» dura 6 s y aparece abajo; si la persona está mirando la lista no lo nota. | 2 (Menor) | Mantener el aviso hasta la siguiente acción o mostrar «Deshacer» en la misma línea. |
| 5 | H10 · Ayuda y documentación | Global | No hay sección de ayuda: no se explica cómo cancelar ni qué pasa si no se retira el pedido. | 1 (Cosmético) | Agregar una ayuda breve en la confirmación. |
| 6 | H10 · Ayuda y documentación | Inicio | La hora límite de retiro (17:45) no aparece en el inicio. | 1 (Cosmético) | Agregar «Último retiro 17:45» al aviso de horario. |

**Total de problemas:** 6 · **Severidad promedio:** 1,8

**Evaluador:** González Álvarez Vladimir Humberto

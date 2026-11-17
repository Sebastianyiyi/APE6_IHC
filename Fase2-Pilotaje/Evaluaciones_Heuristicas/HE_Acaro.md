# Evaluación heurística individual · Acaro Ibujés Pedro Sebastián

**Prototipo:** CaféU v3 · **Fecha:** 14/11/2026 · **Duración:** 30 min · **Método:** 10 heurísticas de Nielsen, severidad 0–4
**Procedimiento:** recorrido libre (5 min) y recorrido guiado del flujo completo y de los estados de error, de forma individual y sin comentar con el resto del grupo hasta la consolidación.

## 1. Cumplimiento por heurística

| H | Heurística | Cumple | Evidencia |
|---|---|---|---|
| H1 | Visibilidad del estado del sistema | Parcial | Falta destacar la hora de retiro en la revisión. |
| H2 | Relación con el mundo real | Sí | Lenguaje cercano. |
| H3 | Control y libertad del usuario | Parcial | Quitar borra todo; Deshacer ayuda. |
| H4 | Consistencia y estándares | Sí | Componentes repetidos igual. |
| H5 | Prevención de errores | No | Hora preseleccionada y leche por defecto. |
| H6 | Reconocer antes que recordar | Parcial | Leches fuera de la vista. |
| H7 | Flexibilidad y eficiencia de uso | Parcial | Atajos ocultos en el buscador. |
| H8 | Diseño estético y minimalista | Sí | Limpio. |
| H9 | Reconocer, diagnosticar y recuperarse de errores | Sí | Mensajes de rango claros. |
| H10 | Ayuda y documentación | Parcial | Sin ayuda general. |

## 2. Problemas encontrados

| N.º | Heurística | Pantalla | Descripción y evidencia | Severidad | Recomendación |
|---|---|---|---|---|---|
| 1 | H5 · Prevención de errores | Hora de retiro / Revisar | Es posible confirmar el pedido sin haber elegido conscientemente la hora; para una app de retiro, la hora es tan importante como el producto. | 3 (Mayor) | Hacer obligatoria la elección de la hora o mostrarla en el botón «Confirmar pedido · 09:51». |
| 2 | H3 · Control y libertad del usuario | Mi pedido | El botón «Quitar» elimina la línea completa; el nombre no aclara que borra todas las unidades. | 2 (Menor) | Cambiar a «Eliminar todo» o usar un ícono con confirmación. |
| 3 | H6 · Reconocer antes que recordar | Detalle del producto | La leche entera viene marcada; si la persona no baja, agrega algo distinto a lo que quería sin darse cuenta. | 2 (Menor) | Mostrar un resumen de la personalización junto al botón de agregar. |
| 4 | H6 · Reconocer antes que recordar | Mi pedido | En el pedido no se ve el precio unitario de cada producto. | 1 (Cosmético) | Agregar el precio unitario en gris. |
| 5 | H7 · Flexibilidad y eficiencia de uso | Menú | El buscador entiende «capu» o «cafe» sin tilde, pero no lo dice; nadie sabe que existe esa ayuda. | 1 (Cosmético) | Agregar ejemplos en el marcador de posición: «Busca: capuchino, pan…». |
| 6 | H2 · Relación con el mundo real | Menú | «Desde $2,00» puede leerse como precio final. | 1 (Cosmético) | Mantener «desde» en gris y el precio final en el detalle. |

**Total de problemas:** 6 · **Severidad promedio:** 1,7

**Evaluador:** Acaro Ibujés Pedro Sebastián

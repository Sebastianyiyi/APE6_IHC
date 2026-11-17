# Evaluación heurística individual · Mora Beltrán Santiago Sebastián

**Prototipo:** CaféU v3 · **Fecha:** 13/11/2026 · **Duración:** 28 min · **Método:** 10 heurísticas de Nielsen, severidad 0–4
**Procedimiento:** recorrido libre (5 min) y recorrido guiado del flujo completo y de los estados de error, de forma individual y sin comentar con el resto del grupo hasta la consolidación.

## 1. Cumplimiento por heurística

| H | Heurística | Cumple | Evidencia |
|---|---|---|---|
| H1 | Visibilidad del estado del sistema | Parcial | El paso actual se ve; la hora elegida no se destaca. |
| H2 | Relación con el mundo real | Sí | Nombres de productos y precios como en la cafetería. |
| H3 | Control y libertad del usuario | No | Quitar borra todo y no se puede cancelar un pedido confirmado. |
| H4 | Consistencia y estándares | Parcial | «Quitar» se ve igual que los botones de cantidad. |
| H5 | Prevención de errores | Parcial | La hora por defecto no previene errores. |
| H6 | Reconocer antes que recordar | Parcial | Las leches quedan fuera de la vista. |
| H7 | Flexibilidad y eficiencia de uso | Sí | Filtros y búsqueda. |
| H8 | Diseño estético y minimalista | Sí | Diseño sobrio. |
| H9 | Reconocer, diagnosticar y recuperarse de errores | Sí | Los mensajes de hora dicen el rango válido. |
| H10 | Ayuda y documentación | Parcial | Textos de apoyo, sin ayuda general. |

## 2. Problemas encontrados

| N.º | Heurística | Pantalla | Descripción y evidencia | Severidad | Recomendación |
|---|---|---|---|---|---|
| 1 | H5 · Prevención de errores | Hora de retiro / Revisar | Si no toco nada en «¿Cuándo pasas a retirar?» el pedido sale para lo antes posible. Para alguien que quería programar, el error solo se nota después de confirmar. | 3 (Mayor) | Mostrar la hora de retiro en grande en la revisión y en el botón de confirmar. |
| 2 | H3 · Control y libertad del usuario | Mi pedido | Esperaba que «Quitar» quitara una unidad; borró los dos panes. Es fácil de confundir porque está pegado al − y al +. | 3 (Mayor) | Renombrar a «Eliminar» y alejarlo del contador, o pedir confirmación. |
| 3 | H6 · Reconocer antes que recordar | Detalle del producto | En pantallas bajas, la sección «Tipo de leche» queda fuera de la vista; nada indica que hay más opciones abajo. | 2 (Menor) | Mostrar las opciones en dos columnas o un indicio de desplazamiento. |
| 4 | H2 · Relación con el mundo real | Menú | En el menú el capuchino dice «desde $2,00»; puede confundirse con el precio final. | 1 (Cosmético) | Mantener «desde», pero mostrar el precio final en el detalle de forma destacada (ya ocurre en el botón). |
| 5 | H3 · Control y libertad del usuario | Confirmación | Después de confirmar no hay forma de cancelar o corregir el pedido. | 2 (Menor) | Permitir cancelar durante los primeros minutos. |

**Total de problemas:** 5 · **Severidad promedio:** 2,2

**Evaluador:** Mora Beltrán Santiago Sebastián

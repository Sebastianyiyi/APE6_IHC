# Backlog de mejoras · Texto de los GitHub Issues

**Responsable:** Mora Beltrán Santiago Sebastián · Los issues se crean **en este orden** para que su número coincida con el backlog del README (#1 a #11).

## Issue #1

**Título:** `[P1] C-01 · Hora de retiro / Revisar y confirmar`

**Descripción:**

```
Hallazgos: H-01 (severidad consensuada 4)
Componente: Hora de retiro / Revisar y confirmar
Cambio: Ninguna opción de retiro viene marcada; «Revisar y confirmar» se habilita solo después de elegir; el botón final muestra la hora («Confirmar pedido · 11:15»).
Estándar: Nielsen H5 y H1; WCAG 2.1 3.3.4 Prevención de errores (AA); ISO 9241-11 eficacia
Criterio de aceptación: Repetir T6 con 3 usuarios: 0 errores críticos y la hora dicha coincide con la confirmada.
Evidencia: resultados/heuristica-consolidado.md y resultados/P1.md–P3.md
```

## Issue #2

**Título:** `[P1] C-02 · Aviso con «Deshacer»`

**Descripción:**

```
Hallazgos: H-02 (severidad consensuada 3)
Componente: Aviso con «Deshacer»
Cambio: El aviso permanece hasta la siguiente acción del usuario (sin cierre automático) y aparece encima de la lista, con foco accesible.
Estándar: WCAG 2.1 2.2.1 Tiempo ajustable (A); Nielsen H3
Criterio de aceptación: T8: 3/3 recuperan el producto sin el menú.
Evidencia: resultados/heuristica-consolidado.md y resultados/P1.md–P3.md
```

## Issue #3

**Título:** `[P2] C-03 · Mi pedido · «Quitar»`

**Descripción:**

```
Hallazgos: H-03 (severidad consensuada 3)
Componente: Mi pedido · «Quitar»
Cambio: «Quitar» pasa a «Eliminar», con ícono, separado al menos 24 px del contador y distinto en estilo de − y +.
Estándar: Nielsen H3 y H4; WCAG 2.1 2.5.5 Tamaño del objetivo (AAA, recomendado)
Criterio de aceptación: T5: 0 usos de «Eliminar» para restar una unidad.
Evidencia: resultados/heuristica-consolidado.md y resultados/P1.md–P3.md
```

## Issue #4

**Título:** `[P2] C-04 · Hora de retiro · campo de hora`

**Descripción:**

```
Hallazgos: H-04 (severidad consensuada 3)
Componente: Hora de retiro · campo de hora
Cambio: El campo nativo se reemplaza por un selector de franjas de 15 min (09:51–17:45) y, si hay error, el mensaje dice qué falta y cómo corregirlo.
Estándar: WCAG 2.1 3.3.1 Identificación de errores (A) y 3.3.3 Sugerencias ante errores (AA); Nielsen H9
Criterio de aceptación: T6: 0 mensajes de hora incompleta; mediana ≤ 90 s.
Evidencia: resultados/heuristica-consolidado.md y resultados/P1.md–P3.md
```

## Issue #5

**Título:** `[P3] C-05 · Detalle del producto`

**Descripción:**

```
Hallazgos: H-05 (severidad consensuada 2)
Componente: Detalle del producto
Cambio: Las opciones de tamaño y leche caben en la primera vista en 1366 × 657 o el botón de agregar muestra el resumen («Mediano · almendra · $2,70»).
Estándar: Nielsen H6 y H5; WCAG 2.1 3.3.2 Etiquetas o instrucciones (A)
Criterio de aceptación: T3: 0 productos agregados con una leche no elegida.
Evidencia: resultados/heuristica-consolidado.md y resultados/P1.md–P3.md
```

## Issue #6

**Título:** `[P3] C-06 · Mi pedido · línea`

**Descripción:**

```
Hallazgos: H-06 (severidad consensuada 2)
Componente: Mi pedido · línea
Cambio: Cada línea con más de una unidad muestra «cantidad × precio unitario = subtotal».
Estándar: Nielsen H6 y H2; ISO 9241-11 eficiencia
Criterio de aceptación: T4: ninguna duda verbal sobre el precio unitario.
Evidencia: resultados/heuristica-consolidado.md y resultados/P1.md–P3.md
```

## Issue #7

**Título:** `[P3] C-07 · Menú · filtros`

**Descripción:**

```
Hallazgos: H-07 (severidad consensuada 2)
Componente: Menú · filtros
Cambio: El borde de los filtros no seleccionados alcanza al menos 3:1 (p. ej. #8D7B73, 4,03:1 sobre blanco).
Estándar: WCAG 2.1 1.4.11 Contraste de componentes (AA)
Criterio de aceptación: Medición con un verificador de contraste ≥ 3:1.
Evidencia: resultados/heuristica-consolidado.md y resultados/P1.md–P3.md
```

## Issue #8

**Título:** `[P4] C-08 · Confirmación`

**Descripción:**

```
Hallazgos: H-08 (severidad consensuada 2)
Componente: Confirmación
Cambio: Botón «Cancelar pedido» visible durante los 2 primeros minutos tras confirmar, con confirmación.
Estándar: Nielsen H3; WCAG 2.1 3.3.4 (AA)
Criterio de aceptación: Prueba de cancelación: el pedido pasa a «Cancelado».
Evidencia: resultados/heuristica-consolidado.md y resultados/P1.md–P3.md
```

## Issue #9

**Título:** `[P4] C-09 · Menú · buscador`

**Descripción:**

```
Hallazgos: H-09 (severidad consensuada 1)
Componente: Menú · buscador
Cambio: El marcador de posición muestra ejemplos («Busca: capuchino, cacao, pan…»).
Estándar: Nielsen H7 y H10
Criterio de aceptación: Revisión visual del marcador de posición.
Evidencia: resultados/heuristica-consolidado.md y resultados/P1.md–P3.md
```

## Issue #10

**Título:** `[P4] C-10 · Inicio y confirmación · ayuda`

**Descripción:**

```
Hallazgos: H-10, H-12 (severidad consensuada 1)
Componente: Inicio y confirmación · ayuda
Cambio: El inicio muestra «Último retiro 17:45» y la confirmación incluye ayuda de 2 líneas sobre pago y retraso.
Estándar: Nielsen H10; ISO 9241-11 satisfacción
Criterio de aceptación: Revisión del contenido en inicio y confirmación.
Evidencia: resultados/heuristica-consolidado.md y resultados/P1.md–P3.md
```

## Issue #11

**Título:** `[P4] C-11 · Menú · tarjetas y filtros`

**Descripción:**

```
Hallazgos: H-11, H-13 (severidad consensuada 1)
Componente: Menú · tarjetas y filtros
Cambio: «desde» en texto secundario junto al precio y filtros con ícono (taza/plato) además del texto.
Estándar: Nielsen H2 y H6
Criterio de aceptación: T2: 0 búsquedas de comida en «Bebidas».
Evidencia: resultados/heuristica-consolidado.md y resultados/P1.md–P3.md
```

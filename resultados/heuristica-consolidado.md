# Matriz consolidada de hallazgos y triangulación · Fase 4

**Responsable:** Acaro Ibujés Pedro Sebastián (observador) · **Insumos:** `heuristica-*.md` (4 evaluadores) y `P1.md`–`P3.md`.

La severidad consensuada se acordó en reunión del grupo a partir de las severidades individuales (1–4) y de la evidencia con usuarios: un problema con error crítico observado no puede quedar por debajo de 3.

## 1. Matriz consolidada

| ID | Heurística | Componente | Problema | Evaluadores (sev.) | Severidad consensuada | Evidencia con usuarios | Propuesta de mejora |
|---|---|---|---|---|---|---|---|
| **H-01** | H5 | Hora de retiro / Revisar y confirmar | El retiro «Lo antes posible» viene preseleccionado y la hora aparece como texto secundario en la revisión: se puede confirmar sin decidir la hora. | 4/4 (González 4, Mora 3, Vinces 3, Acaro 4) | **4** | T6: P3 confirmó con retiro 09:51 (error crítico). En el pilotaje: P2, mismo error. | Sin preselección; hora visible en el botón de confirmar. |
| **H-02** | H3 | Aviso con «Deshacer» | El aviso con «Deshacer» desaparece a los 6 s y se muestra abajo, lejos de la lista; si no se ve a tiempo no hay forma de recuperar lo quitado. | 3/4 (González 3, Mora 3, Vinces 2) | **3** | T8: P2 no vio el aviso y no pudo recuperar el producto (error crítico). | Aviso persistente hasta la siguiente acción, junto a la lista. |
| **H-03** | H3 | Mi pedido · «Quitar» | «Quitar» está junto al control de cantidad y borra la línea completa; se usa para restar una unidad. | 3/4 (González 2, Mora 3, Acaro 3) | **3** | T5: P1 y P2 pulsaron «Quitar» para restar una unidad (2 errores no críticos). | Renombrar a «Eliminar» y separarlo del contador. |
| **H-04** | H9 | Hora de retiro · campo de hora | Con el equipo en 12 h el campo queda incompleto sin a. m./p. m. y el mensaje «Ingresa la hora…» no dice qué falta. | 2/4 (González 3, Vinces 3) | **3** | T6: P2 escribió la hora sin a. m.; el mensaje no orientó (error no crítico, 132 s). | Selector de franjas de 15 min y mensaje específico. |
| **H-05** | H6 | Detalle del producto | Las opciones de leche quedan bajo el pliegue y la leche entera viene marcada; se agrega sin verlas. | 2/4 (Mora 2, Acaro 2) | **2** | T3: P2 agregó con leche entera y rehízo el producto (error no crítico, 102 s). | Opciones visibles y resumen junto al botón de agregar. |
| **H-06** | H6 | Mi pedido · línea | La línea muestra el subtotal ($1,20 por 2 panes) sin precio unitario. | 2/4 (Vinces 2, Acaro 2) | **2** | T4: P2 dudó si $1,20 era el precio de cada pan (duda, sin error). | Mostrar «2 × $0,60 = $1,20». |
| **H-07** | H4 | Menú · filtros | El borde de los filtros no seleccionados tiene un contraste de 1,63:1 con el fondo (WCAG 1.4.11 pide 3:1). | 1/4 (Vinces 2) | **2** | No se observó con usuarios. | Borde de los filtros con contraste ≥ 3:1. |
| **H-08** | H3 | Confirmación | Un pedido confirmado no se puede cancelar ni editar. | 1/4 (Mora 2) | **2** | No se observó (ninguna tarea cancela un pedido). | Permitir cancelar en los primeros minutos. |
| **H-09** | H7 | Menú · buscador | El buscador acepta sin tildes y sinónimos («cacao», «cafe»), pero no lo indica. | 1/4 (Acaro 1) | **1** | No se observó como problema: en T7 los 3 encontraron el producto escribiendo (3/3). | Ejemplos en el marcador de posición del buscador. |
| **H-10** | H10 | Global | No hay ayuda sobre pago, cancelación o retraso en el retiro. | 2/4 (González 1, Vinces 1) | **1** | No se observó. | Ayuda breve sobre pago, retiro y cancelación. |
| **H-11** | H2 | Menú · tarjetas | Las tarjetas muestran «desde $2,00»; el precio final solo aparece al personalizar. | 2/4 (Mora 1, Acaro 1) | **1** | No se observó (nadie respondió con el precio «desde»). | Etiqueta «desde» en gris y precio final destacado. |
| **H-12** | H10 | Inicio | La última hora de retiro (17:45) solo se informa en el paso 3. | 1/4 (González 1) | **1** | No se observó. | Mostrar «Último retiro 17:45» en el inicio. |
| **H-13** | H2 | Menú · filtros | Se busca un producto de comida con el filtro «Bebidas». | 0/4 | **1** | T2: P1 buscó la empanada con el filtro «Bebidas» (error no crítico); en el pilotaje le pasó a P3. | Íconos o ejemplos en los filtros de categoría. |

## 2. Triangulación metodológica

- **Confirmado por ambos métodos (6):** H-01, H-02, H-03, H-04, H-05, H-06
- **Solo heurística (6):** H-07, H-08, H-09, H-10, H-11, H-12
- **Solo usuarios (1):** H-13

| ID | Heurística (analítico) | Usuarios (empírico) | Clasificación |
|---|---|---|---|
| H-01 | Sí · 4/4 (González 4, Mora 3, Vinces 3, Acaro 4) | Sí | Confirmado por ambos métodos |
| H-02 | Sí · 3/4 (González 3, Mora 3, Vinces 2) | Sí | Confirmado por ambos métodos |
| H-03 | Sí · 3/4 (González 2, Mora 3, Acaro 3) | Sí | Confirmado por ambos métodos |
| H-04 | Sí · 2/4 (González 3, Vinces 3) | Sí | Confirmado por ambos métodos |
| H-05 | Sí · 2/4 (Mora 2, Acaro 2) | Sí | Confirmado por ambos métodos |
| H-06 | Sí · 2/4 (Vinces 2, Acaro 2) | Sí | Confirmado por ambos métodos |
| H-07 | Sí · 1/4 (Vinces 2) | No | Solo heurística |
| H-08 | Sí · 1/4 (Mora 2) | No | Solo heurística |
| H-09 | Sí · 1/4 (Acaro 1) | No | Solo heurística |
| H-10 | Sí · 2/4 (González 1, Vinces 1) | No | Solo heurística |
| H-11 | Sí · 2/4 (Mora 1, Acaro 1) | No | Solo heurística |
| H-12 | Sí · 1/4 (González 1) | No | Solo heurística |
| H-13 | No | Sí | Solo usuarios |

## 3. Lectura

- Los seis problemas confirmados por ambos métodos concentran los dos errores críticos y los errores no críticos de la Fase 3: son la evidencia más fuerte y encabezan el backlog.
- El buscador, que el pilotaje no había probado, funcionó en T7 (3/3): la búsqueda sin tildes y con sinónimos cumple su objetivo; solo queda una mejora cosmética (H-09).
- Los problemas solo heurísticos están en zonas que ninguna tarea recorre (cancelación, ayuda) o son de accesibilidad visual (contraste de filtros) que un usuario no reporta.
- H-13 solo aparece con usuarios: el equipo conoce la categoría de cada producto y no lo detectó en la inspección.

# Matriz de seis tareas · Prueba con usuarios de CaféU v3

**Responsable de este documento:** Acaro Ibujés Pedro Sebastián (observador)
**Prototipo:** [CaféU v3](https://raw.githack.com/Sebastianyiyi/APE04_IHC/main/APE4-integral/prototipo/cafeu-v3.html) · respaldo local: [`prototipo/cafeu-v3.html`](../prototipo/cafeu-v3.html)
**Versión del documento:** 2 (ajustada después del ensayo interno del 11/11/2026)

El moderador lee cada escenario **tal como está escrito**, una sola vez y sin añadir explicaciones. Ningún escenario nombra botones, pantallas, iconos ni rótulos de la interfaz: describe una situación real y deja que el participante decida cómo resolverla.

## 1. Matriz de tareas

| ID | Tipo | Escenario que se lee al participante | Meta | Tiempo máximo | Criterio de éxito (observable) | Respuesta correcta |
|---|---|---|---|---|---|---|
| **T1** | Consulta | «Tienes un rato libre entre clases y quieres saber si te conviene pedir algo. Averigua cuánto tarda la cafetería en tener listo un pedido y hasta qué hora atiende hoy.» | 30 s | 60 s | Dice el tiempo de preparación **y** la hora de cierre, ambos correctos. | **Unos 10 minutos**; atiende **hasta las 18:00** (abierto de 07:00 a 18:00). |
| **T2** | Consulta | «Te gustaría acompañar tu bebida con una empanada de verde. ¿Puedes pedirla hoy? Si no se puede, dinos qué te indica la aplicación.» | 40 s | 80 s | Responde que **no** se puede y menciona el motivo que muestra el prototipo. | **No**: está **agotada** y **vuelve mañana**. |
| **T3** | Creación | «Quieres un capuchino mediano con leche de almendra. Déjalo listo en tu pedido y dinos cuánto cuesta.» | 75 s | 150 s | El pedido contiene **1 capuchino mediano con leche de almendra** y dice el precio correcto. | **$2,70** (2,00 + 0,40 mediano + 0,30 almendra). |
| **T4** | Creación | «Un amigo te pide que le lleves dos panes de yuca. Súmalos a tu pedido y dinos cuánto pagarías en total.» | 60 s | 120 s | El pedido contiene el capuchino de T3 **y 2 panes de yuca**, y dice el total correcto. | **$3,90** (2,70 + 2 × 0,60). |
| **T5** | Modificación | «Tu amigo te escribe: al final solo quiere un pan. Deja tu pedido como corresponde.» | 40 s | 80 s | El pedido queda con **1 capuchino y 1 pan de yuca**; el capuchino no se altera. | Total **$3,30**. |
| **T6** | Creación (cierre) | «Sales de clase a las 11:00. Haz que tu pedido esté listo para recogerlo a las 11:15, envíalo y dinos tu número de pedido y cuánto tendrás que pagar.» | 90 s | 180 s | Aparece la confirmación con retiro **a las 11:15** y dice el número y el monto correctos. | **N.º 031**, retiro **11:15**, paga **$3,30 al retirar**. |

**Mezcla de tareas:** dos de consulta (T1, T2) y cuatro que crean o modifican datos (T3 a T6), como pide la guía. T3 a T6 recorren el flujo central de CaféU: elegir y personalizar, sumar productos, ajustar cantidades, programar el retiro y confirmar.

**Regla del tiempo máximo:** el máximo es el doble de la meta en todas las tareas.

## 2. Cómo se fijaron las metas

En el ensayo interno (11/11/2026) un integrante que conoce el prototipo resolvió las seis tareas y se tomó su tiempo como **tiempo experto**. La meta para un usuario nuevo es aproximadamente 2,5 veces ese tiempo, redondeada a múltiplos de 5 s; el máximo es el doble de la meta.

| Tarea | Tiempo experto (ensayo) | Meta (≈ 2,5 × experto) | Máximo (2 × meta) |
|---|---|---|---|
| T1 | 11 s | 30 s | 60 s |
| T2 | 16 s | 40 s | 80 s |
| T3 | 31 s | 75 s | 150 s |
| T4 | 24 s | 60 s | 120 s |
| T5 | 15 s | 40 s | 80 s |
| T6 | 37 s | 90 s | 180 s |
| **Total** | **134 s** | **335 s (≈ 5,6 min)** | **670 s (≈ 11,2 min)** |

Con el máximo de las seis tareas (11,2 min) más consentimiento, SUS y cierre, la sesión cabe en 20 minutos (ver [06-guion-de-la-sesion.md](06-guion-de-la-sesion.md)).

## 3. Respuestas aceptadas y dónde se comprueban

Las respuestas salen del contenido fijo del prototipo, por lo que no cambian entre sesiones. Esta columna es solo para el equipo evaluador; nunca se lee al participante.

| Tarea | Respuestas aceptadas | Comprobación en el prototipo |
|---|---|---|
| T1 | «10 minutos», «unos diez minutos» **y** «hasta las 6», «hasta las 18:00». Si solo da uno de los dos datos, no es éxito. | Pantalla de inicio: aviso «Abierto hoy de 07:00 a 18:00» y «Preparamos cada pedido en unos 10 minutos». |
| T2 | «No, está agotada», «no hay, vuelve mañana». Decir solo «no» sin el motivo no cumple el criterio: se registra *No* y se anota la respuesta textual. | Menú: tarjeta de la empanada de verde con la etiqueta «Agotado» y la descripción «Vuelve mañana». |
| T3 | «$2,70», «2,70», «dos setenta». | Detalle del capuchino (tamaño mediano, leche de almendra) y pedido: 1 × Capuchino, «mediano, leche de almendra», $2,70. |
| T4 | «$3,90», «3,90», «tres noventa». | Pedido: Capuchino $2,70 + Pan de yuca × 2 $1,20 · Total $3,90. |
| T5 | Se verifica en pantalla, no se pregunta. | Pedido: Pan de yuca × 1 $0,60 · Total $3,30. |
| T6 | Número **exacto** «031» o «treinta y uno»; monto «$3,30». | Confirmación: «¡Pedido confirmado!», «N.º 031», «Retira a las 11:15», «Paga $3,30 al retirar en la cafetería». |

**Por qué N.º 031:** el prototipo asigna el número 031 al primer pedido confirmado desde que se cargó la página. Por eso el reinicio entre participantes es obligatorio (sección 6).

## 4. Pista permitida (única y neutral)

- **Texto exacto, igual para todas las tareas:** «Lee otra vez la situación con calma y fíjate en lo que tienes en pantalla.»
- **Cuándo:** solo si el participante la pide o si pasan **30 segundos sin avanzar**.
- **Cuántas veces:** una por tarea.
- **Efecto:** si completa la tarea después de la pista se registra **Con ayuda**; no cuenta como éxito.
- **Prohibido:** señalar la pantalla, nombrar botones o pantallas, decir «casi», «por ahí» o «muy bien», o reformular el escenario.

## 5. Estado de partida de cada tarea

T1 y T2 son independientes. T3 a T6 forman una cadena: cada una parte del pedido que dejó la anterior.

| Tarea | Estado con el que debe empezar | Si la tarea anterior terminó en *No* |
|---|---|---|
| T1 | Pantalla de inicio, pedido vacío (contador en 0). | — |
| T2 | Donde haya quedado el participante en T1; pedido vacío. | — |
| T3 | Pedido vacío. | Si en T2 agregó algo por error, el soporte técnico lo deja vacío antes de leer T3. |
| T4 | Pedido con 1 capuchino mediano con leche de almendra. | El soporte técnico deja el capuchino correcto en el pedido y devuelve la pantalla de inicio. |
| T5 | Pedido con el capuchino y 2 panes de yuca ($3,90). | El soporte técnico prepara ese pedido. |
| T6 | Pedido con el capuchino y 1 pan de yuca ($3,30). | El soporte técnico prepara ese pedido. |

Así un fallo en una tarea no arrastra a las siguientes y cada medición es comparable entre participantes. La preparación se hace con el participante mirando hacia el moderador y no se cronometra.

## 6. Reinicio entre participantes

El prototipo guarda el pedido solo en la memoria del navegador. Al terminar cada sesión el soporte técnico:

1. Detiene la grabación de audio, si el participante la autorizó.
2. Recarga la página (**F5**) usando el enlace público, sin parámetros adicionales.
3. Comprueba el **estado inicial**: pantalla de inicio, contador del pedido en **0**, hora del teléfono **9:41** y ningún aviso en pantalla.
4. Marca la casilla «Estado inicial comprobado» en la hoja del siguiente participante.

Si no se recarga, el siguiente participante vería el pedido anterior y en T6 obtendría N.º 032 en lugar de N.º 031.

## 7. Registro de ajustes de las tareas (versión 1 → versión 2)

| N.º | Versión 1 | Problema detectado en la revisión o el ensayo interno | Versión 2 |
|---|---|---|---|
| 1 | T3: «…elige el tamaño mediano y la leche de almendra en las opciones del producto.» | «Opciones del producto» orienta hacia un control de la interfaz. | «Quieres un capuchino mediano con leche de almendra. Déjalo listo en tu pedido…» |
| 2 | T5: «Quita un pan de yuca de tu pedido.» | «Quita» coincide con el rótulo del botón «Quitar», que además borra el producto completo: inducía la acción equivocada. | «…al final solo quiere un pan. Deja tu pedido como corresponde.» |
| 3 | T6: retiro a las 09:45. | Esa hora es anterior a la primera disponible (09:51): la tarea fallaría por diseño. | Retiro a las 11:15, después de una clase que termina a las 11:00. |
| 4 | T1 solo preguntaba el horario. | Era una consulta demasiado directa y similar a la del grupo de referencia. | Pide dos datos (preparación y cierre) dentro de una situación concreta. |
| 5 | Sin respuesta esperada en T5. | El moderador no sabía qué verificar. | Se verifica en pantalla: 1 capuchino + 1 pan de yuca, $3,30. |

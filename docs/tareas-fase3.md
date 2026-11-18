# Protocolo de la Fase 3 · Ajuste post-pilotaje (versión 2)

**Responsable:** González Álvarez Vladimir Humberto (soporte técnico) · **Base:** protocolo V1 de la Fase 1 y ajustes V1 → V2 de la Fase 2.

## 1. Brechas del pilotaje que motivan el ajuste

| Brecha detectada en la Fase 2 | Respuesta en la Fase 3 |
|---|---|
| Nadie usó el buscador: la función solo se evaluó por inspección. | **T7 (refuerzo):** encontrar un producto escribiendo, sin recorrer el menú. |
| La recuperación con «Deshacer» solo se observó de forma incidental (P1 en T5). | **T8 (refuerzo):** quitar un producto y recuperarlo sin volver al menú (prevención y recuperación de errores). |
| P3 pidió repetir T6 (C5). | Tarjeta impresa con el texto de cada tarea. |
| El error de P2 en T6 solo se detectó en la pantalla final (C4). | Campos «Hora confirmada» y «¿Abrió programar?» en la hoja. |
| La sesión de P3 duró 23 min (C7). | Instrucción previa del SUS y franjas de 25 min. |
| El formato de hora del equipo no estaba documentado. | Se registra el formato (12 h) y se usa el mismo equipo para todos. |

## 2. Tareas T1–T8

| ID | Tipo | Escenario (se lee y se entrega en tarjeta) | Meta / Máx. | Respuesta correcta | Origen |
|---|---|---|---|---|---|
| **T1** | Consulta | «Tienes un rato libre entre clases y quieres saber si te conviene pedir algo. Averigua cuánto tarda la cafetería en tener listo un pedido y hasta qué hora atiende hoy.» | 30 s / 60 s | Unos 10 min; hasta las 18:00 | Base |
| **T2** | Consulta | «Te gustaría acompañar tu bebida con una empanada de verde. ¿Puedes pedirla hoy? Si no se puede, dinos qué te indica la aplicación.» | 40 s / 80 s | No: agotada, vuelve mañana | Base |
| **T3** | Creación | «Quieres un capuchino mediano con leche de almendra. Déjalo listo en tu pedido y dinos cuánto cuesta.» | 75 s / 150 s | $2,70 | Base |
| **T4** | Creación | «Un amigo te pide que le lleves dos panes de yuca. Súmalos a tu pedido y dinos cuánto pagarías en total.» | 60 s / 120 s | Total $3,90 | Base |
| **T5** | Modificación | «Tu amigo te escribe: al final solo quiere un pan. Deja tu pedido como corresponde.» | 40 s / 80 s | Total $3,30 | Base |
| **T6** | Creación | «Sales de clase a las 11:00. Haz que tu pedido esté listo para recogerlo a las 11:15, envíalo y dinos tu número de pedido y cuánto tendrás que pagar.» | 90 s / 180 s | N.º 031; $3,30; retiro 11:15 | Base |
| **T7** | Consulta | «Hace frío y te recomendaron algo con cacao ecuatoriano. Sin recorrer todo el menú, encuéntralo escribiendo y dinos cómo se llama y cuánto cuesta en tamaño pequeño.» | 45 s / 90 s | Chocolate caliente; $1,75 (pequeño) | Refuerzo |
| **T8** | Modificación | «Agrega ese producto pequeño a tu pedido. Luego sácalo del pedido porque cambiaste de idea; enseguida te arrepientes: recupéralo sin volver a elegirlo desde el menú.» | 40 s / 80 s | Chocolate de vuelta en el pedido ($1,75) | Refuerzo |

**Criterios de éxito de los refuerzos.** T7: dice «Chocolate caliente» y «$1,75» habiéndolo encontrado con el buscador. T8: el producto vuelve al pedido sin pasar por el menú (con «Deshacer»). En ambos, ninguna instrucción nombra el buscador, el aviso ni sus botones.

## 3. Reinicio de estado (F5)

- **Entre participantes:** el soporte técnico recarga la página con **F5** desde el enlace público y comprueba el estado inicial (inicio, pedido en 0, hora 9:41, sin avisos). Se marca en la hoja.
- **Entre T6 y T7:** como T6 confirma el pedido, se recarga con **F5** antes de T7; T7 y T8 parten de un pedido vacío.
- **Cadena T3 → T6:** si una tarea termina en «No», el soporte técnico deja preparado el estado de partida de la siguiente.
- **Verificación:** el primer pedido confirmado de cada sesión debe ser N.º 031.

## 4. Roles del laboratorio

| Rol | Responsable |
|---|---|
| Moderador | Mora Beltrán Santiago Sebastián |
| Usuario | Participante externo P1, P2 o P3 |
| Cronometrista (métricas) | Vinces Cueva Boris Yussef |
| Observador | Acaro Ibujés Pedro Sebastián |
| Soporte técnico (reinicio F5 y estados) | González Álvarez Vladimir Humberto |

## 5. Escala de severidad para la evaluación heurística (1–4)

Cada problema se califica en **Frecuencia (F)**, **Impacto (I)** y **Persistencia (P)**, de 1 a 3 cada uno [Nielsen, 1995]. La severidad es: F + I + P = 3–4 → **1 Cosmético**; 5–6 → **2 Menor**; 7–8 → **3 Mayor**; 9 → **4 Crítico**.

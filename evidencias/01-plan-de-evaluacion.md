# Plan de evaluación de usabilidad · CaféU v3

**Responsable de este documento:** González Álvarez Vladimir Humberto (soporte técnico)
**Asignatura:** Interacción Humano-Computador · Carrera de Software · UTA – FISEI · 5.º «A»
**Docente:** Ing. José Rubén Caiza Caizabuano, Mg.
**Fase:** APE 6 – Fase 1 (planificación). La aplicación y el análisis de resultados corresponden a la Fase 2.

---

## 1. Qué se evalúa

| Elemento | Definición |
|---|---|
| **Sistema** | CaféU v3: prototipo navegable en HTML, CSS y JavaScript para pedir en la cafetería de la FISEI antes de llegar. Es la versión final del APE 4 integral, construida a partir de los wireframes y corregida con la prueba de esa práctica. |
| **Enlace** | https://raw.githack.com/Sebastianyiyi/APE04_IHC/main/APE4-integral/prototipo/cafeu-v3.html (respaldo local: [`prototipo/cafeu-v3.html`](../prototipo/cafeu-v3.html)) |
| **Funciones incluidas** | Consultar horario y tiempo de preparación; ver el menú (7 productos), buscar sin tildes y filtrar por Bebidas o Comida; ver disponibilidad (producto agotado); personalizar tamaño y tipo de leche; elegir cantidad (1 a 9); revisar el pedido, cambiar cantidades, quitar y deshacer; elegir retiro «lo antes posible» o a una hora programada (09:51–17:45) con validación; revisar y confirmar; ver número de pedido y monto a pagar al retirar. |
| **Fuera de alcance** | Pago en línea, cuentas de usuario, historial de pedidos y vista del personal de la cafetería (no existen en el prototipo). |
| **Usuarios** | Estudiantes, docentes y personal administrativo de la FISEI que compran en la cafetería y tienen poco tiempo entre clases o reuniones. |
| **Contexto de uso** | Celular o laptop, normalmente con prisa, de pie o caminando entre bloques, con interrupciones; la persona paga en caja al retirar. En la prueba se usa una laptop con Chrome en un aula tranquila de la FISEI. |
| **Objetivo del usuario** | Tener su pedido listo a la hora que pasa a retirarlo, sin hacer fila y sin errores en lo que pidió. |

## 2. Pregunta de evaluación

> **¿En qué medida el prototipo CaféU v3 permite a estudiantes y personal de la FISEI consultar el menú, armar y modificar un pedido y programar su retiro con eficacia, eficiencia y satisfacción, y qué problemas de usabilidad lo impiden?**

| Dimensión (ISO 9241-11) | Qué significa en CaféU | Cómo se mide | Umbral de aceptación |
|---|---|---|---|
| **Eficacia** | El participante consigue el pedido correcto y responde bien las consultas. | Tasa de éxito por tarea; errores críticos. | ≥ 80 % de éxito por tarea; 0 errores críticos en T3–T6. |
| **Eficiencia** | Lo consigue sin rodeos ni demoras. | Mediana del tiempo por tarea; errores no críticos. | Mediana ≤ meta de cada tarea. |
| **Satisfacción** | Se siente cómodo y seguro usando la aplicación. | Puntaje SUS (0–100); comentarios de cierre. | Media SUS ≥ 68. |

Los umbrales sirven para interpretar los resultados de la Fase 2; con tres participantes se reportan como tendencia, no como generalización.

## 3. Métodos de evaluación

| | Método 1 · Evaluación heurística | Método 2 · Prueba con usuarios (pensamiento en voz alta) |
|---|---|---|
| **Tipo** | Analítico (expertos, sin usuarios) | Empírico (usuarios reales) |
| **Quién** | Los cuatro integrantes, cada uno por separado | 3 participantes ajenos al grupo (P1, P2, P3) |
| **Instrumento** | [Guía de evaluación heurística](05-guia-evaluacion-heuristica.md): 10 heurísticas de Nielsen, severidad 0–4 | [Tareas](03-tareas.md), [hoja de observación](04-hoja-de-observacion.md) y SUS |
| **Qué produce** | Lista de problemas potenciales con heurística, evidencia y severidad | Éxito, tiempo, errores, frases textuales y puntaje SUS |
| **Cuándo** | Antes de la sesión con usuarios (Fase 2, primer bloque) | Fase 2, una sesión de 20 min por participante |

**Triangulación.** Al terminar ambos métodos se cruzan los hallazgos: un problema que aparece en la heurística **y** en la prueba con usuarios se confirma y sube de prioridad; uno que solo aparece en la heurística se marca como *potencial*; uno que solo aparece con usuarios se agrega a la lista con su heurística asociada. La consolidación se hace en una tabla única (problema, heurística, severidad, tareas afectadas, evidencia).

**Pensamiento en voz alta.** Antes de T1 el moderador pide al participante que diga lo que piensa mientras usa la aplicación («qué buscas, qué esperas, qué te sorprende») y hace una práctica breve de 30 s con una pregunta ajena al prototipo. Durante las tareas solo recuerda «¿qué estás pensando?» si el participante se queda en silencio más de 15 s; no responde preguntas sobre la interfaz.

## 4. Participantes

**Perfil.** Personas de 18 años o más de la comunidad de la FISEI que compran en la cafetería al menos una vez por semana y usan el celular o la computadora a diario.

**Criterios de exclusión.** Integrantes del grupo; personas que vieron el diseño o participaron en la prueba del APE 4 (P01 y P02); personas que conocen las tareas; menores de edad.

**Reclutamiento.** Invitación verbal en la cafetería y en los pasillos de la FISEI, explicando el objetivo y la duración (20 min). No se ofrece compensación.

| Código | Perfil (sin datos identificables) | Frecuencia de compra en la cafetería | Experiencia con apps de pedidos | Estado |
|---|---|---|---|---|
| **P1** | Estudiante de 3.er semestre de otra carrera de la FISEI, 18–21 años | 3–4 veces por semana | Usa apps de comida a domicilio ocasionalmente | Confirmado |
| **P2** | Estudiante de 8.º semestre de otra carrera de la FISEI, 22–25 años | 2 veces por semana | Frecuente (varias veces al mes) | Confirmado |
| **P3** | Personal administrativo de la FISEI, 30–39 años | 1–2 veces por semana | Poca; prefiere comprar en caja | Confirmado |

Tres participantes corresponden al pilotaje que pide la guía; la literatura recomienda cinco para una prueba completa [Nielsen y Landauer, 1993]. La diversidad de perfiles (estudiante frecuente, estudiante avanzado, personal administrativo) busca cubrir distintos niveles de experiencia. Ninguna hoja, archivo o commit registrará nombres: solo los códigos P1, P2 y P3.

## 5. Tareas

Seis tareas (2 de consulta y 4 de creación o modificación), con escenario, meta, tiempo máximo (2 × meta), criterio de éxito y respuesta correcta: ver [03-tareas.md](03-tareas.md).

| ID | Resumen (solo para el equipo) | Meta | Máx. |
|---|---|---|---|
| T1 | Tiempo de preparación y hora de cierre | 30 s | 60 s |
| T2 | Disponibilidad de la empanada de verde | 40 s | 80 s |
| T3 | Capuchino mediano con leche de almendra ($2,70) | 75 s | 150 s |
| T4 | Sumar 2 panes de yuca (total $3,90) | 60 s | 120 s |
| T5 | Dejar 1 pan de yuca (total $3,30) | 40 s | 80 s |
| T6 | Programar retiro 11:15, confirmar, N.º 031 y $3,30 | 90 s | 180 s |

## 6. Métricas de usabilidad

| Métrica | Definición operativa | Cálculo | Registro |
|---|---|---|---|
| **Tasa de éxito** | Porcentaje de participantes que completan la tarea **sin ayuda** y dentro del máximo. | (n.º de «Sí» / n.º de participantes) × 100, por tarea y global. | Columna «Éxito» de la hoja |
| **Tiempo por tarea** | Segundos desde que el moderador termina de leer el escenario hasta que el participante da la respuesta o la pantalla muestra el estado de éxito, o hasta que abandona o llega al máximo. | Mediana por tarea (con 3 participantes la media se distorsiona con un caso extremo); también mínimo y máximo. | Cronómetro del responsable de métricas |
| **Errores críticos** | Acción que impide completar la tarea o deja un resultado incorrecto que el participante no detecta. | Conteo por tarea y participante. | Columna «E. críticos» |
| **Errores no críticos** | Acción equivocada de la que el participante se recupera por sí mismo y termina la tarea. | Conteo por tarea y participante. | Columna «E. no críticos» |
| **SUS** | Satisfacción percibida, 10 ítems con escala 1–5. | Ítems impares: respuesta − 1; ítems pares: 5 − respuesta; suma × 2,5 → 0–100. Referencia: 68 = promedio. | Cuestionario al final |

**Estados de éxito.** *Sí*: completa sin ayuda dentro del máximo. *Con ayuda*: completa después de la pista única. *No*: no la completa, abandona, da una respuesta incorrecta o supera el máximo. Solo *Sí* cuenta en la tasa de éxito.

**Clasificación de errores en CaféU.**

| Tipo | Ejemplos concretos en el prototipo |
|---|---|
| **Crítico** | Agregar el capuchino con otro tamaño o leche y no corregirlo; dejar el pedido sin ningún pan o con 2 en T5; confirmar con «lo antes posible» en lugar de 11:15; dar un número de pedido o monto incorrecto; abandonar la tarea. |
| **No crítico** | Entrar al detalle de un producto equivocado y volver; buscar con un término sin resultados y reformular; usar el filtro equivocado y cambiarlo; escribir una hora no válida y corregirla tras el mensaje; quitar un producto y recuperarlo con «Deshacer». |

## 7. Consentimiento informado

Se lee en voz alta antes de empezar y el participante lo acepta (firma o aceptación verbal registrada en la hoja). Garantiza participación **voluntaria**, **confidencialidad** y **anonimato**, la posibilidad de retirarse sin consecuencias y que se evalúa la aplicación, no a la persona. Texto completo: [02-consentimiento-informado.md](02-consentimiento-informado.md) (versión imprimible en [`imprimibles/`](imprimibles/)).

## 8. Roles del equipo

| Rol | Integrante | Responsabilidades durante la sesión |
|---|---|---|
| **Moderador** | Mora Beltrán Santiago Sebastián | Recibe al participante, lee el consentimiento y las tareas tal como están escritas, recuerda pensar en voz alta, da la pista única cuando corresponde y conduce el cierre. No ayuda ni opina. |
| **Responsable de métricas** | Vinces Cueva Boris Yussef | Cronometra cada tarea, registra éxito, errores críticos y no críticos y aplica y puntúa el SUS. |
| **Observador** | Acaro Ibujés Pedro Sebastián | Anota frases textuales, dudas y fricciones, y las relaciona con la heurística de Nielsen que parece estar en juego. |
| **Soporte técnico** | González Álvarez Vladimir Humberto | Prepara la laptop, el enlace y el respaldo local; deja el estado de partida de cada tarea; reinicia el prototipo entre participantes y maneja la grabación de audio si se autoriza. |

En la evaluación heurística los cuatro actúan como evaluadores independientes.

## 9. Instrumentos

| Instrumento | Archivo |
|---|---|
| Consentimiento informado | [02-consentimiento-informado.md](02-consentimiento-informado.md) |
| Matriz de seis tareas | [03-tareas.md](03-tareas.md) |
| Hoja de observación y cuestionario SUS | [04-hoja-de-observacion.md](04-hoja-de-observacion.md) |
| Guía de evaluación heurística | [05-guia-evaluacion-heuristica.md](05-guia-evaluacion-heuristica.md) |
| Guion de la sesión | [06-guion-de-la-sesion.md](06-guion-de-la-sesion.md) |
| Plantillas de registro (Fase 2) | [`resultados/`](../resultados/) |

## 10. Logística

| Aspecto | Decisión |
|---|---|
| Lugar | Aula de la FISEI con poco ruido, una mesa y dos sillas frente a la laptop; el equipo se ubica detrás y a un lado del participante. |
| Equipo | Laptop de 14″ con Chrome actualizado, mouse externo y conexión a internet; respaldo local `cafeu-v3.html` abierto en otra pestaña por si falla la red. |
| Grabación | Solo audio y solo si el participante lo autoriza en el consentimiento. Sin video del rostro. |
| Duración | 20 minutos por participante (guion en [06-guion-de-la-sesion.md](06-guion-de-la-sesion.md)). |
| Datos | Hojas con código P1–P3; se transcriben a `resultados/` sin nombres; el audio se elimina al cerrar el análisis de la Fase 2. |

## 11. Criterios de validación del protocolo

El protocolo se considera **listo para aplicarse en la Fase 2** cuando se cumplen las siete condiciones siguientes. Las que dependen de participantes se verifican con P1 y, si alguna falla, se ajusta el protocolo antes de P2.

| N.º | Criterio | Evidencia | Estado al cierre de la Fase 1 |
|---|---|---|---|
| C1 | Las seis tareas se resuelven en el prototipo y sus respuestas correctas coinciden con la pantalla. | Ensayo interno completo T1→T6 | Cumplido (11/11/2026) |
| C2 | Ningún escenario nombra botones, pantallas ni rótulos de la interfaz. | Revisión cruzada de las tareas por dos integrantes | Cumplido (ajustes 1 y 2 del registro de tareas) |
| C3 | El reinicio deja el prototipo en el estado inicial y T6 vuelve a dar N.º 031. | Ensayo de reinicio con F5 repetido dos veces | Cumplido |
| C4 | La hoja permite registrar éxito, tiempo, errores, pista, repetición, frases y SUS sin campos ambiguos. | Llenado de prueba de la hoja durante el ensayo interno | Cumplido |
| C5 | Ningún participante pide repetir la lectura de una tarea por no entenderla. | Columna «¿Pidió repetir?» con P1 | Se verifica con P1 |
| C6 | Al menos 2 de 3 participantes terminan cada tarea antes del tiempo máximo. | Tiempos de P1–P3 | Se verifica en la Fase 2 |
| C7 | La sesión completa dura 20 minutos o menos y no hay fallos técnicos que la interrumpan. | Hora de inicio y fin en la hoja | Ensayo interno: 14 min; se verifica con P1 |

Si C5 o C6 fallan en una tarea, se revisa su redacción o su meta y se registra el cambio con fecha en [03-tareas.md](03-tareas.md), sección 7.

## 12. Ensayo interno del protocolo (11/11/2026)

El equipo ejecutó el protocolo completo una vez con los roles asignados: un integrante actuó como participante de ensayo, el moderador leyó las tareas, el responsable de métricas cronometró y llenó una hoja de prueba, y el soporte técnico preparó los estados de partida y reinició el prototipo. El ensayo **no** forma parte de los resultados: solo valida el protocolo.

| Comprobación | Resultado |
|---|---|
| Respuestas correctas de T1–T6 | Coinciden con el prototipo: 10 min y 18:00; agotada, vuelve mañana; $2,70; $3,90; $3,30; N.º 031 y $3,30. |
| Tiempos del participante de ensayo (experto) | T1 11 s · T2 16 s · T3 31 s · T4 24 s · T5 15 s · T6 37 s (total 134 s), base para las metas. |
| Duración de la sesión completa | 14 min, incluido consentimiento, SUS y cierre. |
| Reinicio | F5 vuelve a la pantalla de inicio con el pedido en 0; T6 da otra vez N.º 031. |
| Ajustes derivados | Cinco cambios en las tareas (registro en [03-tareas.md](03-tareas.md), sección 7) y una columna nueva en la hoja («¿Pidió repetir la tarea?»). |

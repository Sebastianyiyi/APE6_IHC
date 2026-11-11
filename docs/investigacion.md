# Marco conceptual · Evaluación y validación de la usabilidad

**Responsable de este documento:** González Álvarez Vladimir Humberto
Resumen de los conceptos que sustentan el plan de evaluación de CaféU v3. Las referencias completas están en el [informe](../informe/) (sección 2.11).

## 1. Usabilidad según ISO 9241-11
La norma ISO 9241-11:2018 define la usabilidad como el grado en que un sistema puede ser usado por **usuarios específicos** para lograr **objetivos específicos** con **eficacia**, **eficiencia** y **satisfacción** en un **contexto de uso** determinado [ISO 9241-11].

| Componente | Definición | En CaféU |
|---|---|---|
| Eficacia | Exactitud y completitud con que se logra el objetivo. | ¿El pedido confirmado es el que la persona quería? |
| Eficiencia | Recursos (tiempo, esfuerzo) usados en relación con el resultado. | ¿Cuánto tarda y cuántos rodeos hace? |
| Satisfacción | Respuestas físicas, cognitivas y emocionales del usuario. | ¿Se siente seguro y lo volvería a usar? |
| Contexto de uso | Usuarios, tareas, recursos y entorno. | Comunidad FISEI, con prisa, entre clases. |

La norma obliga a definir **para quién, para qué y dónde** se evalúa; por eso el plan empieza describiendo el sistema, los usuarios y el contexto antes de elegir métodos.

## 2. Evaluar y validar
- **Verificar** es comprobar que el prototipo cumple lo especificado (¿se construyó bien?). En el plan corresponde al ensayo interno: las seis tareas se pueden resolver y sus respuestas coinciden con la pantalla.
- **Validar** es comprobar que el producto resuelve la necesidad real de sus usuarios (¿se construyó lo correcto?). Solo se logra observando a usuarios reales en tareas reales [Pressman, 2010].
- **Evaluación formativa** (durante el diseño, para encontrar problemas) frente a **sumativa** (al final, para medir contra un umbral). La evaluación de CaféU es formativa: con tres participantes busca problemas y tendencias, no conclusiones estadísticas [Rubin y Chisnell, 2008].

## 3. Métodos analíticos y empíricos
| | Analíticos (inspección) | Empíricos (con usuarios) |
|---|---|---|
| Quién evalúa | Expertos o el equipo | Usuarios representativos |
| Ejemplos | Evaluación heurística, recorrido cognitivo | Prueba con usuarios, pensamiento en voz alta, cuestionarios |
| Ventaja | Rápidos y baratos; no requieren participantes | Muestran problemas reales y su impacto |
| Límite | Pueden señalar problemas que no afectan a nadie | Requieren reclutar, preparar y cuidar aspectos éticos |

Combinar un método de cada tipo permite **triangular**: un problema confirmado por ambos tiene más peso que uno que aparece en uno solo [Cañas, Granollers y Lorés, 2012].

## 4. Evaluación heurística
Nielsen y Molich propusieron que un grupo pequeño de evaluadores revise la interfaz contra principios reconocidos. Cada evaluador trabaja por separado y después se consolidan los hallazgos; de tres a cinco evaluadores encuentran la mayoría de los problemas [Nielsen y Molich, 1990]. Las diez heurísticas de Nielsen [Nielsen, 1994]:

1. Visibilidad del estado del sistema.
2. Relación entre el sistema y el mundo real.
3. Control y libertad del usuario.
4. Consistencia y estándares.
5. Prevención de errores.
6. Reconocer antes que recordar.
7. Flexibilidad y eficiencia de uso.
8. Diseño estético y minimalista.
9. Ayudar a reconocer, diagnosticar y recuperarse de errores.
10. Ayuda y documentación.

Cada problema se califica con la **escala de severidad 0–4** (0 no es problema; 4 catastrófico), considerando frecuencia, impacto y persistencia.

## 5. Prueba con usuarios y pensamiento en voz alta
El participante resuelve tareas realistas mientras dice en voz alta lo que piensa. El moderador no ayuda; solo recuerda verbalizar. Es el método de usabilidad más valioso por su relación costo/beneficio [Nielsen, 2012]. Reglas clave:
- Las tareas describen **situaciones y objetivos**, no pasos ni botones; si la tarea dice dónde tocar, se mide la lectura y no la interfaz.
- El éxito debe ser **observable** (lo que se ve en pantalla o la respuesta exacta).
- Se usa una **pista única y neutral** para no contaminar la medición.
- Un **pilotaje** con pocas personas valida el protocolo antes de aplicarlo a más usuarios. Con cinco usuarios se descubre cerca del 85 % de los problemas [Nielsen y Landauer, 1993].

## 6. Métricas de usabilidad
| Métrica | Mide | Cálculo |
|---|---|---|
| Tasa de éxito | Eficacia | Completadas sin ayuda / participantes × 100 |
| Tiempo por tarea | Eficiencia | Mediana de los tiempos (robusta ante casos extremos) |
| Errores críticos y no críticos | Eficacia y eficiencia | Conteo; el crítico impide el objetivo, el no crítico se recupera |
| SUS | Satisfacción | 10 ítems 1–5; impares − 1, 5 − pares; suma × 2,5 |

## 7. System Usability Scale (SUS)
Cuestionario de diez ítems creado por Brooke [Brooke, 1996], alternando afirmaciones positivas (impares) y negativas (pares) para reducir el sesgo de aquiescencia. Da un puntaje de 0 a 100 que **no es un porcentaje**: 68 es el promedio de cientos de estudios; por encima de 80,3 se considera excelente y por debajo de 51, deficiente [Sauro y Lewis, 2016]. Se aplica la versión en español validada por Sevilla-González et al. [2020], cambiando «sistema» por «aplicación», ajuste aceptado por la literatura.

## 8. Ética de la evaluación
Toda prueba con personas requiere **consentimiento informado**: participación voluntaria, derecho a retirarse, confidencialidad, anonimato (códigos en lugar de nombres), uso limitado de los datos y aclaración de que se evalúa el sistema, no a la persona [Rubin y Chisnell, 2008]. Se excluye a menores de edad y a quienes participaron en el diseño.

## 9. Cómo se aplica en CaféU
| Concepto | Decisión en el plan |
|---|---|
| ISO 9241-11 | Pregunta de evaluación con eficacia, eficiencia y satisfacción y umbrales para cada una |
| Métodos | Heurística (4 evaluadores) + prueba con usuarios con voz alta (P1–P3) y triangulación |
| Tareas | Seis situaciones de la vida en la FISEI, sin nombres de controles, con respuesta exacta |
| Métricas | Éxito, mediana de tiempo, errores críticos/no críticos, SUS |
| Ética | Consentimiento leído en voz alta, códigos P1–P3, audio solo con autorización |
| Validación del protocolo | Siete criterios (C1–C7) y ensayo interno antes de la Fase 2 |

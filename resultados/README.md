# Resultados · APE 6

**Responsable de esta carpeta:** Vinces Cueva Boris Yussef (responsable de métricas)

Esta carpeta recibe, en la **Fase 2**, los datos transcritos de las hojas de observación de P1, P2 y P3 y la evaluación heurística de los cuatro integrantes. En la Fase 1 contiene solo las plantillas, para que todos registren con el mismo formato.

| Archivo | Contenido | Se llena con |
|---|---|---|
| `plantilla-registro-tareas.csv` | Una fila por participante y tarea: éxito, tiempo en segundos, errores, pista, repetición y respuesta. | Parte B de la hoja de observación |
| `plantilla-sus.csv` | Una fila por participante: respuestas de los 10 ítems y puntaje SUS. | Parte D de la hoja de observación |

## Reglas
- Solo códigos P1, P2, P3; ningún nombre ni dato personal.
- El tiempo se registra en **segundos enteros** tal como lo marcó el cronómetro.
- `exito` admite solo `Si`, `Con ayuda` o `No`.
- No se completan campos vacíos ni se corrigen datos después de la sesión; las aclaraciones van en la columna `observaciones`.

## Cálculos previstos (Fase 2)
- **Tasa de éxito por tarea** = número de `Si` / 3 × 100.
- **Tiempo por tarea** = mediana de los tres tiempos (además del mínimo y el máximo).
- **Errores** = suma de críticos y de no críticos por tarea.
- **SUS** = (Σ impares − 5 + 25 − Σ pares) × 2,5 por participante; luego la media del grupo frente a la referencia de 68.

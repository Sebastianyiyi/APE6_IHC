# Evaluación heurística individual (Fase 3) · Vinces Cueva Boris Yussef

**Prototipo:** CaféU v3 · **Fecha:** 18/11/2026 · **Duración:** 36 min · **Escala:** severidad 1–4 a partir de Frecuencia (F), Impacto (I) y Persistencia (P), de 1 a 3 cada uno.
**Procedimiento:** inspección individual del flujo completo, del buscador, de «Deshacer» y de los estados de error, aplicando las 10 heurísticas de Nielsen, sin comentar con el grupo hasta la consolidación.

| N.º | Heurística | Componente | Problema y evidencia | F | I | P | Severidad | Recomendación |
|---|---|---|---|---|---|---|---|---|
| 1 | H9 · Reconocer, diagnosticar y recuperarse de errores | Hora de retiro · campo de hora | En la laptop con 12 h, escribir solo 11:15 deja el campo incompleto y el mensaje confunde. | 2 | 3 | 3 | **3** | Reemplazar el campo nativo. |
| 2 | H5 · Prevención de errores | Hora de retiro / Revisar y confirmar | La línea de retiro en la revisión no resalta. | 2 | 3 | 3 | **3** | Resaltar la hora con color o ícono. |
| 3 | H6 · Reconocer antes que recordar | Mi pedido · línea | «Pan de yuca $1,20» con cantidad 2 no aclara si es unitario. | 2 | 1 | 3 | **2** | Mostrar «2 × $0,60 = $1,20». |
| 4 | H3 · Control y libertad del usuario | Aviso con «Deshacer» | Perdí el «Deshacer» al mover el mouse a la lista. | 2 | 2 | 2 | **2** | Aviso hasta la siguiente acción. |
| 5 | H4 · Consistencia y estándares | Menú · filtros | Medí el borde de los filtros (#D7C8BC sobre blanco): 1,63:1, bajo el 3:1 de WCAG 1.4.11. | 2 | 1 | 2 | **2** | Borde de al menos 3:1 (p. ej. #8D7B73, 4,03:1). |
| 6 | H10 · Ayuda y documentación | Global | No se explica qué pasa si llego tarde. | 1 | 1 | 2 | **1** | Nota en la confirmación. |

**Total:** 6 problemas · **Severidad promedio:** 2,17 · **Heurísticas con hallazgos:** H3, H4, H5, H6, H9, H10

Escala: 1 Cosmético · 2 Menor · 3 Mayor · 4 Crítico (F + I + P: 3–4 → 1; 5–6 → 2; 7–8 → 3; 9 → 4).

**Evaluador:** Vinces Cueva Boris Yussef

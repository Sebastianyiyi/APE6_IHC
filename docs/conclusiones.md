# Conclusiones · APE 6 (Fases 3 y 4)

**Responsable:** Acaro Ibujés Pedro Sebastián

## ¿Una interfaz que funciona técnicamente puede ser una mala interfaz?

**Sí.** CaféU v3 pasa la **verificación** (Boehm, 1984): todas sus funciones hacen lo especificado, el buscador entiende palabras sin tilde y sinónimos, los totales son correctos y no hay errores técnicos en ninguna sesión. Pero la **validación** con usuarios mostró que funcionar no basta: en el pilotaje y otra vez en la Fase 3, el participante más rápido y con más experiencia en apps confirmó su pedido con una hora de retiro que no eligió (H-01), y un participante no pudo recuperar un producto porque el aviso de «Deshacer» desapareció a los 6 s (H-02). En ambos casos el sistema hizo exactamente lo programado y, aun así, el usuario no logró su objetivo.

## Conclusiones

1. **Eficacia alta pero no completa.** 22 de 24 intentos (91,7 %) terminaron con éxito autónomo; los dos fallos son errores críticos silenciosos en la hora de retiro y en la recuperación de lo quitado, justo donde la interfaz decide por el usuario o le da poco tiempo.
2. **Eficiencia adecuada.** Las ocho medianas quedaron bajo su meta; el costo de los problemas recae en el perfil con menos experiencia (P2, docente), que concentró los tiempos más altos.
3. **Satisfacción sobre la referencia, con dispersión.** El SUS medio fue 76,67 (> 68), pero P2 dio 62,5; quien sufre los problemas percibe peor el sistema, y quien comete un error sin notarlo (P3) puede calificarlo muy alto (92,5).
4. **Los métodos se complementan.** La heurística anticipó los seis problemas confirmados; las pruebas con usuarios midieron su impacto real y revelaron uno que el equipo no veía (H-13). La triangulación permitió priorizar con evidencia y no por opinión.
5. **El backlog es trazable.** Cada mejora (C-01 a C-11) tiene componente, cambio verificable, estándar (WCAG 2.1, ISO 9241-11, Nielsen) y un issue en GitHub con prioridad P1–P4.

## Recomendaciones

- Implementar primero C-01 y C-02 (P1) y repetir T6 y T8 con tres usuarios nuevos para comprobar 0 errores críticos.
- Ampliar a cinco participantes con al menos dos de poca experiencia en apps de pedidos.
- Incorporar una revisión de contraste (WCAG 1.4.11) en cada versión del prototipo.

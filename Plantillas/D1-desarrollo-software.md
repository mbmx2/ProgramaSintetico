# Plantilla D1 — Desarrollo (software y afines)

**Ciclo:** desarrollo completo, por iteraciones · **Universal:** implementaciones de software, automatizaciones, integraciones de sistemas · **Términos de apoyo:** todos los IG (especialmente IG10, IG13, IG17, IG26, IG39, IG40) · **Gobernanza:** GOB13, GOB14, GOB12, GOB48

---

## Para qué sirve y cuándo usarla

Es el ciclo de vida completo en una sola plantilla, en lenguaje de desarrollo: del problema al *release*, pasando por requisitos técnicos, diseño, construcción, pruebas con usuario y mejora. Úsala para cualquier implementación de software —una app, una integración, una automatización, un sitio— manteniendo la misma disciplina que en cualquier otro proyecto.

Los campos tratan al software como lo que es: **un sistema con frontera, requisitos y usuarios**, no como una Coreografía de tecnicismos.

---

## Cómo completarla

**1. Encuadre (resumen de A1).**

Problema real: ______________________________________________

Usuario que lo usa: ______________________________________________

*Fuera de alcance (no construimos esto):* ______________________________________________

**2. Requisitos técnicos (resumen de A2, en lenguaje comprobable).**

R1. El sistema deberá ______________________________________________ *Prueba:* ____________

R2. El sistema deberá ______________________________________________ *Prueba:* ____________

R3. El sistema deberá ______________________________________________ *Prueba:* ____________

*No funcionales (rendimiento, seguridad, datos):* ______________________________________________

**3. Iteración actual.** *Qué construimos en esta vuelta (una pieza que se pueda entregar):* ______________________________________________

*Definición de terminado (DoD):*
- ☐ código probado con lo esencial cubierto
- ☐ revisado por otra persona (o por el futuro yo, con ojos frescos)
- ☐ documentación actualizada (la que mentirá, arreglada)
- ☐ demo con usuario o con datos reales
- ☐ sin deuda técnica nueva sin anotar (IG39)

**4. Verificación (¿lo hice bien?).**

*Qué se prueba y cómo:* ______________________________________________
*Resultado:* ☐ todo verde · ☐ defectos anotados (lista): ____________________________

**5. Validación (¿era esto lo que se necesitaba?).**

*El usuario probó:* ______________ *¿Le sirvió?* ☐ sí ☐ en parte ☐ no
*Qué cambia el próximo ciclo:* ______________________________________________

**6. Deuda técnica consciente** (lo que dejamos simple a propósito):

D.1 ______________ *costo futuro estimado:* ________ *cuándo se paga:* ____________

**7. Métricas del ciclo** (línea base → ahora): ______________ → ______________
*¿Quién lee este dato?* ______________

**8. Riesgo técnico rojo:** ______________________________________________

**9. Retrospectiva breve** (de A6, tres renglones): mantener ______________ · cambiar ______________ · probar ______________

---

## Consejo de uso

Las dos trampas clásicas del desarrollo son construir más de lo pedido (deriva de alcance, A5) y validar con el propio equipo en lugar de con quien va a usarlo (IG13 con cara de QA). Y la deuda técnica sin anotar es el crédito de consumismo del proyecto: se puede usar, pero con recibo y fecha de pago. Si la iteración no puede escribir su DoD en cinco casillas, es demasiado grande: córtala.

---

*Plantillas · Ciclo: desarrollo · v0.1*

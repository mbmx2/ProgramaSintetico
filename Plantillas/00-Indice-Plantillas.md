# Índice de plantillas

## Cómo elegir y usar las plantillas del proyecto

*Capa Ingeniería de la Educación · Plantillas v0.1 · 28 de septiembre de 2026*
*Derivadas de: `glosario-ingenieria-general.md` (IG), `glosario-ingenieria-aplicada-educacion.md` (IA), `glosario-ingenieria-de-la-educacion.md` (IE) y sus compendios*

---

## El criterio

Una plantilla no es un formulario: es un **andamio de pensamiento**. Te obliga a responder, en orden, las preguntas que el ciclo de vida de todo proyecto hace —y que se saltan los proyectos que fracasan. Cada plantilla de esta carpeta trae su porqué (con el término ingenieril que la sostiene), campos para llenar y un consejo con la trampa que evita.

La regla de uso es la de siempre: **se llena hablando con la gente y con datos, no desde el escritorio**. Un campo vacío es información; un campo inventado es deuda.

---

## Las familias de plantillas

### Familia A — el ciclo completo, para cualquier proyecto y cualquier fase

Ocho plantillas que cubren el recorrido entero: encuadrar, pedir, planificar, verificar, cuidar, revisar, aprender y decidir. Sirven para un proyecto de software, una mudanza, un programa escolar o una investigación.

**A1 — Encuadre y alcance.** El punto de partida: problema real, meta, dentro y fuera de alcance, partes interesadas. *Ciclo:* inicio. *Evita:* el proyecto que empieza a construir antes de saber qué casa piden.

**A2 — Requisitos.** Levantamiento de fuentes y requisitos verificables con criterio de aceptación. *Ciclo:* inicio. *Evita:* "mejorar la calidad", que no se puede comprobar.

**A3 — Diseño y plan.** WBS, secuencia, roles y supuestos. *Ciclo:* diseño. *Evita:* el plan que nadie entiende y por eso nadie cumple.

**A4 — Verificación y validación.** Línea base, evidencia y métricas con lectura. *Ciclo:* ejecución y cierre de fase. *Evita:* celebrar sin haber medido, medir sin haber leído.

**A5 — Riesgos y control de cambios.** Registro de riesgos y tramitación de cambios. *Ciclo:* transversal. *Evita:* la deriva de alcance disfrazada de buenas ideas.

**A6 — Retrospectiva y mejora.** Qué pasó, por qué, qué cambiamos —con causa raíz. *Ciclo:* cierre y mejora. *Evita:* repetir el mismo error con entusiasmo renovado.

**A7 — Registro de patrones y antipatrones.** Para ir poblando tu catálogo propio de soluciones y errores recurrentes. *Ciclo:* mejora continua. *Evita:* que lo aprendido se pierda con quien se va.

**A8 — ADR: registro de decisión.** Decisiones estructurales con alternativas y consecuencias. *Ciclo:* diseño y cambios mayores. *Evita:* la costumbre que nadie puede justificar.

### Familia S — estudio y práctica personal (metas y sesiones)

**S1 — Meta y práctica de estudio.** Para tus metas y alcances personales: qué voy a dominar, evidencia de que lo logré, plan de sesiones de práctica y registro. Funciona con un libro, una herramienta o una habilidad. *Ciclo:* cualquier aprendizaje autodirigido (y el bloque G del glosario neuro lo respalda: andragogía aplicada a ti mismo).

### Familia D — desarrollos (software y afines)

**D1 — Desarrollo (ciclo completo en una).** Para implementaciones de software u otros desarrollos: del problema al *release*, con requisitos técnicos, entregables por iteración, pruebas (verificación) con usuario (validación), deuda técnica consciente y retrospectiva por sprint. Usa el vocabulario IG sin traducir.

### Familia N — proyectos de neuroeducación con niños concretos

**N1 — Realidad alcanzable (neuroeducación).** Para plantear realidades alcanzables para un grupo o una niña o niño específico: perfil sin diagnóstico, referentes por edad, apoyos por perfil, entorno y estados, protocolos y evidencia de proceso. Trae las guardas del Acta: consentimiento, minimización de datos, derivación sin diagnóstico.

### Familia T — talleres y cursos

**T1 — Diseño de taller o curso.** Objetivo verificable, evidencia, secuencia con tiempos, accesibilidad (UDL), evaluación por proceso y piloto breve. Es el ADDIE de una página (IA2).

---


### Familia GOB — gobernanza formal (11)

Las plantillas que cierran las brechas del inventario de gobernanza (`Ingeniería de la Educación/gobernanza-inventario-de-instrumentos.md`, §8). Cada una lleva el código GOB del instrumento que formaliza:

**GOB7 — Política de protección** (datos, imagen, IA y no daño) · **GOB8 — Código de conducta** con canal de reporte · **GOB9 — Registro de decisiones, problemas y supuestos** · **GOB10 — Acta de reunión con acuerdos** · **GOB15 — Informe de estado ejecutivo y de ciclo** · **GOB16 — Consentimiento informado** (lenguaje llano para familias) · **GOB19 — Acuerdos con terceros** (NDA, encargos, visitantes) · **GOB20 — Manual de inducción y transferencia** · **GOB22 — Presupuesto y autorizaciones** · **GOB25 — Escalera de decisión y delegación** · **GOB51 — Caso de negocio y decisión Go/No-Go**.

*Ciclo:* la mayoría en **inicio**; GOB9 y GOB10 son **transversales**; GOB15 alterna lo periódico y lo de cierre; GOB20 se mantiene **continuo**.

## Mapa rápido: ¿cuál uso según lo que tienes en frente?

- **No sabes por dónde empezar** → A1, después A2.
- **Ya sabes qué quieres pero no cómo** → A3 (y D1 si es software, T1 si es un curso, N1 si hay niños).
- **Va en marcha y necesitas medir** → A4.
- **Hay que cambiar lo que ya estaba decidido** → A5 (y A8 si la decisión es estructural).
- **Terminó una etapa** → A6; si descubriste algo repetible → A7.
- **Aprendes algo tú solo** → S1.
- **Tienes que decidir si vale la pena o no empezar** → GOB51 (caso de negocio y Go/No-Go).
- **Vas a formalizar cómo trabaja tu equipo** → GOB7, GOB8 y GOB20 primero; GOB9 y GOB10 todos los días.
- **Entras en relación con un tercero o una plataforma** → GOB19 + la elección en ADR (y el catálogo `plataformas-fooss-de-gobernanza.md`).
- **Diseñas para niñas y niños concretos** → N1 (siempre junto a A2).

---

## Convenciones

Los campos se llenan en línea (`____`), con casillas (`☐`) para lo que se marca. Cada plantilla indica su **fase del ciclo**, sus **términos IG/IA/IE** de apoyo y, desde esta versión, su código de **gobernanza (GOB)** —el inventario completo de instrumentos vive en `Ingeniería de la Educación/gobernanza-inventario-de-instrumentos.md`. Se imprimen o se usan digitalmente; el DOCX de esta carpeta mantiene portada, índice y foliado de la serie. Y una nota honesta: **plantilla no es sustituto de conversación** —lo que no se puede llenar sin hablar con alguien, es exactamente lo que había que hablar con alguien.

---

*Capa Ingeniería de la Educación · Plantillas · v0.1 (23 plantillas: 12 del ciclo + índice y 11 de gobernanza) · Proyecto Programa Sintético.*

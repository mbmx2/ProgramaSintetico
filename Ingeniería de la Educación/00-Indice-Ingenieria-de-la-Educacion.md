# Índice de la capa: Ingeniería de la Educación

## Arquitectura de los cuatro niveles y ruta de capacitación

*Documento de navegación · Capa Ingeniería de la Educación · v0.1 · 28 de septiembre de 2026*
*Serie de Neuroeducación · Proyecto Programa Sintético · Fuente de requerimientos: `Requisitos.md` (esta carpeta)*

---

## 0. Qué es esta carpeta

Es la **capa de ingeniería** del proyecto: el lugar donde las disciplinas de diseño, construcción y verificación de sistemas se hacen explícitas para **estar capacitados** —no sólo para aplicar de memoria—. Los Requisitos piden cuatro **pares distintos** (un compendio + un glosario por nivel); este índice explica qué es cada nivel, por qué se separan y en qué orden se estudian.

La regla de la separación: **cada nivel tiene objeto propio**. Confundirlos es el error típico: hablar de "ingeniería" sin decir de cuál, o vender neuroingeniería cuando sólo se está diseñando un entorno. Cada par responde a tres preguntas —**qué es, qué se necesita saber para ejercerla, y cómo se practica aquí**— y su glosario da el vocabulario mínimo para no improvisar el lenguaje en una discusión técnica.

---

## 1. Los cuatro niveles

**Nivel 1 — Ingeniería (General).** La disciplina madre: diseño, construcción y operación de **sistemas** que resuelven problemas reales bajo restricciones, con ciclo de vida, requisitos, verificación y mejora. Su objeto es **lo artificial en general** (Simon). No habla de educación todavía.

**Nivel 2 — Ingeniería Aplicada a la Educación (General).** La misma disciplina **trasladada a contextos educativos de cualquier nivel y país**: diseño instruccional, ingeniería del aprendizaje (learning engineering), especificaciones de curso, calidad de servicios formativos (ISO 21001, ISO/IEC 29990), tecnología educativa. Su objeto: **el diseño de experiencias y sistemas de aprendizaje en abstracto** —funciona igual en una universidad alemán que en un taller mexicano.

**Nivel 3 — Ingeniería de la Educación.** La disciplina que construye y opera **programas y sistemas educativos completos** —de la ley y el currículo al aula— con requisitos legales no negociables, arquitectura curricular, calidad con puertas de verificación y configuración documentada. Su objeto: **el programa educativo como sistema**, y este proyecto es su instancia viva (requisitos = ley + CDN + evidencia; arquitectura = campos y Analítico; puertas = G1; configuración = Tandas y ADR).

**Nivel 4 — NeuroIngeniería y de la NeuroEducación.** Dos mitades: la **neuroingeniería** (disciplina que diseña sistemas que se conectan, se inspiran o intervienen sobre el sistema nervioso —imagen, interfaces, estimulación, neuroergonomía) y la **ingeniería de la NeuroEducación** (diseñar y operar entornos, experiencias y programas de aprendizaje optimizados según los mecanismos neurales del desarrollo —la serie completa de este proyecto es su instancia). Su objeto: **el cerebro como condición de diseño** —y también como límite honesto de lo que la ingeniería puede prometer.

---

## 2. Cómo se relacionan (y en qué se diferencian)

Los niveles se **anidan, no se solapan**: el 4 usa herramientas del 1–3 con objeto neural; el 3 exige el 2 y el 1 como lenguaje común; el 2 es portable a cualquier contexto; el 1 es previo a todo. Una frase los distingue: **el 1 diseña sistemas, el 2 diseña aprendizajes, el 3 diseña programas educativos enteros, el 4 diseña aprendizajes con el cerebro sobre la mesa —incluyendo saber cuándo retirar el cerebro de la mesa por respeto a él.**

Cada glosario usa prefijo propio para que una cita nunca se confunda: **IG** (ingeniería general), **IA** (aplicada a la educación), **IE** (ingeniería de la educación), **NI** (neuroingeniería y neuroeducación). Y todos ellos dialogan con los glosarios previos del proyecto (`glosario-neuroeducativo`, con prefijos A–J; `glosario-interseccionalidades`) —el mismo hábito de trazabilidad, cuatro campos más.

---

## 3. Los cuatro pares y qué contiene cada uno

`compendio-ingenieria-general.md` + `glosario-ingenieria-general.md` — fundamentos, ciclo de vida, calidad y gestión de configuración; términos IG1 en adelante.

`compendio-ingenieria-aplicada-educacion.md` + `glosario-ingenieria-aplicada-educacion.md` — diseño instruccional, ingeniería del aprendizaje, estándares de calidad educativa, tecnología; términos IA1 en adelante.

`compendio-ingenieria-de-la-educacion.md` + `glosario-ingenieria-de-la-educacion.md` — la disciplina del programa completo: requisitos legales/científicos, arquitectura curricular, puertas de calidad, patrones pedagógicos; términos IE1 en adelante (con puentes a los constructos de este proyecto).

`compendio-neuroingenieria-neuroeducacion.md` + `glosario-neuroingenieria-neuroeducacion.md` — neuroingeniería honesta (qué mide, qué interviene, qué NO hacemos), neuroergonomía, diseño de entornos para el cerebro del desarrollo, neuroética infantil; términos NI1 en adelante.

---

## 4. Ruta de capacitación recomendada

**Orden base (para cualquiera que entre nuevo):** Nivel 1 → Nivel 2 → Nivel 3 → Nivel 4. Cada compendio declara sus **áreas de conocimiento requeridas** con nivel esperado (básico entendedor / practicante / referente): se empieza por entender el lenguaje (glosario) y se cierra por **practicar en el proyecto** (el compendio da el "cómo se ejerce aquí").

**Rutas por rol.** *Sponsors y managers*: compendios 1 y 3 (sistemas y programa) con sus glosarios —nivel gestor—, más el mapa del 4 para decidir con honestidad límites. *Docentes*: compendios 3 y 4 con sus glosarios (y 2 si diseñan materiales), aplicados a los planes por grado. *Diseñadores instruccionales / quienes crean materiales*: nivel 2 primero, luego 3. *Quienes miden o argumentan con neurociencia*: nivel 4 con la neuroepistemología al lado (el filtro obligatorio: ninguna afirmación "neuro" sin fuente, `neuroepistemologia-compendio.md`).

**Vínculo con el resto del proyecto.** Esta capa se alimenta de la serie (informes, planes, acta) y la alimenta: los patrones de `neurogestion-patrones-y-antipatrones.md` son insumo del nivel 3; los axiomas y pilares gobiernan los cuatro niveles (ninguna ingeniería aquí procede sin sus guardas: no daño, evidencia, derechos).

---

## 5. Convenciones y estado

Redacción en prosa sin tablas (línea editorial de la serie), entradas de glosario con prefijo de nivel y fuente, encabezados en frase, versión **v0.1** en cada documento (compendios y glosarios están **abiertos por diseño**: se alimentan con la práctica y se revisan con los ciclos del Acta si se incorporan formalmente a la gobernanza). Los DOCX de esta carpeta se generan con el pipeline visual de la serie (portada, índice, foliado).

---

*Capa Ingeniería de la Educación · Índice v0.1 · Compañero de `Requisitos.md` · Proyecto Programa Sintético.*

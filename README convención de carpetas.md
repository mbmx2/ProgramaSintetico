# Convención de carpetas — Proyecto Programa Sintético / Neuroeducación

**Fecha de creación:** 26 de septiembre de 2026 · **Última actualización:** 27 de septiembre de 2026

## Estructura

```
Programa Sintético/
├── Primera Tanda/    → Archivo inmutable v1 (NO EDITAR)
├── Segunda Tanda/    → Trabajo intelectual v2 (axiomas + paquete + termómetro + docx previos)
├── Tercera Tanda/    → Edición visual v3 (estado v2 + tipografía elegante en DOCX) ← versión activa de la serie
├── Acta Constitutiva/→ Fase 4: Acta (guía y métrica, v0.5) + Roadmap de la década ← gobernanza
├── Ingeniería de la Educación/ → Capa de ingeniería: 4 niveles (general → aplicada → de la educación → neuro) con su par compendio+glosario por nivel, índice de capa, `gobernanza-inventario-de-instrumentos.md` (51 instrumentos + marco de referencia de 10 categorías) y `plataformas-fooss-de-gobernanza.md` (catálogo de plataformas libres por función), `Requisitos.md` (fuente) y DOCX propios
├── Plantillas/ → 24 plantillas rellenables: índice de uso + 12 del ciclo de vida (A1–A8, S1, D1, N1, T1) + 11 de gobernanza formal (GOB7, GOB8, GOB9, GOB10, GOB15, GOB16, GOB19, GOB20, GOB22, GOB25, GOB51)
├── docx/             → Entrega de lectura de documentos raíz (incluye `Manual-de-gobernanza-y-plantillas.docx`: inventario + plataformas + 24 plantillas en un solo DOCX)
├── Manual-de-gobernanza-y-plantillas.md → Fuente del DOCX maestro
├── Pilares-filosoficos.md   → Fuente de pilares (raíz, fuente viva) — incluye NeuroAxiología y NeuroEpistemología
├── propuesta-hibrida-de-posturas.md → Análisis del debate + Modelo Raíz–Red + contraposturas
├── neuroaxiologia-compendio.md · neuroepistemologia-compendio.md → Compendios vivos (pilares neuro, v0.1 en construcción desde los planes y programas)
├── neurogestion-patrones-y-antipatrones.md → Tercer compendio (neurogestión · antipatrones de enseñanza/aprendizaje · neuroantipatrones · 16 patrones ideales)
├── debateformasyalcances.md · tabla1–5.md · materialesdeapoyoyreferencias.md → Fuentes raíz del debate y del SEP
└── README (este archivo)
```

## Reglas

1. **`Primera Tanda/` es inmutable.** Contiene la base conceptual original (6 documentos de la serie + `basesconceptuales.md` + plan v1 + Plan Sintético PDF). Nunca se edita: es la línea base contra la cual se valida la Segunda Tanda (diferencias = solo adiciones) y la fuente verbatim de los axiomas.
2. **`Segunda Tanda/`** recibió la integración de los axiomas AX-1..3 (método híbrido, sin pérdidas), la fuente de pilares (`Pilares-filosoficos.md`), los **6 entregables de gobernanza** (`fundamentos-axiomas-del-programa.md`, `roadmap-cronograma-proyecto.md`, `adr-modelo-construccion-programa-analitico-curso.md`, `foda-programa-neuroeducacion-preescolar.md`, `soach-estrategias-programa-neuroeducacion.md`, `plan-de-estudios-curso-andragogia-neuroeducacion.md`), el plan de fase y la **Puerta G1** (`puerta-G1-revision-y-aprobacion.md`). Es además el archivo de respaldo previo a la edición visual.
3. **Futuras tandas:** antes de iniciar una capa mayor, crear carpeta nueva y copiar el estado vigente; la anterior queda como archivo. Cada revisión mayor trienal del Acta abre una nueva Tanda (ver `Acta Constitutiva/Roadmap-deca-10-anios-actualizaciones.md`, §6).
4. **Fuente verbatim de los axiomas:** `Primera Tanda/basesconceptuales.md`. **Fuente de los pilares:** `Pilares-filosoficos.md`. Documento canónico con anclaje y guardas: `Segunda Tanda/fundamentos-axiomas-del-programa.md`.
5. **`Tercera Tanda/` (vigente para la serie):** snapshot del estado final de Segunda Tanda, con **edición visual** (portada, índice automático en página propia, tipografía serif Georgia, encabezados azules, citas en panel, foliado `— N —`, párrafos sin tablas) y ampliada con `actividades-2do-y-3ro-de-jardin.md` y `planes-por-grado-inclusion-y-ayudas.md` (filtro de los 34 Contenidos). DOCX en `Tercera Tanda/docx/`.
6. **`Acta Constitutiva/` (fase 4):** contiene `Acta-Constitutiva-Proyecto-Neuroeducacion-Preescolar-3-6.md` (**borrador v0.5** — v0.2: enmienda epistemológica, modelo Raíz–Red, Arts. 2, 15, 16, 19; v0.3: enmienda de trazabilidad, anexos de fuentes raíz, auditoría epistémica y errata; v0.4: pilares **NeuroAxiología** y **NeuroEpistemología** con sus compendios anexados; v0.5: anexo del compendio de **neurogestión y patrones**; entra en vigor al firmarse el DoD de la Puerta G1, Artículo 27) y `Roadmap-deca-10-anios-actualizaciones.md` (ciclos de actualización legal semestral, científica anual y revalidación trienal). DOCX en `Acta Constitutiva/docx/`. Con vigencia de **10 años** desde la firma, con revalidaciones obligatorias (Artículos 22–25 del Acta).
6b. **Fuentes raíz del debate y sus derivados:** `propuesta-hibrida-de-posturas.md` (análisis del debate, Modelo Raíz–Red, 12 contraposturas, mapa de integración Acta/pilares/materiales) con su DOCX en `docx/`; `debateformasyalcances.md` (conversación fuente, inmutable); `tabla1.md`–`tabla5.md` (Contenidos y PDA SEP, inmutables); `materialesdeapoyoyreferencias.md` (extracción SEP + sección *Aporte del proyecto* con contraposturas y referencias).
7. **Regla general de DOCX:** todo `.md` se puede regenerar como DOCX elegante con el pipeline (`pandoc` + `reference-elegante.docx` + posproceso de foliado); los `.md` son la fuente viva, los `.docx` la entrega de lectura.

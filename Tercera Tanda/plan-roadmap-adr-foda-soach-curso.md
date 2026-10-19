# Plan: Segunda Tanda — Integración transversal/longitudinal de los axiomas + paquete de 6 entregables (previo al Acta Constitutiva)

## Contexto y estructura de carpetas (ya creada por el usuario)

```
Programa Sintético/
├── Primera Tanda/     ← ARCHIVO INMUTABLE v1 (los 9 archivos originales, movidos por el usuario; NO se edita)
│   ├── neuroeducacion-preescolar-3-6-informe.md                (D1)
│   ├── analisis-programa-sintetico-integracion-neuroeducacion.md (D2)
│   ├── estres-crisis-calma-y-entornos-seguros-3-6.md           (D3)
│   ├── glosario-neuroeducativo.md                              (D4, 193 términos)
│   ├── glosario-interseccionalidades-y-aparatos-ideologicos.md (D5, 124 términos)
│   ├── analisis-transversal-constitucion-cdn-neuroeducacion-ia.md (D6)
│   ├── basesconceptuales.md          ← FUENTE VERBATIM de los axiomas (usuario)
│   ├── plan-roadmap-adr-foda-soach-curso.md  (plan v1)
│   └── Programa_Sintetico_Fase_2_ DAVID_BETAN.pdf
├── Segunda Tanda/     ← ESPACIO DE TRABAJO v2 (toda la ejecución de esta fase)
└── README de convención (en raíz)
```

**Propuesta del usuario (aceptada como buena práctica de gestión de versiones):** resguardar la base conceptual original (Primera Tanda) y construir la segunda capa teórico-práctico-filosófica sobre una copia en Segunda Tanda — así no se pierde ni lo primero ni lo segundo.

**Objetivo de esta fase:** antes del Acta Constitutiva: (1) integrar los **3 axiomas fundacionales** (AX-1..3) en los 6 documentos de la serie de forma **transversal y longitudinal**, y (2) **crear los 6 entregables** del paquete de gobernanza.

## Decisiones ya tomadas con el usuario

1. **Alcance**: integración en la serie **+ paquete completo** de 6 entregables, todo antes del Acta.
2. **Profundidad de integración en la serie**: **híbrida** — resguardar el contenido existente (no reescribir) y a la vez tejer la nueva capa: en cada documento, **una sección compacta** "Fundamentos transversales (AX-1..3)" con el anclaje propio del documento, más **2–4 anclajes inline** en secciones donde encajan naturalmente. Referencias cruzadas, no reescrituras.
3. **Ubicación**: **todo en Segunda Tanda** — la copia de los 9 archivos (con integración aplicada) + los 6 entregables nuevos. Primera Tanda queda **inmutable**. Raíz = README + las dos carpetas.
4. **Paquete**: 6 archivos: `fundamentos-axiomas-del-programa.md`, `roadmap-cronograma-proyecto.md`, `adr-modelo-construccion-programa-analitico-curso.md`, `foda-programa-neuroeducacion-preescolar.md`, `soach-estrategias-programa-neuroeducacion.md`, `plan-de-estudios-curso-andragogia-neuroeducacion.md`.
5. **Formato curso**: 8 módulos, CTE quincenal (~16 sem), sponsors/managers en M1/M2/M8.
6. **Sin fechas de calendario**: solo secuencia relativa en semanas.
7. **Alcance**: piloto 1 plantel, diseño escalable.
8. **Redacción axiomas**: verbatim (fuente: `Primera Tanda/basesconceptuales.md`) + anclaje académico + guardas.
9. **Unificación**: mapa de principios (AX fundacional / P0–P3, T1–T4, G22, B26, IA-J operativos) **sin romper las etiquetas existentes**.

## Tarea 0 — Preparación de carpetas

1. Verificar que Primera Tanda contiene los 9 archivos y **no se modifica** en toda la fase (validación por mtime/tamaño al cierre).
2. Copiar los 9 archivos de `Primera Tanda/` → `Segunda Tanda/`.
3. Crear `README de convención.md` en la raíz: qué es cada tanda, regla de inmutabilidad de Primera, cómo se versiona una futura "Tercera Tanda", índice de contenidos.

## Tarea 1 — Integración híbrida de AX-1..3 en los 6 documentos (en Segunda Tanda)

Para cada documento: **(a)** añadir sección compacta `## Fundamentos transversales — Axiomas del programa (AX-1..3)` (texto + tabla de consecuencias prácticas + puntero al canónico), **(b)** 2–4 anclajes inline como notas `[AX-n]` en secciones existentes, **(c)** sin alterar tablas, numeración ni contenido previo.

**D1 informe neuro.** **Sección nueva (anclaje propio):** Los axiomas como base paidagógica: error-información ↔ evaluación formativa; niño = producto de adultos/realidad; resignificar mitos del desarrollo · **Anclajes inline (2–4):** §4.2 (el error del niño es dato), §5.1 (adulto como consecuencia), §8 (conclusión con AX-1)

**D2 integración Programa.** **Sección nueva (anclaje propio):** AX en los 3 planos del Analítico: realidad (AX-2), contextualización (AX-3), formulación (AX-1) · **Anclajes inline (2–4):** §4.2 (evaluación formativa), §6 (qué NO hacer), §8 conclusiones

**D3 estrés/crisis.** **Sección nueva (anclaje propio):** Crisis como información (AX-1) + historia adulta y co-regulación (AX-2) + resignificar la propia infancia (AX-3) · **Anclajes inline (2–4):** §1.2 (meltdown ≠ rabieta: leer, no juzgar), §5.1 frustración productiva, §6 protocolo

**D4 glosario neuro.** **Sección nueva (anclaje propio):** **Entradas AX-1..3 en el preámbulo** (junto a P0) + nota de mapa unificado en Bloque G · **Anclajes inline (2–4):** G22 (Consecuencia Adulta ↔ AX-2), bloque J (neuromitos como anti-resignificación), I16 (retrospectiva ↔ AX-1)

**D5 glosario interseccional.** **Sección nueva (anclaje propio):** AX-3 y la mirada de matices vs. binarismo; AX-2 y posicionalidad/historia material · **Anclajes inline (2–4):** A8 posicionalidad (AX-2), A9 esencialismo (AX-3), B20 sentido común (AX-3)

**D6 análisis transversal.** **Sección nueva (anclaje propio):** AX como corolario longitudinal (§0 principios T1–T4 + AX) · **Anclajes inline (2–4):** §4.4 neuroandragogía (AX-2/AX-3), §7 recomendaciones (+R11: axiomas en el Acta), §5.1 (límites de la IA: AX-2 — la IA no ha vivido)

**Cadena longitudinal** (consistencia de la etiqueta): misma redacción, mismos IDs AX-1..3 en los 6 docs, enlazando al canónico `fundamentos-axiomas-del-programa.md`.

## Tarea 2 — `Segunda Tanda/fundamentos-axiomas-del-programa.md` (canónico)

- AX-1, AX-2, AX-3: verbatim de `basesconceptuales.md` (solo erratas: "no es es útil"→"nos es útil"; "si dse"→"si se") + anclaje académico por axioma + guardas (no daño B26/minimización de datos; no determinismo/no culpa; no positivismo tóxico) + tabla consecuencias paidagógico/andragógico.
- Mapa unificado de principios (fundacional AX ↔ operativos P0–P3, T1–T4, G22, B26, 6 principios IA, bloque J) con documento fuente y dónde se aplica (ADR/M1/FODA/SOACH).
- Regla de uso anti-slogan (F9 [D5]).

## Tarea 3 — `Segunda Tanda/roadmap-cronograma-proyecto.md`

- Fases F0–F5 sin fechas (semanas relativas): F0 gobernanza+aprobación de axiomas+canónico (~2 sem) → F1 curso M1–M8 (~16 sem) → F2 codiseño Analítico (~4 sem) → F3 validación CTE (~2 sem) → F4 Acta (hito, fuera de alcance) → F5 diseño de escalamiento.
- Gantt Mermaid (`axisFormat` semanas), hitos/DoD por fase, riesgos, sección "Principios rectores" → AX.

## Tarea 4 — `Segunda Tanda/adr-modelo-construccion-programa-analitico-curso.md`

- **AD-0** adopción de AX-1..3 (Estado: Propuesta → Acta). AD-1…AD-6 (modelo de capa transversal, arquitectura 8 módulos, requisitos del Analítico, metodología andragógica, política IA + anti-neuromitos, gobernanza RACI). AD-1 y AD-4 referencian AX-1/AX-2.
- Cierre: matriz trazabilidad (doc → decisión → módulo → salida en Analítico).

## Tarea 5 — `Segunda Tanda/foda-programa-neuroeducacion-preescolar.md`

- 4 cuadrantes × 7–10 ítems con fuente de la serie; **+ Fortaleza**: "fundamento axiomático explícito (AX-1..3) compartido por todas las audiencias".

## Tarea 6 — `Segunda Tanda/soach-estrategias-programa-neuroeducacion.md`

- FO/DO/FA/DA derivados 1:1 del FODA; FO usa AX-1 (cultura de error-útil), DA traduce AX-3 (laboratorios de resignificación en CTE); cada estrategia con acción, rol responsable y métrica.

## Tarea 7 — `Segunda Tanda/plan-de-estudios-curso-andragogia-neuroeducacion.md`

- Perfil de egreso por audiencia; **M1–M8** con propósito, doc fuente, resultados de aprendizaje, guion de sesión (tiempos relativos), actividades andragógicas, tarea, acreditación.
- **M1 abre con bloque de axiomas** (lectura verbatim + "¿qué cambiaría en tu práctica si AX-1 fuera cierto?").
- Matriz de trazabilidad: módulo × documento × plano del Analítico × axioma × KPI.

## Tarea 8 — Cierre

1. Copiar este plan actualizado a `Segunda Tanda/plan-roadmap-adr-foda-soach-curso.md`.
2. Revisión cruzada (validación) y verificación de inmutabilidad de Primera Tanda.

## Validación

- **Primera Tanda intacta**: 9 archivos, mismo tamaño/mtime que al inicio.
- **Verbatim** de AX contrastado contra `Primera Tanda/basesconceptuales.md` (solo erratas).
- **Integración híbrida**: cada D1–D6 tiene exactamente 1 sección nueva + 2–4 anclajes; ninguna tabla/numeración previa alterada (diff contra Primera Tanda: solo adiciones).
- **Etiqueta AX idéntica** en los 6 docs y en los 6 entregables; canónico único.
- **Cobertura**: 6 docs → M2–M7; M1 axiomas; M8 laboratorio; AD-0 presente; FODA con fortaleza AX; SOACH con ejes AX-1/AX-3; roadmap con F0-axiomas.
- **Sin fechas absolutas**; Analítico conforme al PDF SEP; Knowles por ítem; Mermaid válido.

## Riesgos y cuidados

- Romper contenido existente → método híbrido + validación por diff (solo adiciones).
- Duplicar el canónico → la fuente verbatim es Primera Tanda/basesconceptuales; el canónico es el único con anclaje+guardas; la serie solo referencia.
- AX-1 como "todo riesgo vale" → guardas B26. AX-2 como culpa → "responsabilidad presente".
- Primera Tanda editada por error → README de inmutabilidad + verificación final.

## Fuera de alcance

- Acta Constitutiva (fase siguiente; los axiomas quedan listos como su preámbulo).
- Ejecución real del curso, montos, contrataciones.
- Editar archivos de Primera Tanda.

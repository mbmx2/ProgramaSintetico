# Glosario Neuroeducativo

## Documento base previo al Acta Constitutiva del proyecto

*Versión 1.0 · Proyecto de desarrollo pedagógico preescolar (3–6 años) · Serie documental: (1) informe de neuroeducación, (2) análisis e integración con el Programa Sintético, (3) estrés/crisis/calma/entornos, (4) **este glosario** · Fecha: 26 de septiembre de 2026*

---

## 0. Preámbulo: para qué sirve este glosario

**Propósito.** Que padres, tutores, profesores, aprendientes, estudiantes, directivos, sponsors, stakeholders, managers y cualquier participante del proyecto **compartan un mismo léxico**, de modo que el Acta Constitutiva y todas las decisiones de arquitectura sean **comprensibles, trazables, observables y aceptables** para todos los involucrados.

**Por qué incluye andragogía además de paidagogía.** Prácticamente todos los actores del proyecto son adultos: sponsors, stakeholders, managers, tutores, profesores y familias. La mayor parte del contenido del proyecto debe ser **discutido, decidido y aprendido entre adultos**; los niños son el destinatario final del resultado de esos adultos. Por eso el glosario separa dos campos:

- **Neuropaidagogía** (bloque A): cómo aprende el cerebro del niño de 3–6.
- **Neuroandragogía / NeuroAprendizaje Andragógico** (bloque G): cómo aprende el cerebro del adulto que decide, enseña, financia y acompaña.

> **Principio de Consecuencia Adulta (P0):** *el niño es la consecuencia del resultado de los adultos con los que convive*. La evidencia lo respalda: serve and return, co-regulación y ecosistemas del desarrollo (Bronfenbrenner) muestran que el adulto es la variable ambiental de mayor impacto sobre el niño. Un proyecto que forma solo a los niños y no a los adultos no escala.

**Convenciones de trazabilidad:**

| Etiqueta | Significado |
|---|---|
| [I1] | `neuroeducacion-preescolar-3-6-informe.md` (informe base) |
| [I2] | `analisis-programa-sintetico-integracion-neuroeducacion.md` |
| [I3] | `estres-crisis-calma-y-entornos-seguros-3-6.md` |
| [PS] | Plan de Estudio 2022 / Programa Sintético Fase 2 (SEP, 2024) |
| [PM] | Modelo de gestión de proyectos del proyecto |
| (autor, año) | Fuente externa citada en Referencias |

**Cómo leerlo según su rol (lectura mínima sugerida):**

| Rol | Bloques imprescindibles |
|---|---|
| Sponsors / directivos / managers | P0, G, H, I, J |
| Profesores y tutores | A, B, C, D, E, F, H |
| Familias y padres | C, D, F, J + preámbulo |
| Estudiantes / aprendientes | A, B, E, G |
| Todos (sesión de arranque) | P0 + reglas de lenguaje + índice |

**Mapa conceptual de los bloques:**

```mermaid
flowchart TD
    A[Bloque A<br>Neuropaidagogía<br>y neurociencia del niño] --> E[Método en el aula]
    B[Bloque B<br>Desarrollo y pilares<br>filosóficos] --> E
    C[Bloque C<br>Regulación, estrés<br>y crisis] --> E
    D[Bloque D<br>Trato y vínculo] --> E
    F[Bloque F<br>Neurodiversidad<br>e inclusión] --> E
    G[Bloque G<br>NeuroAprendizaje<br>Andragógico - adultos] --> S[Decisión, formación<br>y sostén de los adultos]
    H[Bloque H<br>Marco curricular<br>NEM/SEP] --> E
    I[Bloque I<br>Gestión de<br>proyectos] --> S
    J[Bloque J<br>Neuromitos<br>(qué NO usar)] -.filtra.-> A & E & G
    S --> E
    E --> R[Resultado: niño 3–6]
```

---

## Bloque A — Neuropaidagogía y neurociencia del desarrollo (3–6 años)

| ID | Término | Definición operativa | Base y uso en el proyecto |
|---|---|---|---|
| A1 | **Neuroeducación** | Campo interdisciplinario que aplica hallazgos de neurociencia y psicología del diseño y la práctica educativa. No es "enseñar neurociencia a los niños" sino **enseñar mejor a los niños con base en cómo aprende el cerebro**. | [I1] Marco del proyecto |
| A2 | **Neuropaidagogía** | Rama de la neuroeducación centrada en el aprendizaje **infantil** (aquí, 3–6 años): ventanas de desarrollo, juego, regulación, lenguaje. | [I1] Bloque A del glosario |
| A3 | **Neurona** | Célula que procesa y transmite información mediante señales eléctricas y químicas. | [I1 §3.1] |
| A4 | **Sinapsis** | Punto de conexión entre neuronas; su fuerza determina qué circuitos se usan y cuáles se debilitan. "Las que no se usan, se debilitan". | [I1 §3.1] |
| A5 | **Sinaptogénesis** | Formación masiva de sinapsis; en los primeros años se crean **más de 1 millón de conexiones por segundo**. | Harvard/NSCDC [I1 §3.1] |
| A6 | **Poda sináptica (pruning)** | Eliminación selectiva de sinapsis poco usadas para hacer los circuitos eficientes; es normal y necesaria. | [I1 §3.1] |
| A7 | **Mielinización** | Revestimiento de los axones que acelera la transmisión; explica por qué ciertas habilidades se vuelven automáticas con la práctica. | [I1 §3.1] |
| A8 | **Arquitectura cerebral** | Estructura física de las redes cerebrales construida por **genética + experiencia**; la genética da el plano, la experiencia decide la calidad. | Harvard [I1 §3.1] |
| A9 | **Neuroplasticidad** | Capacidad del cerebro de cambiar por la experiencia; máxima al inicio de la vida y **presente toda la vida** (ver G12). | [I1 §3.1] |
| A10 | **Periodo sensible / ventana crítica** | Etapa en la que un circuito se configura con especial facilidad (lenguaje, orden, refinamiento sensorial-motor a los 3–6). **Ojo:** la ventana extrema "si no se estimula antes de 3, se pierde" es falso (J6). | Montessori; Knudsen [I1 §4.1, §3.5] |
| A11 | **Corteza prefrontal** | Región del "freno" y la planificación; madura hacia los 18–20 y sigue afinándose hasta los ~25. **Por eso un niño de 3–6 no "reacciona como un adulto".** | NIMH; Hardy 2023 [I1 §2.3] |
| A12 | **Funciones ejecutivas (EF)** | Familia de capacidades que permiten "jugar mentalmente con las ideas, pensar antes de actuar y adaptarse": inhibición, memoria de trabajo y flexibilidad cognitiva. | Diamond 2013 [I1 §3.4] |
| A13 | **Inhibición de respuesta** | Freno de los impulsos; primera EF en madurar (esperar turnos, no correr a la calle). Se entrena en juego de reglas. | [I1 §3.4, §6.4] |
| A14 | **Memoria de trabajo** | Mantener y manipular información en mente (recordar un protocolo de 3 pasos). Límite corto a esta edad. | [I1 §3.4] |
| A15 | **Flexibilidad cognitiva** | Cambiar de estrategia o perspectiva; se construye sobre las dos anteriores, hacia fin de preescolar/primaria. | [I1 §3.4] |
| A16 | **Amígdala** | Centro de detección de amenaza; activa la alarma antes de que la corteza prefrontal responda. En crisis, "primero alarma, luego razón". | [I1 §3.3] |
| A17 | **Eje HHA (hipotálamo-hipófisis-adrenal)** | Sistema hormonal de la respuesta al estrés; si se activa de forma excesiva o prolongada sin apoyo, produce estrés tóxico. | NSCDC [I1 §3.3] |
| A18 | **Estrés tóxico / tolerable / positivo** | Tóxico: activación intensa o prolongada **sin adulto de apoyo** (daña arquitectura cerebral). Tolerable: fuerte pero amortiguada. Positivo: reto con acompañamiento (fortalece). | Harvard [I1 §3.3; I3 §1.1] |
| A19 | **Serve and return (servir y devolver)** | Intercambio ida y vuelta adulto-niño (el niño señala → el adulto responde); construye lenguaje, vínculo y bienestar social. | Harvard [I1 §3.2] |
| A20 | **Estado de activación (arousal)** | Nivel de alerta del sistema nervioso: ni muy bajo (distracción) ni muy alto (colapso). El objetivo es el **nivel óptimo**, no la quietud total. | [I3] |
| A21 | **Interocepción / exterocepción** | Percibir el interior del cuerpo (hambre, dolor, vejiga) / el exterior (ruido, tacto). Diferencias en la interocepción explican crisis "sin causa visible". | [I3 §2.1] |
| A22 | **Neurotransmisores** | Mensajeros químicos (dopamina, serotonina, GABA…). Evitar simplificaciones: la dopamina no es "la molécula del placer" sino de **seguimiento de metas y aprendizaje**. | [I1 §3.5] |
| A23 | **Lateralización hemisférica** | Existe especialización (el lenguaje suele ser más izquierdo), pero **cooperan siempre**; no hay "personas de izquierda o de derecha" (ver J2). | [I1 §3.5] |

---

## Bloque B — Psicología del desarrollo, aprendizaje y pilares filosóficos

| ID | Término | Definición operativa | Base y uso en el proyecto |
|---|---|---|---|
| B1 | **Constructivismo** | El sujeto **construye** su conocimiento interactuando con el mundo; no lo recibe pasivamente. Filosofía rectora del proyecto. | Piaget [I1 §3.6] |
| B2 | **Esquema, asimilación, acomodación, equilibración** | Esquema = patrón de acción; asimilarlo = encajar lo nuevo en lo que sé; acomodarlo = cambiar mi esquema; equilibración = buscar coherencia. Cómo aprende de verdad. | Piaget [I1 §3.6] |
| B3 | **Etapa preoperacional (2–7 años)** | Pensamiento **simbólico y egocéntrico**, sin lógica formal ni conservación. Implica: exigir razonamiento abstracto a los 3–6 es **frustración innecesaria**. | Piaget [I1 §2.4] |
| B4 | **Pensamiento simbólico / función simbólica** | Representar algo con otro thing (un palo = caballo). Base del juego pretendido, la escritura y el conteo. | Piaget [I1 §4.1] |
| B5 | **Egocentrismo (sentido piagetiano)** | No es "egoísmo": es **dificultad para tomar la perspectiva del otro** antes de ~5 años (madura con la teoría de la mente). | Piaget [I1 §3.6] |
| B6 | **Conservación** | Entender que la cantidad no cambia al modificar la forma (misma agua en vaso alto o bajo). A los 3–6 **aún no se conserva**; es un error esperable, no ignorancia. | Piaget [I1 §2.4] |
| B7 | **Socioculturalismo** | El aprendizaje es **social y cultural**; primero interpersonal (con otro), luego intrapersonal (propio). | Vygotsky [I1 §3.6] |
| B8 | **Zona de desarrollo próximo (ZDP)** | Distancia entre lo que el niño hace solo y lo que hace **con ayuda**. Enseñar ahí es el punto óptimo: ni fácil (aburrido) ni imposible (frustrante). | Vygotsky [I1 §3.6] |
| B9 | **Andamiaje (scaffolding)** | Apoyo temporal que se da y **se retira** según el niño pueda. El adulto no resuelve: acompaña y luego se retira. | Wood, Bruner & Ross 1976 [I1 §3.6] |
| B10 | **Teoría de la mente** | Comprender que otros tienen deseos, creencias y emociones **distintos** a los propios; base de empatía y cooperación. | Wellman et al. 2001 [I1 §4.2] |
| B11 | **Creencias falsas** | Entender que alguien puede creer algo que no es real (madura ~4½–5 años); hito central de la teoría de la mente. | Wellman 2001 [I1 §4.2] |
| B12 | **Apego** | Vínculo afectivo duradero con el cuidador principal; la seguridad del apego condiciona exploración y regulación. | Bowlby/Ainsworth [I1 §5] |
| B13 | **Base segura** | Desde el apego seguro el niño **explora y se arriesga** porque sabe que hay un refugio al que volver. El adulto es esa base. | Bowlby [I1 §6.6] |
| B14 | **Cognitivismo** | Enfoque que estudia procesos internos (atención, memoria, resolución de problemas); fuente de la teoría de la carga cognitiva (G13). | [I1] |
| B15 | **Conductismo / behaviorismo** | Enfoque centrado en estímulo-respuesta y refuerzo; útil para ciertas técnicas (modelado, entrenamiento conductual) pero **insuficiente** como visión completa del aprendizaje. | Contraste en [I1] |
| B16 | **Modelado / aprendizaje vicario** | Aprender observando a otros y sus consecuencias. Los niños **y los adultos** aprenden así: el docente es el modelo más observado del aula. | Bandura [I1 §5.2] |
| B17 | **Ecosistemas del desarrollo** | Cada niño está inmerso en microsistema (familia/aula), mesosistema (escuela-familia), exosistema y macrosistema; intervenir solo en el aula es insuficiente. | Bronfenbrenner [I2 §4.2] |
| B18 | **Modelo médico vs. modelo social de la discapacidad** | Médico: el déficit está en la persona. Social: el problema está en barreras del entorno. **El proyecto adopta el modelo social + neuroafirmación (F11).** | Filosofía del proyecto [I3 §5.4] |
| B19 | **Práctica basada en evidencia (EBP)** | Decisión pedagógica sustentada en la mejor evidencia disponible + experiencia profesional + contexto. **Filtro obligatorio** de todo material "neuro-". | [I1 §3.5] |
| B20 | **Pensamiento crítico** | "Juicio deliberado y autorregulado" de interpretar, analizar, evaluar, inferir y explicar con base en evidencia (versión adulta); en 3–6: preguntar, comparar, notar lo raro. | Facione 1990; OCDE [I1 §2.2, §4.2] |
| B21 | **Metacognición** | "Pensar sobre el propio pensar": saber qué sé, qué no sé y qué estrategia uso. Precursor en 3–6: revisar su propio error. | [I1 §4.2] |
| B22 | **Motivación intrínseca / extrínseca y efecto de sobrejustificación** | Hacer algo por interés propio / por recompensa externa. Premiar lo que ya gusta **socava** la motivación interna. | Deci & Ryan 1987 [I3 §5.5] |
| B23 | **Orientación a dominio vs. rendimiento** | Dominio: aprender y mejorar. Rendimiento: parecer competente y evitar el error. Elogiar el talento fijo induce rendimiento; elogiar estrategia y esfuerzo induce dominio. | [I1 §5.4] |
| B24 | **Inteligencias múltiples** | Modelo descriptivo de Gardner (8 capacidades humanas). **Útil como repertorio, NO como taxonomía validada ni diagnóstico** (crítica de la comunidad científica). | Gardner 1983; críticas [I1 §2.1] |
| B25 | **Inteligencia emocional** | Versión académica (Salovey-Mayer): percibir, comprender y regular emociones propias y ajenas. Versión popular (Goleman): competencias de liderazgo, con método más criticado. | [I1 §2.1] |
| B26 | **Principio de no daño (primum non nocere)** | Ninguna práctica del proyecto puede dañar el bienestar del niño o del adulto en nombre de "resultados". Límite ético del Acta Constitutiva. | [I1 §7; I3] |
| B27 | **Pensamiento crítico adulto vs. infantil (continuidad)** | El estándar adulto es la **meta**; el niño de 3–6 construye **precursores**. No se evalúa al niño con criterios de adulto. | [I1 §2.4] |

---

## Bloque C — Regulación, estrés y crisis

| ID | Término | Definición operativa | Base y uso en el proyecto |
|---|---|---|---|
| C1 | **Autorregulación** | Capacidad propia de modular emoción, atención y conducta. **No nace: se construye** desde la co-regulación. | [I1 §5.1] |
| C2 | **Co-regulación** | Interacciones cálidas y responsivas en las que el adulto **ayuda al niño a regularse**: se regula primero, valida, modela y devuelve la estrategia. **Palanca #1 del proyecto.** | NAEYC; Murray 2015 [I1 §5.1; I3] |
| C3 | **Regulación / desregulación emocional** | Modular la emoción adecuadamente / perder el control (explosión o cierre). En preescolar la desregulación es **esperable**, no patológica. | [I1 §4.3] |
| C4 | **Ventana de tolerancia** | Rango de activación en el que la persona puede pensar y aprender. Por debajo: apagón (shutdown); por encima: colapso (meltdown). **El adulto mantiene al niño dentro de su ventana.** | Siegel [I3] |
| C5 | **Rabieta (tantrum)** | Exabrupto con **meta** (obtener o evitar algo). Común: ~1/día a los 3–4 años es promedio. Se enseña con espera y alternativas. | Hoyniak 2022 [I3 §1.2] |
| C6 | **Colapso (meltdown)** | **Falla del sistema por sobrecarga**; no es voluntario ni manipulador. Se protege, no se razona. | [I3 §1.2] |
| C7 | **Cierre (shutdown)** | Retirada y "apagón" como respuesta a la sobrecarga; también no es desobediencia. | [I3 §1.2] |
| C8 | **Cadena rumbling → rage → recovery** | Fases de la crisis: señales tempranas → explosión → recuperación. **Intervenir en "rumbling" evita la mayoría de las crisis.** | Myles & Southwick [I3 §1.3] |
| C9 | **Sobrecarga sensorial** | Exceso de estímulos (ruido, luz, multitudes, texturas) que rebasa la capacidad de procesamiento y dispara la alarma. | [I3 §2.2] |
| C10 | **Hiperreactividad / hiporreactividad sensorial** | Respuesta exagerada ("¡no me toques!") o apagada ("no siente dolor/frío") ante estímulos. Ambas son conductas de regulación, no capricho. | Raevsky 2025 [I3 §1.4] |
| C11 | **Estimulación reguladora (stimming)** | Repeticiones (girar, aletear, sonidos) que **regulan**. Se permite salvo daño; suprimirla sin sustituto **aumenta** la crisis. | Neuroafirmación [I3 §5.4] |
| C12 | **Monotropismo** | Estilo de atención de **foco intenso y único**; explica intereses profundos y el coste de las interrupciones. Recurso didáctico, no defecto. | Murray et al. [I3 §3.4] |
| C13 | **Alexitimia** | Dificultad para identificar y nombrar las propias emociones; común en algunos perfiles ND; se compensa con vocabulario emocional externo. | [I3 §2.6] |
| C14 | **Resiliencia** | Capacidad de recuperarse de la adversidad **con apoyo**; no es "aguantar solo". | [I1 §2.3] |
| C15 | **Frustración innecesaria vs. productiva** | Innecesaria: imposible, sin aviso, sin salida (evitar). Productiva: en la ZDP con acompañamiento (buscar). **Regla de oro del diseño.** | [I3 §5.1] |
| C16 | **Rincón de calma / espacio tranquilo** | Zona de baja estimulación a la que el niño **elige** ir para re-regularse. **Nunca es castigo ni time-out**, y su uso se enseña explícitamente. | NYSED [I3 §3.3] |
| C17 | **Time-out / estancamiento** | Aislamiento como castigo. **No se usa**: silencia, no enseña habilidad y rompe el vínculo. | NJ-DOE [I3 §5.5] |
| C18 | **Deuda sensorial / fatiga de desregulación** | Acumulación de sobrecarga a lo largo del día; estalla típicamente al final. Se previene con pausas y zonas de baja estimulación. | [I3] |
| C19 | **Protocolo de crisis (antes/durante/después)** | Secuencia acordada por todos los adultos: prevenir básicos → proteger sin razonar → acompañar en silencio → reparar y plan después. | [I3 §6] |
| C20 | **Intercepción conductual** | Observar señales tempranas (puños apretados, aleteo, quedarse quieto de golpe) para intervenir antes del estallido. Formación básica del docente. | [I3 §1.3] |

---

## Bloque D — Trato, vínculo y estilo educativo

| ID | Término | Definición operativa | Base y uso en el proyecto |
|---|---|---|---|
| D1 | **Estilo autoritativo** | **Alta exigencia + alta calidez + razones.** El estilo con mejores resultados; adoptado por el proyecto. | Baumrind [I1 §5.1] |
| D2 | **Estilo autoritario** | Exigencia sin calidez ("porque sí"): sumisión, ansiedad, baja iniciativa. **Prohibido por diseño.** | Baumrind [I1 §5.1] |
| D3 | **Estilo permisivo** | Calidez sin exigencia: baja autorregulación y problemas de límites. **Prohibido por diseño.** | Baumrind [I1 §5.1] |
| D4 | **Estilo negligente** | Ni exigencia ni calidez: peores resultados en todas las áreas. | Baumrind [I1 §5.1] |
| D5 | **Validación emocional** | Reconocer que la emoción tiene sentido antes de corregir la conducta: "estás enojado; no se golpea". Validar ≠ permitir. | [I1 §5.1] |
| D6 | **Empatía vs. simpatía** | Empatía: sentir **con** el otro desde su perspectiva. Simpatía: sentir **por** el otro desde la tuya. El aula necesita empatía. | [I1 §5.1] |
| D7 | **Reparación vs. castigo** | Reparación: arreglar, ayudar, disculparse, rehacer (enseña consecuencia y empatía). Castigo: sólo produce miedo y evasión. | [I1 §5.4; I3 §4.5] |
| D8 | **Límites claros** | Pocos, visibles, con **razón** y consistentes entre adultos; siempre acompañados de decir qué **SÍ** hacer. | [I1 §5.1] |
| D9 | **Sensibilidad/responsividad del cuidador** | Capacidad de percibir la señal del niño y responder de forma oportuna y adecuada; predictora central de apego seguro. | Ainsworth [I1 §5] |
| D10 | **Respuesta contingente** | Responder **a lo que el niño hizo**, no en automático: es el "devolver" del serve and return. | [I1 §3.2] |
| D11 | **Alta exigencia y alta calidez** | Síntesis del proyecto: límites firmes **con** cálido vínculo; no es ni dureza ni condescendencia. | [I3 §5.2] |
| D12 | **Apoyo a la autonomía vs. control psicológico** | Apoyo: ofrecer elección, razones y perspectiva (↑ bienestar en todas las culturas). Control: presión, amenaza, amor condicional (↑ malestar). | Bradshaw 2025 (n=126,423) [I3 §5.2] |

---

## Bloque E — Metodología, ambiente y evaluación en el aula

| ID | Término | Definición operativa | Base y uso en el proyecto |
|---|---|---|---|
| E1 | **Ambiente preparado** | Espacio pensado: materiales reales a su altura, ordenados, autocorregibles; el ambiente enseña sin que el adulto intervenga. | Montessori [I1 §4.1] |
| E2 | **El ambiente como "tercer docente"** | Idea de Reggio Emilia: el espacio, los materiales y los tiempos **enseñan** por sí mismos. Base del diseño físico del plantel. | Reggio [I3 §4.1] |
| E3 | **Práctica apropiada al desarrollo (DAP)** | Decisión pedagógica con tres lentes: generalidad (edad), individualidad (este niño) y contexto (familia/cultura). | NAEYC 2020 [I1 §5.2] |
| E4 | **Evaluación formativa** | Evaluación **para** aprender: observación continua, diálogo y registro flexible; sin exámenes estandarizados ni ranking en preescolar. | SEP/UNESCO [I2 §1.4] |
| E5 | **Evaluación sumativa** | Evaluación **del** aprendizaje (calificación final). Fuera de alcance como instrumento principal en 3–6. | Contraste [I2] |
| E6 | **Retroalimentación (feedback)** | Información sobre el desempeño que permite ajustar; dirigida a **estrategia y esfuerzo**, no a "bien/mal" ni a talento fijo. | [I1 §5.1] |
| E7 | **Observación sistemática y registro** | Observar con intención y anotar (frecuencia, disparador, estrategia), no "mirar y recordar". Herramienta central de medición. | [I2 §4.2] |
| E8 | **Taxonomía de Bloom (adaptada a preescolar)** | Recordar/entender (base) + preguntar de orden superior (analizar, evaluar, crear) dosificadas por edad. | NAEYC [I1 §4.2] |
| E9 | **Preguntas de orden superior** | "¿Por qué crees?", "¿qué pasaría si…?", "¿cómo lo sabes?"; los mediadores del pensamiento crítico junto con el diálogo. | O'Reilly 2022 [I1 §4.2] |
| E10 | **Role-play / ensayo con roles** | Practicar conductas (seguridad, conflictos) **actuándolas**. Sin ensayo, el niño no ejecuta el protocolo en la emergencia. | Miltenberger [I1 §6.6] |
| E11 | **Entrenamiento conductual (BST)** | Método: instrucción + demostración + ensayo con roles + corrección y repetición hasta ejecución independiente. **Formato exigido para todo contenido de seguridad.** | Miltenberger 2020 [I1 §4.3] |
| E12 | **Simulacro** | Práctica real de emergencias (incendio, "si me pierdo"). Se hace **repetido y corregido**, no una vez simbólica. | [I1 §6.6] |
| E13 | **Juego libre** | Juego no dirigido por el adulto, prolongado. **Núcleo de la jornada**: construye EF, lenguaje, sociabilidad y agencia. | AAP 2018 [I1 §6.4] |
| E14 | **Juego pretendido / simbólico** | Juego de roles y ficción; entrena inhibición, perspectiva y regulación; asociado con mejor autorregulación. | Slot 2017; Bredikyte 2023 [I1 §6.4] |
| E15 | **Juego de reglas** | Juego con reglas acordadas; enseña que **la regla tiene razón** y a renegociarla (precursores de juicio normativo y pensamiento crítico). | [I1 §6.4] |
| E16 | **Metodologías del Programa Sintético** | Proyectos, aprendizaje basado en problemas, estudio de casos, secuencia didáctica, enseñanza globalizada. El proyecto aplica criterios neuro **dentro** de estas. | [PS; I2 §4.4] |
| E17 | **Instrucción en 1 paso + apoyo visual** | Una instrucción corta acompañada de imagen/objetivo. Reduce carga de memoria de trabajo; estándar para niños neurodivergentes. | [I3 §2.4] |
| E18 | **Secuenciación espiral** | Los contenidos se retoman y complejizan por grado (1°→2°→3°), alineados a la maduración: inhibición → memoria → flexibilidad. | [PS; I2 §4.2] |
| E19 | **Lectura de la realidad** | Primer plano del Programa Analítico: diagnóstico del grupo **añadiendo** sueño, movimiento, alimentación y estrés del hogar. | [I2 §4.2] |
| E20 | **Referente por grado vs. examen** | Los hitos (CDC) y las PDA sirven de **referente** para orientar la observación; jamás como examen ni para diagnosticar. | [I1 §7] |

---

## Bloque F — Neurodiversidad e inclusión

| ID | Término | Definición operativa | Base y uso en el proyecto |
|---|---|---|---|
| F1 | **Neurodiversidad** | Variación natural del cerebro humano; incluye autismo, TDAH, TDL, entre otros, como formas de desarrollo distintas, no como "defecto moral". | Paradigma adoptado [I3 §Convenciones] |
| F2 | **Neurodivergente** | Persona cuyo neurodesarrollo difiere del patrón típico. **No es enfermedad**: su conducta casi siempre es respuesta a un entorno mal ajustado. | [I3] |
| F3 | **Neurotípico** | Persona cuyo desarrollo sigue el patrón estadísticomente típico. Ninguna de las dos categorías es "mejor". | [I3] |
| F4 | **Autismo / TEA** | Perfil de desarrollo con diferencias en comunicación social, preferencia por lo repetible e intereses intensos, y **diferencias sensoriales (≈95% a los 3–6)**. | APA; PMC8430129 [I3 §1.4] |
| F5 | **TDAH** | Perfil con atención/inhibición y regulación emocional labil: frustración por demoras, aburrimiento y búsqueda de estímulo. | [I3 §1.4] |
| F6 | **Trastorno del lenguaje (TDL)** | Dificultad para comprender o producir el lenguaje con la edad esperada; **no poder comunicarse es en sí mismo un generador masivo de frustración**. | [I3 §2.6] |
| F7 | **Trastorno del procesamiento sensorial (TPS)** | Dificultad para modular respuestas a estímulos sensoriales; afecta a ~5–16% de los niños. Se trabaja con terapeuta ocupacional, no con etiquetas. | Raevsky 2025 [I3 §1.4] |
| F8 | **Perfil de evitación de demandas (PDA)** | Perfil descrito con alta sensibilidad a las exigencias; se aborda con lenguaje indirecto, elección y autonomía. **No es diagnóstico** en DSM-5-TR ni CIE-11. | [I3 §2.4] |
| F9 | **Problema de doble empatía** | La incomprensión entre neurotípicos y neurodivergentes es **bidireccional**; la responsabilidad de entenderla es de los dos lados. | Milton 2012 [I3 §5.3] |
| F10 | **Enmascaramiento (camouflaging)** | Ocultar rasgos ND para parecer típico; se asocia con **peor salud mental**. El proyecto no lo exige ni lo premia. | [I3 §5.4] |
| F11 | **Neuroafirmación** | Práctica que respeta la identidad y el estilo ND: permite stimming, intereses intensos, no fuerza mirada/tacto/lenguaje. Postura oficial del proyecto. | [I3 §5.4] |
| F12 | **Comunicación aumentativa y alternativa (CAA) / PECS** | Sistemas (pictogramas, tableros, dispositivos) para comunicarse **sin voz**. Es un **derecho**, no un "último recurso": reduce la frustración. | [I3 §2.6] |
| F13 | **Integración vs. inclusión** | Integración: el niño se adapta al grupo. Inclusión: **el entorno se adapta** al niño. El proyecto practica inclusión. | [I2 §4.2] |
| F14 | **Ajustes razonables** | Modificaciones de entorno, tiempos o materiales que permiten participar sin cambiar el objetivo de aprendizaje. | [I2] |
| F15 | **Cuentos sociales** | Historias breves que anticipan situaciones ("qué pasará en la fiesta") para reducir la incertidumbre. | [I3 §3.1] |
| F16 | **Perfil sensorial (buscador / evitador / mezcla)** | Algunos buscan estímulo (hipo), otros lo evitan (hiper). **La misma conducta puede ser al revés en dos niños**: individualizar siempre. | [I3 §3.3] |
| F17 | **Hiperfoco** | Inmersión intensa en un interés (típico en TDAH y autismo). **Recurso regulador y didáctico**, no "desobediencia a la tarea". | [I3 §3.4] |

---

## Bloque G — NeuroAprendizaje Andragógico (aprendizaje de los adultos)

> *Los sponsors, stakeholders, managers, tutores, profesores y familias son adultos. El contenido crítico del proyecto debe ser discutido y aprendido entre ellos. Este bloque es la base de la formación, la gobernanza y la comunicación del proyecto.*

| ID | Término | Definición operativa | Base y uso en el proyecto |
|---|---|---|---|
| G1 | **NeuroAprendizaje Andragógico / Neuroandragogía** | Rama de la neuroeducación que aplica neurociencia al aprendizaje **del adulto**: cómo cambia el cerebro adulto, qué lo facilita o lo bloquea (estrés, carga cognitiva, motivación) y cómo diseñar formación eficaz para docentes, directivos y familias. | Patil 2022; Routledge cap. 12 [Refs] |
| G2 | **Andragogía** | "El arte y la ciencia de ayudar a los adultos a aprender" (Knowles, 1970). Método propio del adulto, distinto del de los niños. | Knowles 1970 [Ref] |
| G3 | **Pedagogía vs. andragogía** | Pedagogía: el contenido lo define el docente, el alumno depende. Andragogía: el adulto es **autónomo**, parte de su experiencia y aprende para resolver problemas reales. **Un proyecto educativo necesita ambos métodos: pedagogía para los niños, andragogía para los adultos.** | Knowles 1970 [Ref] |
| G4 | **Los 6 principios de Knowles** | (1) Necesita saber **por qué** aprende; (2) es **autodirigido**; (3) aporta **experiencia** de vida; (4) listo para aprender cuando asume un **rol nuevo**; (5) orientado a la **vida y los problemas reales**; (6) motivado **por dentro**. Todo módulo de formación del proyecto debe cumplir los 6. | Knowles; CDC [Ref] |
| G5 | **Aprendizaje autodirigido (SDL)** | ~70% del aprendizaje adulto ocurre fuera del aula formal (Cross 1981): el adulto decide qué, cuándo y cómo. El proyecto facilita recursos, no impone rutas únicas. | Owen 2002 [Ref] |
| G6 | **Andragogía transformacional** | Aprendizaje que cambia el **marco interpretativo** del adulto (revisar creencias profundas), no solo sus técnicas. Aplica a cambiar creencias sobre "niños buenos/malos" o neuromitos. | Mezirow [Ref] |
| G7 | **Aprendizaje experiencial** | Aprender **haciendo y reflexionando**: experiencias, simulaciones, casos. En adultos supera a la charla expositiva. (Ej.: ensayar el protocolo de crisis, no leerlo.) | Kolb [Ref] |
| G8 | **Heutagogía** | Autodirección plena: el profesional **autodetermina** su aprendizaje y desarrolla capacidad, no solo competencia. Continuo de la andragogía; aplica a docentes senior. | Blaschke [Ref] |
| G9 | **Aprendizaje situado / comunidad de práctica** | Se aprende **participando** en la práctica con otros (acompañamiento entre pares, CTE). La formación en el aula vence a la formación en el aula-separada. | Lave & Wenger [Ref] |
| G10 | **Aprendizaje de doble bucle** | Bucle simple: corregir el error. **Doble bucle: revisar la regla o creencia que produjo el error.** Es lo que debe pasar en la retrospectiva del proyecto. | Argyris [Ref] |
| G11 | **Reserva cognitiva** | Capacidad acumulada por aprendizaje y experiencia que amortigua el deterioro; **se sigue construyendo toda la vida**: los adultos del proyecto también aprenden. | Stern; PMC12082096 [Ref] |
| G12 | **Neuroplasticidad en el adulto** | El cerebro adulto **sigue cambiando** por la experiencia (nuevo conocimiento, nueva práctica docente). El mito "los adultos ya no aprenden" es falso. | Chen & Goodwill 2023 [Ref] |
| G13 | **Carga cognitiva** | Cantidad de información que la memoria de trabajo puede manejar a la vez. En formación adulta: pocos conceptos nuevos por sesión, bien estructurados, con aplicación inmediata. | Sweller [I1 §3.4] |
| G14 | **Práctica deliberada** | Práctica enfocada, con retroalimentación y repetición, no "exposición pasiva". Aplica a docentes (ensayar co-regulación) y a niños (role-play). | [I1 §4.3] |
| G15 | **Burnout docente / desgaste por compasión** | Agotamiento emocional por exposición sostenida al sufrimiento ajeno y a la carga laboral. **Riesgo #1 del proyecto para el personal**: se mitiga con apoyo entre pares, rotación y supervisión distribuida. | [PM; I3 §4.3] |
| G16 | **Necesidad de saber el porqué (WIIFM)** | "¿Qué hay para mí?" — si el adulto no entiende el **por qué**, resiste la capacitación. Toda sesión de CTE empieza por el porqué. | Knowles #1 [Ref] |
| G17 | **Motivación del adulto** | Predomina la motivación **interna y de rol** (ser mejor docente/padre) sobre las recompensas externas; las recompensas mal usadas socavan (ver B22). | Knowles; Deci & Ryan [Ref] |
| G18 | **Andamiaje profesional / coaching** | Aplicar B9 a los adultos: acompañamiento en el aula, modelado y retirada progresiva. **La capacitación de un día no cambia práctica**; sí lo hace el acompañamiento. | [PM; I2 §4.4] |
| G19 | **Comunidad de aprendizaje profesional / CTE** | Espacio donde los docentes aprenden **juntos** con datos de su propia práctica (revisión del Analítico, observación entre pares, retrospectiva). Aprendizaje situado + doble bucle. | [PS; I2] |
| G20 | **Formación docente basada en evidencia** | Desarrollo profesional alineado con neurociencia **y** con buenas prácticas de aprendizaje adulto (activo, aplicado, colaborativo). Dubinsky (2019): la formación en neurociencia rinde cuando usa aprendizaje activo. | Dubinsky 2019 [Ref] |
| G21 | **Retroalimentación efectiva para adultos** | Específica, sobre conducta observable, cercana en el tiempo, orientada a estrategia — y en contexto de **seguridad psicológica** (sin humillación). | [I1 §5.1] |
| G22 | **Principio de Consecuencia Adulta (P0)** | *El niño es la consecuencia del resultado de los adultos con los que convive.* Traducción de evidencia (serve and return, co-regulación, Bronfenbrenner) a principio de proyecto: **si el adulto mejora, el niño mejora; si el adulto no se forma, ningún programa infantil escala.** | [I1 §3.2–3.3; I3 §5.6; G-block] |
| G23 | **Autorregulación del adulto** | El adulto regulado es requisito para co-regular: un adulto estresado **aumenta** la agitación infantil. Incluye el cuidado del docente como parte del alcance del proyecto. | FPG UNC [I3 §3.2] |
| G24 | **Carga decisional del adulto / fatiga de decisión** | El exceso de decisiones pequeñas deteriora el juicio del adulto (protocolos y checklists reducen carga). Aplica a directivos y docentes: **decidir menos, con mejores reglas**. | Kahneman [I1 §2.3] |
| G25 | **Seguridad psicológica** | Convicción de que uno puede preguntar, disentir y admitir errores sin castigo. **Condición del CTE y de la retrospectiva**: sin ella, nadie reporta lo que falló y el proyecto no aprende. | Edmondson [PM] |
| G26 | **Compatibilidad pedagógico-andragógica** | Principio de diseño: **los niños aprenden con pedagogía (juego, andamiaje, rutina) y los adultos con andragogía (autonomía, experiencia, problema real)**; usar el método equivocado produce resistencia y fracaso. | [G2–G4] |

---

## Bloque H — Marco curricular (Plan 2022 / NEM / SEP)

| ID | Término | Definición operativa | Base y uso en el proyecto |
|---|---|---|---|
| H1 | **Nueva Escuela Mexicana (NEM)** | Modelo educativo vigente; visión de comunidad, inclusión y contextualización. Marco institucional del proyecto. | [PS] |
| H2 | **Plan de Estudio 2022** | Norma que define campos, ejes y perfil de egreso. **No se modifica**: el proyecto opera dentro de él. | [PS] |
| H3 | **Fases (Fase 1 / Fase 2)** | Fase 1 = Educación Inicial (0–3). **Fase 2 = Educación Preescolar (3–6)**, ámbito de este proyecto. | [PS; I2 §1] |
| H4 | **Campo formativo** | Organizador curricular que sustituye a las asignaturas: **Lenguajes; Saberes y Pensamiento Científico; Ética, Naturaleza y Sociedades; De lo Humano y lo Comunitario** (4). | [PS; I2 §1.2] |
| H5 | **Contenido (34 en Fase 2)** | Disposición de saberes que se complejizan en espiral a lo largo de la fase. Alcance del proyecto. | [PS; I2 §1.2] |
| H6 | **Proceso de desarrollo de aprendizaje (PDA)** | "Ruta posible" por grado (1°, 2°, 3°). Es la columna donde la neuroeducación aporta **lo posible por edad**. | [PS; I2 §1.1] |
| H7 | **Grados 1°/2°/3°** | Ciclo preescolar: 1° = 3–4 años, 2° = 4–5, 3° = 5–6. Secuencia de maduración (E18). | [PS] |
| H8 | **Programa Sintético** | Primer nivel de concreción curricular (documento nacional, SEP 2024): flexible, inacabado, punto de partida. **No se modifica.** | [PS; I2 §1] |
| H9 | **Programa Analítico** | Segundo nivel: documento **anual, por grado y por plantel** resultante del codiseño. Aquí es donde entra la neuroeducación (puntos de autonomía). Entregable central del proyecto. | [I2 §4] |
| H10 | **Niveles de concreción curricular** | Plan (nacional) → Sintético (nacional) → Analítico (escolar) → Planeación didáctica (aula). Jerarquía de decisiones. | [PS; I2 §4.1] |
| H11 | **Contextualización** | Ajuste de los Contenidos al contexto real; tres decisiones: **sin ajustes / contextualizados / nuevos**. Mecanismo formal para incorporar seguridad, regulación y salud. | [I2 §4.2] |
| H12 | **Contenidos nuevos (locales)** | Contenidos que el Sintético no trae pero la comunidad justifica (p. ej. "simulacros: si me pierdo, si hay fuego"). Vía legítima de la neuroeducación. | [I2 §4.2] |
| H13 | **Ejes articuladores** | Vínculo del conocimiento con la realidad (inclusión, pensamiento crítico, interculturalidad crítica, igualdad de género, vida saludable, apropiación de las culturas a través de la lectura y la escritura, artes y experiencias estéticas). | [PS] |
| H14 | **Perfil de egreso** | Descripción de lo que el egresado de la educación básica debe ser y saber; la meta que orienta todas las decisiones. | [PS; I2 §1] |
| H15 | **CTE (Consejo Técnico Escolar)** | Espacio de trabajo colaborativo del personal donde se revisa y actualiza el Programa Analítico. **Aquí ocurre la formación G20 y el filtro anti-neuromitos.** | [PS; I2 §4.2] |
| H16 | **Planeación didáctica** | Tercer nivel: diseño concreto de actividades del aula; aquí se aplican los criterios de los bloques A–F. | [PS; I2 §4.1] |
| H17 | **"El aprendizaje no tiene relación con la edad o los grados" (lectura correcta)** | El programa dice que los Contenidos no se encasillan rígidamente por edad. **Lectura errónea a evitar:** creer que un niño de 3 puede lo que uno de 6. La neuroeducación aporta el matiz: la edad no fija el interés, sí el **techo de lo posible**. | [I2 §3.3] |

---

## Bloque I — Gestión de proyectos (léxico PM del proyecto)

| ID | Término | Definición operativa | Base y uso en el proyecto |
|---|---|---|---|
| I1 | **Acta constitutiva (project charter)** | Documento que autoriza el proyecto: objetivo, alcance, sponsor, riesgos altos, stakeholders. **Este glosario es su insumo previo.** | [PM] |
| I2 | **Interesado (stakeholder)** | Persona o grupo afectado o con influencia: niños, familias, docentes, dirección, sponsors, autoridad educativa. **Todas las decisiones requieren su mapa.** | [PM] |
| I3 | **Alcance** | Qué se entrega y qué **no**. Aquí: 4 Campos, 34 Contenidos, 3 grados, con método neuroeducativo. | [PM] |
| I4 | **Entregable** | Producto verificable (Programa Analítico, protocolos, registros, glosario, acta). | [PM] |
| I5 | **Estructura de desglose de trabajo (WBS)** | Descomposición del proyecto en paquetes manejables (los 8 paquetes del modelo PM). | [PM] |
| I6 | **Hito (milestone)** | Punto de control sin duración ("Analítico cerrado", "piloto iniciado", "línea base capturada"). | [PM] |
| I7 | **Cronograma y ruta crítica** | Secuencia temporal de tareas y la cadena de tareas que **retrasa todo** si se atrasa. | [PM] |
| I8 | **Riesgo y registro de riesgos** | Evento incierto que puede afectar objetivos + probabilidad, impacto y mitigación. Ej.: "formación de 1 día → vuelta a la práctica vieja". | [PM; I2 §6] |
| I9 | **Matriz RACI** | Quién **R**esuelve, **A**prueba, **C**onsulta e **I**nforma. Evita duplicidades y huérfanos. | [PM] |
| I10 | **Sponsor (patrocinador)** | Adulto con autoridad y presupuesto que **protege** el proyecto (tiempo de CTE, acompañamientos). Sin sponsor, el proyecto no escala. | [PM] |
| I11 | **Gobernanza** | Estructura de decisiones: quién aprueba qué, con qué cadencia (comité de seguimiento, CTE, revisión de riesgos). | [PM] |
| I12 | **KPI / indicador** | Medida de éxito acordada (ej.: % de aulas con protocolo practicado, crisis/semana). | [PM] |
| I13 | **Línea base (baseline)** | Medición inicial antes de intervenir. **Sin línea base no hay control de proyecto**: no se puede demostrar mejora. | [PM] |
| I14 | **Control de cambios** | Proceso formal para modificar alcance aprobado; evita que el proyecto crezca sin decisión ("deriva de alcance"). | [PM] |
| I15 | **Trazabilidad** | Capacidad de rastrear cada decisión hasta su fuente (esta es la función de las etiquetas [I1]–[PM]). | Este glosario |
| I16 | **Retrospectiva** | Sesión del equipo para revisar qué funcionó, qué no y qué cambiar. **Aprendizaje de doble bucle (G10) del proyecto.** | [PM] |
| I17 | **Piloto y escalamiento** | Probar primero en un aula o grado, medir, ajustar y luego extender. **Nunca escalar sin datos.** | [PM] |
| I18 | **Criterios de aceptación** | Condiciones explícitas que definen "terminado y correcto" de un entregable (Definition of Done). | [PM] |
| I19 | **Cuadro de mando (dashboard)** | Vista única de KPIs por beneficiario: niños, docentes, familias, plantel. | [PM] |
| I20 | **Beneficiario final vs. usuario** | Beneficiario final: el niño. Usuario: docente/familia. Un proyecto falla si optimiza al usuario a costa del beneficiario (o viceversa). | [PM] |

---

## Bloque J — Neuromitos: términos que NO se usan en el proyecto

*Lista comprometida de lenguaje prohibido. Usar cualquiera de estos términos como argumento pedagógico requiere revisión en CTE.*

| ID | Neuromito | Por qué es falso | Fuente |
|---|---|---|---|
| J1 | **"Estilos de aprendizaje"** (visual/auditivo/kinestésico) | No hay evidencia de que enseñar en el estilo preferido mejore el aprendizaje. **Sí es cierto que todos** aprendemos mejor con información multisensorial y concreta a los 3–6. | Pashler 2008 [I1 §3.5] |
| J2 | **"Cerebro izquierdo / derecho"** (niños "de izquierda" o "de derecha") | Los hemisferios cooperan; no hay tipos cerebrales. | [I1 §3.5] |
| J3 | **"Solo usamos el 10% (o 5%) del cerebro"** | Falso. | [I1 §3.5] |
| J4 | **"La creatividad está en el hemisferio derecho"** | Simplificación comercial; la creación involucra redes distribuidas. | [I1 §3.5] |
| J5 | **Programas comerciales "brain-based" sin evidencia** (p. ej. Brain Gym) | No respaldados por investigación. Todo material "neuro-" pasa el filtro EBP (B19). | [I1 §3.5] |
| J6 | **"Si no se estimula antes de los 3, se pierde la capacidad"** | Falso y dañino: las ventanas tempranas importan, pero el cerebro aprende toda la vida (A9, G12). Mensaje correcto: *las primeras oportunidades son las más eficientes, no las únicas*. | [I1 §3.5] |
| J7 | **"Inteligencias múltiples" como taxonomía diagnóstica o evaluadora** | Gardner es repertorio descriptivo, no teoría validada; no existe consenso para medirlas. | Santarnecchi 2021 [I1 §2.1] |
| J8 | **"Sentarse quieto y en silencio = aprender"** | Contradice la etapa preoperacional y el papel del movimiento en EF. | [I1 §6.4] |
| J9 | **"Más tareas y trabajo académico temprano = más exigencia"** | Exigencia prematura ≠ rigor; produce frustración innecesaria (C15) y choca con el programa. | [I1 §6; I3 §5.1] |
| J10 | **"Castigar fuerte hace que respeten"** | El castigo físico/humillante asocia peores resultados y estrés tóxico. | [I1 §5.4] |
| J11 | **"El niño se porta mal para manipular"** | Atribuir intención en todo ignora cuerpo, sensorio, comunicación y carga (bloque C). | [I3 §1.2] |

---

## Reglas de lenguaje del proyecto ("decimos… no decimos…")

| Decimos | No decimos | Por qué (ID) |
|---|---|---|
| "Conducta comunicativa / el niño nos está diciendo algo" | "Travesura", "manipulación" | C15, J11 |
| "Frustración productiva acompañada" | "Que aprenda a frustrarse" (sin apoyo) | C15 |
| "Rincón de calma / espacio tranquilo" | "Rincón de enfado", "time-out", "esquina del castigo" | C16, C17 |
| "Colapso (meltdown)" | "Rabieta malintencionada" | C6 |
| "Co-regulación" | "Que se calme, ya" | C2 |
| "Referente por grado" | "Examen", "estándar de aprobación" | E20 |
| "Pregunta de orden superior" | "Interrogatorio" | E9 |
| "Ajuste razonable / adaptación" | "Lo especial", "lo de él" | F14 |
| "Comunicación aumentativa (CAA)" | "Cuando ya no quede opción" | F12 |
| "Perfil neurodivergente" | "Discapacidad", "tonto", "retrasado" | F1, F2 |
| "Andragogía" para los adultos | Capacitar a los profes "como a los niños" | G3, G26 |
| "Elogio a estrategia y esfuerzo" | "Eres muy listo" (talento fijo) | B23 |
| "Práctica basada en evidencia" | "Porque lo vi en un video / lo dice el folleto" | B19 |
| "Entrenamiento con role-play" | "Se les explicó una vez" | E10, E11 |

---

## Índice alfabético de términos

| Término | ID | Término | ID |
|---|---|---|---|
| Acta constitutiva | I1 | Juego libre | E13 |
| Ajustes razonables | F14 | Juego pretendido / simbólico | E14 |
| Alcance | I3 | KPI / indicador | I12 |
| Alexitimia | C13 | Lateralización hemisférica | A23 |
| Alta exigencia y alta calidez | D11 | Lectura de la realidad | E19 |
| Ambiente como tercer docente | E2 | Límites claros | D8 |
| Ambiente preparado | E1 | Línea base | I13 |
| Amígdala | A16 | Lo hace para manipular [neuromito] | J11 |
| Andamiaje (scaffolding) | B9 | Los 6 principios de Knowles | G4 |
| Andamiaje profesional / coaching | G18 | Más tareas = más exigencia [neuromito] | J9 |
| Andragogía | G2 | Matriz RACI | I9 |
| Andragogía transformacional | G6 | Memoria de trabajo | A14 |
| Apego | B12 | Metacognición | B21 |
| Apoyo a la autonomía vs. control psicológico | D12 | Metodologías del Programa Sintético | E16 |
| Aprendizaje autodirigido | G5 | Mielinización | A7 |
| Aprendizaje de doble bucle | G10 | Modelado / aprendizaje vicario | B16 |
| Aprendizaje experiencial | G7 | Modelo médico vs. modelo social de la discapacidad | B18 |
| Aprendizaje situado / comunidad de práctica | G9 | Monotropismo | C12 |
| Arquitectura cerebral | A8 | Motivación del adulto | G17 |
| Autismo / TEA | F4 | Motivación intrínseca / extrínseca y efecto de sobrejustificación | B22 |
| Autorregulación | C1 | Necesidad de saber el porqué (WIIFM) | G16 |
| Autorregulación del adulto | G23 | Neuroafirmación | F11 |
| Base segura | B13 | NeuroAprendizaje Andragógico / Neuroandragogía | G1 |
| Beneficiario final vs. usuario | I20 | Neurodivergente | F2 |
| Burnout docente / desgaste por compasión | G15 | Neurodiversidad | F1 |
| Cadena de la crisis (rumbling→rage→recovery) | C8 | Neuroeducación | A1 |
| Campo formativo | H4 | Neurona | A3 |
| Carga cognitiva (adulto) | G13 | Neuropaidagogía | A2 |
| Carga decisional del adulto | G24 | Neuroplasticidad (adulto) | G12 |
| Castigar fuerte hace que respeten [neuromito] | J10 | Neuroplasticidad (niño) | A9 |
| Cerebro izquierdo/derecho [neuromito] | J2 | Neurotípico | F3 |
| Cierre (shutdown) | C7 | Neurotransmisores | A22 |
| Co-regulación | C2 | Niveles de concreción curricular | H10 |
| Cognitivismo | B14 | Nueva Escuela Mexicana (NEM) | H1 |
| Colapso (meltdown) | C6 | Observación sistemática y registro | E7 |
| Compatibilidad pedagógico-andragógica | G26 | Orientación a dominio vs. rendimiento | B23 |
| Comunicación aumentativa (CAA) / PECS | F12 | Pedagogía vs. andragogía | G3 |
| Comunidad de aprendizaje profesional / CTE | G19 | Pensamiento crítico | B20 |
| Conductismo / behaviorismo | B15 | Pensamiento crítico: adulto vs. infantil | B27 |
| Conservación | B6 | Pensamiento simbólico / función simbólica | B4 |
| Constructivismo | B1 | Perfil de egreso | H14 |
| Contenido (34 en Fase 2) | H5 | Perfil de evitación de demandas | F8 |
| Contenidos nuevos | H12 | Perfil sensorial | F16 |
| Contextualización | H11 | Periodo sensible / ventana crítica | A10 |
| Control de cambios | I14 | Piloto y escalamiento | I17 |
| Corteza prefrontal | A11 | Plan de Estudio 2022 | H2 |
| Creatividad = hemisferio derecho [neuromito] | J4 | Planeación didáctica | H16 |
| Creencias falsas | B11 | Poda sináptica | A6 |
| Criterios de aceptación | I18 | Práctica apropiada al desarrollo (DAP) | E3 |
| Cronograma y ruta crítica | I7 | Práctica basada en evidencia (EBP) | B19 |
| CTE (Consejo Técnico Escolar) | H15 | Práctica deliberada | G14 |
| Cuadro de mando | I19 | Preguntas de orden superior | E9 |
| Cuentos sociales | F15 | Principio de Consecuencia Adulta (P0) | G22 |
| Deuda sensorial / fatiga de desregulación | C18 | Principio de no daño | B26 |
| Ecosistemas del desarrollo | B17 | Problema de doble empatía | F9 |
| Edad y aprendizaje (lectura correcta) | H17 | Proceso de desarrollo de aprendizaje (PDA) | H6 |
| Egocentrismo | B5 | Programa Analítico | H9 |
| Eje HHA | A17 | Programa Sintético | H8 |
| Ejes articuladores | H13 | Programas brain-based sin evidencia [neuromito] | J5 |
| Empatía vs. simpatía | D6 | Protocolo de crisis | C19 |
| Enmascaramiento (camouflaging) | F10 | Rabieta (tantrum) | C5 |
| Entregable | I4 | Referente por grado vs. examen | E20 |
| Entrenamiento conductual (BST) | E11 | Regulación / desregulación emocional | C3 |
| Esquema, asimilación, acomodación, equilibración | B2 | Reparación vs. castigo | D7 |
| Estado de activación | A20 | Reserva cognitiva | G11 |
| Estilo autoritario | D2 | Resiliencia | C14 |
| Estilo autoritativo | D1 | Respuesta contingente | D10 |
| Estilo negligente | D4 | Retroalimentación (feedback) | E6 |
| Estilo permisivo | D3 | Retroalimentación efectiva para adultos | G21 |
| Estilos de aprendizaje [neuromito] | J1 | Retrospectiva | I16 |
| Estimulación reguladora (stimming) | C11 | Riesgo y registro de riesgos | I8 |
| Estrés tóxico / tolerable / positivo | A18 | Rincón de calma / espacio tranquilo | C16 |
| Estructura de desglose de trabajo (WBS) | I5 | Role-play / ensayo con roles | E10 |
| Etapa preoperacional | B3 | Secuenciación espiral | E18 |
| Evaluación formativa | E4 | Seguridad psicológica | G25 |
| Evaluación sumativa | E5 | Sensibilidad/responsividad del cuidador | D9 |
| Fases (Fase 1 / Fase 2) | H3 | Sentarse quieto = aprender [neuromito] | J8 |
| Flexibilidad cognitiva | A15 | Serve and return (servir y devolver) | A19 |
| Formación docente basada en evidencia | G20 | Simulacro | E12 |
| Frustración innecesaria vs. productiva | C15 | Sinapsis | A4 |
| Funciones ejecutivas | A12 | Sinaptogénesis | A5 |
| Gobernanza | I11 | Sobrecarga sensorial | C9 |
| Grados 1°/2°/3° | H7 | Socioculturalismo | B7 |
| Heutagogía | G8 | Sponsor (patrocinador) | I10 |
| Hiperfoco | F17 | Taxonomía de Bloom (adaptada) | E8 |
| Hiperreactividad / hiporreactividad sensorial | C10 | TDAH | F5 |
| Hito (milestone) | I6 | Teoría de la mente | B10 |
| Inhibición de respuesta | A13 | Time-out / estancamiento | C17 |
| Instrucción en 1 paso + apoyo visual | E17 | Trastorno del lenguaje | F6 |
| Integración vs. inclusión | F13 | Trastorno del procesamiento sensorial | F7 |
| Inteligencia emocional | B25 | Trazabilidad | I15 |
| Inteligencias múltiples | B24 | Usamos solo 10% del cerebro [neuromito] | J3 |
| Inteligencias múltiples como diagnóstico [neuromito] | J7 | Validación emocional | D5 |
| Intercepción conductual | C20 | Ventana crítica extrema a los 3 años [neuromito] | J6 |
| Interesado | I2 | Ventana de tolerancia | C4 |
| Interocepción / exterocepción | A21 | Zona de desarrollo próximo (ZDP) | B8 |
| Juego de reglas | E15 | | |

---

## Referencias

### Serie documental del proyecto
1. `neuroeducacion-preescolar-3-6-informe.md` — fundamentos de neuroeducación 3–6 [I1].
2. `analisis-programa-sintetico-integracion-neuroeducacion.md` — integración con el Programa Sintético Fase 2 [I2].
3. `estres-crisis-calma-y-entornos-seguros-3-6.md` — estrés, crisis, calma y entornos [I3].
4. SEP (2024). *Programa de Estudio para la Educación Preescolar: Programa Sintético de la Fase 2* [PS].

### Andragogía y aprendizaje del adulto (Bloque G)
5. Knowles, M. S. (1970). *The Modern Practice of Adult Education; Andragogy versus Pedagogy*. Association Press.
6. Knowles, M. S. et al. (1984). *Andragogy in Action*. Jossey-Bass.
7. CDC / Head Start (2020). *Adult Learning Principles* (6 principios de Knowles). https://www.cdc.gov/training-development/media/pdfs/2024/04/adult-learning-principles.pdf
8. Clardy, A. (2005). *Andragogy: Adult Learning and Education at Its Best?* ERIC ED492132 (crítica: evidencia empírica inconcluyente; usar andragogía como marco práctico, no como ley cerrada).
9. Owen, T. R. (2002). *Self-Directed Learning in Adulthood: A Literature Review*. ERIC ED461050.
10. Patil, M. R. (2022). *Neuroscience of Adult Learning – Neuroandragogy*. Zenodo. doi:10.5281/zenodo.7801700
11. *The Adult Learner* (10.ª ed.), Cap. 12: *Neuroscience and andragogy*. Routledge Learning. https://routledgelearning.com/theadultlearner/student-guide/chapter-12-neuroscience-and-andragogy
12. Low, K. et al. (2014). *Teaching adults—best practices that leverage the emerging understanding of the neurobiology of learning*. PMID 24981663.
13. Dubinsky, J. M. (2019). *Contributions of Neuroscience Knowledge to Teachers and Their Practice*. PMID 30895863.
14. Chen, S. H. A. & Goodwill, A. M. (2023). Neuroplasticity and Adult Learning. En *Third International Handbook of Lifelong Learning*. Springer. doi:10.1007/978-3-031-19592-1_43
15. *The Impact of Later-Life Learning on Trajectories of Cognitive Function* (2025). PMC12082096 (reserva cognitiva y aprendizaje tardío).
16. EPALE (UE). *Neuromyths and adult learning*.

### Bases de los bloques A–F, H–J
17. Fuentes completas de los bloques A–F y J: ver referencias de [I1], [I2] e [I3] (Diamond 2013; NAEYC 2020; OCDE 2019; Facione 1990; AAP/Yogman 2018; Harvard Center on the Developing Child; CDC milestones; Wellman et al. 2001; O'Reilly et al. 2022; Miltenberger et al. 2020; Baumrind; Vygotsky; Piaget; Montessori; Milton 2012; Bradshaw et al. 2025; Pashler et al. 2008; Dekker et al. 2012; Knowles; Raevsky et al. 2025; Myles & Southwick).

---

*Regla de mantenimiento: todo término nuevo del proyecto se agrega a este glosario con su ID, definición y trazabilidad **antes** de aparecer en el Acta Constitutiva. Versión controlada; cambios por CTE.*

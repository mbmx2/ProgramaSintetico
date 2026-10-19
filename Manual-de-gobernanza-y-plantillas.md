---
title: "Manual de gobernanza y catálogo completo de plantillas"
subtitle: "Inventario de gobernanza, plataformas FOSS y 24 plantillas del ciclo de vida"
author: "Serie de Neuroeducación · Proyecto Programa Sintético"
date: "Tercera edición de lectura · 29 de septiembre de 2026"
---

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

```{=openxml}
<w:p><w:pPr><w:jc w:val="center"/><w:spacing w:before="120" w:after="300"/></w:pPr><w:r><w:rPr><w:rFonts w:ascii="Georgia" w:hAnsi="Georgia"/><w:b/><w:color w:val="1F4E79"/><w:sz w:val="32"/><w:szCs w:val="32"/></w:rPr><w:t>Índice</w:t></w:r></w:p>

```{=openxml}
<w:p><w:r><w:fldChar w:fldCharType="begin"/></w:r><w:r><w:instrText xml:space="preserve"> TOC \o "1-2" \h \z \u </w:instrText></w:r><w:r><w:fldChar w:fldCharType="separate"/></w:r><w:r><w:rPr><w:i/><w:color w:val="777777"/></w:rPr><w:t>Índice automático — en Word se actualiza al abrir; en LibreOffice: Herramientas ▸ Actualizar ▸ Índice (F9)</w:t></w:r><w:r><w:fldChar w:fldCharType="end"/></w:r></w:p>

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Inventario de gobernanza en ingeniería

## Artefactos, dispositivos y herramientas para ejercer la gobernanza en cualquier tipo de proyecto

*Capa Ingeniería de la Educación · v0.1 · 29 de septiembre de 2026*
*Derivado de: `glosario-ingenieria-general.md` (IG), `glosario-ingenieria-de-la-educacion.md` (IE), `Plantillas/` (A1–A8, S1, D1, N1, T1), el Acta Constitutiva y el sistema de tandas del proyecto*

---

## 0. Qué es gobernanza, dicho sin abstractos

Gobernanza es la respuesta ordenada a cinco preguntas que todo proyecto se hace, quiera o no: **¿quién decide? ¿con qué información? ¿con qué reglas? ¿cómo sabemos que se cumple? y ¿a quién rinde cuentas?** Un equipo puede tener el mejor talento del mundo y naufragar si estas cinco preguntas se responden por costumbre. Y un equipo modesto puede llegar lejos si las responde por escrito.

Este inventario reúne **todo lo que sirve para ejercerla** en ingeniería de cualquier tipo —software, educación, organización de un taller, un emprendimiento, un proyecto personal— y lo presenta en tres familias que conviene distinguir, porque se confunden todo el tiempo:

**Artefactos**: los documentos que se redactan, firman y guardan. Son la **memoria** de la gobernanza: si desaparecen, no hay forma de probar lo que se decidió.

**Dispositivos**: los mecanismos que trabajan **solos** una vez instalados. Una puerta que no se abre sin condiciones, un semáforo que obliga a responder, un ciclo que vuelve aunque nadie tenga ganas. Son la **columna vertebral**: no dependen del ánimo del día.

**Herramientas**: las técnicas que empuja tu mano en una reunión o una sesión. El FODA, los cinco porqués, la retrospectiva. Son el **oficio**: no guardan nada por sí solas, producen lo que después se guarda en un artefacto.

La gobernanza sana necesita las tres: documentos sin mecanismos son burocracia viva; mecanismos sin herramientas se instalan vacíos; herramientas sin documentos se olvidan en la próxima rotación. Cada entrada de este inventario lleva su código **GOB** para citar sin ambigüedad, su momento de uso y **dónde vive en este proyecto** (plantilla, Acta o compendio), de modo que puedas copiar el sistema y no sólo la idea.

---

## 1. Artefactos de gobernanza (los documentos que se firman y guardan)

**GOB1 · Acta constitutiva (carta del proyecto).** El documento que autoriza, acota y firma el proyecto: alcance, gobernanza, políticas, métricas y vigencia. *Cuándo:* al inicio, antes de ejecutar; se mantiene con enmiendas registradas. *Evita:* que el proyecto dependa de la voluntad informal de una persona. *Aquí vive:* `Acta Constitutiva/…` (29 artículos; entrada en vigor condicionada a su puerta G1).

**GOB2 · Encuadre y alcance declarado.** Problema real, meta comprobable, dentro y fuera de alcance y partes interesadas, en una página. *Cuándo:* el día cero, antes de diseñar. *Evita:* la deriva de alcance y el "creía que ibas a…". *Aquí vive:* plantilla `A1-encuadre-y-alcance.md`.

**GOB3 · Especificación de requisitos.** Lista de condiciones comprobables con su fuente (norma, evidencia, usuario, contexto) y su criterio de aceptación. *Cuándo:* después del encuadre y antes del diseño; se revisa en cada cambio mayor. *Evita:* "mejorar la calidad" y las discusiones eternas de "quedó". *Aquí vive:* plantilla `A2-requisitos.md`.

**GOB4 · Plan y desglose de trabajo (WBS).** Las piezas del proyecto, sus dependencias, los roles (RACI), los supuestos escritos y las puertas de avance. *Cuándo:* al aprobar el diseño. *Evita:* que el plan viva en la cabeza de una sola persona. *Aquí vive:* plantilla `A3-diseno-y-plan.md`.

**GOB5 · Matriz RACI.** Quién resuelve, quién aprueba, quién consulta y quién se entera —para cada rol o entregable. *Cuándo:* al inicio del diseño; se reevalúa cuando entra o sale gente. *Evita:* "creía que lo hacías tú", el hueco de responsabilidad más caro de los equipos. *Aquí vive:* A3 (el formato) y Acta art. 13 (los roles del proyecto).

**GOB6 · ADR (registro de decisión).** Decisiones estructurales con contexto, alternativas descartadas, consecuencias y condiciones de revisión. *Cuándo:* cuando la decisión es cara de dar marcha atrás. *Evita:* la costumbre injustificable y la "buena idea" que reaparece sin historia. *Aquí vive:* plantilla `A8-adr-registro-decision.md`; en este proyecto, `adr-modelo-construccion…`.

**GOB7 · Políticas de protección.** Las reglas no negociables por escrito: no daño, tratamiento de datos (minimización, consentimiento, revocabilidad), uso de inteligencia artificial, imagen y voz de personas. *Cuándo:* antes de cualquier contacto con personas o datos reales. *Evita:* el daño irreversible (los datos de la infancia no se borran). *Aquí vive:* Acta arts. 6–7 y política de IA (ADR AD-5).

**GOB8 · Código de conducta y compromiso de trato.** Lo que se espera del comportamiento entre miembros y hacia beneficiarios: respeto, cero humillación, canales de reporte. *Cuándo:* con la firma del proyecto o del equipo. *Evita:* que la convivencia dependa del carácter de los presentes. *Aquí vive:* en el Acta, implícito en sus artículos de deberes (6 y 9) — candidato explícito para formalizar en una enmienda.

**GOB9 · Registro de decisiones (bitácora).** La lista cronológica de decisiones: qué, cuándo, quién, por qué. *Cuándo:* continuo — toda decisión relevante, no sólo las grandes. *Evita:* "sin registro no ocurrió" —la frase más honesta del Acta (art. 13). *Aquí vive:* junto a los ADR, con fecha relativa y responsable.

**GOB10 · Actas de reunión con acuerdos.** El resumen mínimo de cada sesión de gobernanza: asistencia, decisiones, acuerdos con responsable y fecha. *Cuándo:* cada reunión formal. *Evita:* la reunión sin decisión (antipatrón N2 de `neurogestion…`). *Aquí vive:* formato heredado de las sesiones de CTE (Formación y práctica del proyecto).

**GOB11 · Registro de riesgos.** Riesgos con probabilidad, impacto, mitigación y disparador; revisado en ciclo. *Cuándo:* se abre en el encuadre y se revisa cada fase. *Evita:* vivir apagando incendios. *Aquí vive:* plantilla `A5-riesgos-y-cambios.md`.

**GOB12 · Historial de cambios y versiones.** Qué versión está vigente, qué cambió, bajo qué autorización. *Cuándo:* continuo (control de cambios). *Evita:* el "final-final" y la pérdida de confianza en los documentos. *Aquí vive:* sistema de tandas (Primera/Segunda/Tercera) y control de cambios del Acta (art. 14).

**GOB13 · Criterios de aceptación y DoD.** Las condiciones explícitas de "terminado y correcto", por entregable y por fase. *Cuándo:* se definen antes de construir y se exigen antes de avanzar. *Evita:* "creemos que quedó" como cierre de fase. *Aquí vive:* plantillas A2 y A4; puerta G1 con su DoD.

**GOB14 · Línea base y tablero de indicadores.** La medición del punto de partida y el panel de métricas con meta, estado y responsable. *Cuándo:* línea base al inicio de cada intervención; tablero en cada revisión. *Evita:* opinar sin medir y decorar con números (métrica sin lectura). *Aquí vive:* plantilla `A4-verificacion-y-validacion.md`; semáforo del Acta art. 20.

**GOB15 · Informes de ciclo (legal, científico, de impacto).** Los informes que, en cada ciclo, dicen qué cambió en el entorno, qué documento afecta y qué acción se abre. *Cuándo:* semestral (ley), anual (evidencia), trienal (impacto completo). *Evita:* envejecer sin notarlo. *Aquí vive:* Acta art. 23; `Roadmap-deca-10-anios-actualizaciones.md`.

**GOB16 · Consentimiento informado.** El permiso específico, explicado, escrito y revocable de las familias o participantes para usos de datos, imagen o participación. *Cuándo:* antes de capturar cualquier dato o imagen. *Evita:* la legitimidad perdida con un solo uso indebido. *Aquí vive:* Acta arts. 7 y 26; plantilla N1 (casilla de consentimiento).

**GOB17 · Lecciones aprendidas y retrospectiva documentada.** El registro de qué pasó, por qué y qué cambiamos. *Cuándo:* al cierre de cada fase o ciclo. *Evita:* repetir el error con entusiasmo renovado. *Aquí vive:* plantilla `A6-retrospectiva-y-mejora.md`.

**GOB18 · Catálogo de patrones y antipatrones.** Las fichas de soluciones y errores recurrentes con nombre propio. *Cuándo:* continuo; se nutre en cada retrospectiva. *Evita:* que lo aprendido se pierda con quien se va. *Aquí vive:* plantilla `A7-registro-de-patrones.md`; en este proyecto, `neurogestion-patrones-y-antipatrones.md`.

**GOB19 · Acuerdos con terceros.** Convenios y compromisos con proveedores, colaboradores, familias o autoridades: qué se espera de cada parte y cómo se resuelve un desacuerdo. *Cuándo:* antes de que un tercero toque el proyecto o a sus beneficiarios. *Evita:* dependencias verbales y visitas sin reglas. *Aquí vive:* reglas de visitantes y nodos (Acta art. 17).

**GOB20 · Manual de inducción y transferencia.** El documento con el que alguien nuevo puede operar el proyecto sin el fundador: roles, procesos, decisiones, contactos. *Cuándo:* desde el día uno, actualizado con cada cambio mayor. *Evita:* que el proyecto muera con su fundador (herencia y transferencia, IE39). *Aquí vive:* el README de convención + la serie, como onboarding vivo.

**GOB21 · Mapa de partes interesadas.** Quién es, qué le importa, cuánto influye y cómo se le informa o consulta. *Cuándo:* al encuadre; se actualiza con cada cambio de actores. *Evita:* el descubrimiento tardío de quien tenía derecho a opinar. *Aquí vive:* plantilla A1 (sección de partes interesadas).

**GOB22 · Presupuesto y autorizaciones de gasto.** Lo disponible, lo comprometido y quién autoriza cada erogación. *Cuándo:* al aprobar alcance; se revisa por fase. *Evita:* que el dinero se gaste "porque ya empezamos" y el proyecto se muera a media obra. *Aquí vive:* fuera de alcance declarado del Acta actual (art. 11) — es un pendiente explícito a cubrir al formalizar.

---

## 2. Dispositivos de gobernanza (los mecanismos que trabajan solos)

**GOB23 · Puerta de calidad (gate).** El punto que no se cruza sin cumplir condiciones verificadas. *Cómo trabaja solo:* aunque todos tengan prisa, la puerta no se abre; el avance exige evidencia. *Evita:* que la velocidad se coma a la calidad. *Aquí vive:* plantillas A3 y A4 (sección de puertas); en el proyecto, la Puerta G1.

**GOB24 · Condición de entrada en vigor.** La cláusula que dice cuándo el Acta o el acuerdo deja de ser borrador: sólo con firmas y condiciones cumplidas. *Cómo trabaja solo:* nadie puede "dar por vigente" lo que no está firmado. *Evita:* la solemnidad prematura. *Aquí vive:* Acta art. 27 (DoD de G1).

**GOB25 · Escalera de decisión.** La regla que asigna niveles: lo operativo lo decide quien ejecuta; lo de alcance o política, el sponsor con el equipo; lo estructural, el Acta y su control de cambios. *Cómo trabaja solo:* nadie escala decisiones por orgullo ni se queda corto por miedo. *Evita:* el cuello de botella del "pregúntale al jefe" y la improvisación de quien no debería decidir. *Aquí vive:* Acta art. 14 (menores: coordinador; mayores: sponsor con CTE).

**GOB26 · Semáforo de salud.** Verde, ámbar, rojo con respuesta obligatoria por estado. *Cómo trabaja solo:* el rojo activa escalamiento sin que nadie tenga que atreverse a hablar. *Evita:* el dato que se mira y no se toca. *Aquí vive:* Acta art. 20.

**GOB27 · Escalamiento por umbral.** Regla automática: si el indicador cae dos ciclos seguidos, o hay un incidente grave, se sube de nivel de atención inmediatamente. *Cómo trabaja solo:* no depende de que alguien "se atreva" a avisar. *Evita:* el problema que se calla hasta que es notorio. *Aquí vive:* Acta art. 20 (estado rojo) y disparadores del art. 23.

**GOB28 · Cadencia de gobernanza.** El ritmo fijo de reuniones y revisiones: semanal para lo operativo, quincenal para lo de diseño, por ciclo para lo de dirección. *Cómo trabaja solo:* lo pendiente encuentra su foro sin depender de la iniciativa del día. *Evita:* que las decisiones esperen "el momento oportuno" (que nunca llega). *Aquí vive:* Acta art. 13 (cadencias del CTE); roadmap F0–F3.

**GOB29 · Ciclos de actualización.** Revisión legal semestral, científica anual y mayor trienal, con disparadores extraordinarios. *Cómo trabaja solo:* el calendario obliga a mirar el entorno aunque no haya crisis. *Evita:* la obsolescencia silenciosa de la norma y de la evidencia. *Aquí vive:* Acta arts. 22–23; roadmap de la década.

**GOB30 · Sistema de versiones y tandas.** Toda capa mayor se archiva inmutable antes de empezar la siguiente; todo documento vigente lleva versión y fecha. *Cómo trabaja solo:* el pasado se vuelve inaccesible al olvido —y auditable. *Evita:* que "cómo estaba antes" dependa de la memoria. *Aquí vive:* README de convención; Acta art. 24.

**GOB31 · Pipeline de generación de documentos.** El proceso estandarizado que convierte fuentes vivas (Markdown) en entregas consistentes (DOCX con portada, índice y foliado). *Cómo trabaja solo:* regenera formatos sin repetir trabajo manual ni divergencias de estilo. *Evita:* la deriva visual y la pérdida de tiempo en formato. *Aquí vive:* el pipeline de la serie (reconstruible según el Acta art. 24).

**GOB32 · Ventana de congelación de cambios.** Periodos en los que no se aprueban cambios de alcance (por ejemplo, en la última semana de una fase o durante un piloto). *Cómo trabaja solo:* protege el foco sin negociación diaria. *Evita:* que el piloto muera de "una idea más". *Aquí vive:* convención implícita del método piloto→puerta; candidata a formalizarse en control de cambios.

**GOB33 · Revisión por pares obligatoria.** Ningún artefacto de impacto sale sin una segunda mirada registrada. *Cómo trabaja solo:* el "listo" requiere dos firmas de lectura, no una. *Evita:* el sesgo de quien está demasiado cerca del texto. *Aquí vive:* revisión humana de la Puerta G1; revisión trienal con pares externos (Acta art. 23).

**GOB34 · Redundancia de roles (suplentes).** Cada rol crítico tiene persona suplente documentada y su inducción al día. *Cómo trabaja solo:* la ausencia de una persona no detiene el sistema. *Evita:* el héroe insustituible (antipatrón N1). *Aquí vive:* SOACH FA-3; Acta art. 13.

**GOB35 · Registro como condición.** La regla de que "sin registro no ocurrió": nada cuenta si no está escrito con fecha y responsable. *Cómo trabaja solo:* cambia la conducta del equipo sin sermones. *Evita:* la memoria generosa y las conversaciones que "se acordaron". *Aquí vive:* Acta art. 13 (cierre).

---

## 3. Herramientas de gobernanza (las técnicas que empuja tu mano)

**GOB36 · FODA y SOACH.** Diagnóstico de fuerzas y debilidades, y su cruce en estrategias con acción, responsable y métrica. *Cuándo:* al encuadre y en revisiones de ciclo. *Evita:* que la estrategia sea intuición sin palancas. *Aquí vive:* `foda-programa…` y `soach-estrategias…` del proyecto.

**GOB37 · Mapa de partes interesadas en taller.** La sesión en que se dibuja quién es, qué le importa y cómo participa —con el equipo, no solo en el escritorio. *Cuándo:* al inicio y ante cambios grandes. *Evita:* diseños que ignoran a quien afectan. *Aquí vive:* artefacto GOB21; herramienta de su elaboración.

**GOB38 · Los cinco porqués (causa raíz).** Preguntar consecutivamente "¿y por qué?" hasta llegar a algo accionable. *Cuándo:* ante un fallo que se repite. *Evita:* corregir síntomas y programar el mismo problema para el miércoles. *Aquí vive:* plantilla A6 (sección de causa raíz).

**GOB39 · Retrospectiva facilitada.** La reunión de tres preguntas —qué mantenemos, qué cambiamos, qué sorprendió— con datos sobre la mesa y sin culpables. *Cuándo:* al cierre de cada fase, sprint o ciclo. *Evita:* el silencio educado y la opinión sin evidencia. *Aquí vive:* plantilla `A6-retrospectiva-y-mejora.md`.

**GOB40 · Preguntas de doble bucle.** La pregunta de segundo nivel: ¿la regla que nos trajo aquí sigue vigente? *Cuándo:* cuando las mejoras de primer nivel ya no bastan. *Evita:* perfeccionar el procedimiento equivocado. *Aquí vive:* plantilla A6 (casilla de doble bucle); Acta art. 14.

**GOB41 · Priorización por impacto y esfuerzo.** La matriz simple para decidir qué entra primero: alto impacto y bajo esfuerzo adelanta. *Cuándo:* al planificar fases o elegir entre pedidos. *Evita:* que gane el pedido más ruidoso. *Aquí vive:* criterio de escalamiento del roadmap (F5) y control de cambios.

**GOB42 · Timeboxing (presupuesto de tiempo).** Asignar un tiempo máximo a deliberar y decidir; al vencer, se cierra con lo mejor disponible y se registra. *Cuándo:* en decisiones de bajo riesgo. *Evita:* la deliberación infinita, que es estrés sin recompensa. *Aquí vive:* práctica de cierre en las sesiones del curso (M1–M8).

**GOB43 · Check-in corto de estado.** La ronda breve de apertura: qué hago, qué bloquea, de qué ayuda. *Cuándo:* reuniones operativas. *Evita:* que los bloqueos se escondan hasta el informe final. *Aquí vive:* práctica de apertura de las sesiones de trabajo del proyecto.

**GOB44 · Tablero visual de trabajo.** El espacio (físico o digital) donde las tareas se ven: por hacer, en curso, bloqueada, hecha. *Cuándo:* siempre, para trabajo con más de una persona. *Evita:* que el estado real dependa de recordatorios individuales. *Aquí vive:* complemento natural del WBS (GOB4) y del acta de reunión (GOB10).

**GOB45 · Auditoría interna con checklist.** La autoinspección periódica contra criterios escritos (calidad, ética, cumplimiento). *Cuándo:* antes de puertas y en revisiones. *Evita:* descubrir el incumplimiento el día de la entrega. *Aquí vive:* checklist de materiales, filtro anti-neuromitos (glosario neuro, bloque J) y auditoría de la Puerta G1.

**GOB46 · Escucha estructurada a partes (entrevista con guion).** Preguntar con guion y registrar, antes de decidir: a usuarios, familias, equipo. *Cuándo:* en levantamiento de requisitos y en validación. *Evita:* diseñar con supuestos no verificados. *Aquí vive:* plantillas A2 (fuentes) y A4 (validación con usuarios).

**GOB47 · Guion de negociación de alcance.** Cuando llega un "¿y si agregamos…?", la respuesta guionada: "sí es posible; requiere cambiar X o Y; lo decidimos con control de cambios". *Cuándo:* ante cada petición post-firma. *Evita:* el sí tonto que deriva el proyecto. *Aquí vive:* plantilla A5 (sección de control de cambios).

**GOB48 · Demostración de estado (demo).** Mostrar el avance real, en uso, ante el equipo o el beneficiario. *Cuándo:* al cierre de iteraciones. *Evita:* que "avanzado" signifique "presentación bonita". *Aquí vive:* DoD de la iteración en la plantilla D1 (demo con usuario o datos).

**GOB49 · Contraloría de uno (autoinspección con preguntas guía).** El hábito personal de revisar la propia decisión con las preguntas del sistema: ¿mi fuente? ¿mi supuesto? ¿mi alcance? *Cuándo:* antes de cada decisión relevante. *Evita:* que la confianza sustituya al criterio. *Aquí vive:* el espíritu de las reglas de uso de axiomas y de neuroepistemología (`neuroepistemologia-compendio.md`).

**GOB50 · Reunión de decisión (no de información).** Formato: una sola pregunta de decisión, contexto mínimo, alternativas, cierre con responsable y fecha. *Cuándo:* cuando hay que decidir, no cuando hay que informar. *Evita:* la reunión sin decisión (antipatrón N2). *Aquí vive:* Acta art. 13 y actas GOB10.

---

## 4. Kit mínimo de gobernanza según el tamaño del proyecto

**Si trabajas solo** (proyecto personal, estudio — plantilla S1): encuadre (GOB2), requisitos con criterio (GOB3), registro de decisiones mínimo (GOB9), presupuesto de tiempo (GOB42) y retrospectiva mensual (GOB39). Cinco cosas bastan para no perderte.

**Si son de 2 a 8 personas** (equipo pequeño, taller, emprendimiento): suma **Acta breve** (GOB1 versión corta: alcance, roles RACI, políticas de datos y trato), riesgos (GOB11), cadencia de reuniones (GOB28), tablero (GOB44) y actas con acuerdos (GOB10). Y una puerta simple: nada avanza sin su DoD (GOB13).

**Si es una organización o programa** (escuela, plataforma, red): añade formalidad —ciclos de actualización (GOB29), versionado con tandas (GOB30), informes de ciclo (GOB15), redundancia de roles (GOB34), consentimientos y políticas de datos (GOB7, GOB16), revisión por pares (GOB33) y presupuesto con autorizaciones (GOB22).

**Regla de progresión**: nunca se salta de "solo" a "organización" de golpe; cada nivel agrega dispositivos **una vez que los anteriores ya operan solos**. Un Acta sin cadencia es papel; una cadencia sin registro es rutina vacía.

---

## 5. Señales de gobernanza enferma (para reconocerlas a tiempo)

Diez síntomas y su antídoto directo: **Se deciden cosas en pasillos** → escalera de decisión y actas (GOB25, GOB10). **Todo es urgente** → priorización (GOB41) y ventanas de congelación (GOB32). **Nadie sabe qué versión es la buena** → versionado (GOB12, GOB30). **Las métricas no se leen** → semáforo con acción obligatoria (GOB26). **Las reuniones no cierran acuerdos** → reunión de decisión (GOB50). **Se firma sin condiciones** → puertas y entrada en vigor (GOB23, GOB24). **Un solo irremplazable** → redundancia de roles (GOB34). **El error se oculta** → retrospectiva sin culpables (GOB39, GOB38). **Los cambios entran por la ventana** → control de cambios con guion (GOB12, GOB47). **La norma cambió y nadie lo sabe** → ciclos de actualización (GOB29).

---

## 6. Cómo ejercerla: seis prácticas de arranque

**Primera:** escribe hoy mismo un encuadre de una página de cualquier proyecto que estés llevando (GOB2). Si no puedes llenar "fuera de alcance", no empieces. **Segunda:** pon un RACI de cinco renglones donde cada tarea tenga dueño (GOB5) — verás desaparecer la mitad de los malentendidos. **Tercera:** instala una cadencia: una reunión corta semanal con acta de acuerdos (GOB28, GOB10). **Cuarta:** define un DoD por fase antes de que empiece (GOB13); sin él, "terminado" es poesía. **Quinta:** ten un registro de decisiones aunque sea de una columna (GOB9) — tu yo de dentro de seis meses te lo agradecerá. **Sexta:** agenda una retrospectiva real con datos, no con impresiones (GOB39), y si no cambia nada tras ella, pregúntate con doble bucle por qué (GOB40).

Y una advertencia final, de las que este proyecto escribe en sus propios documentos: **la gobernanza sirve a las personas, no al revés**. Si un dispositivo de este inventario empieza a exigirle a alguien que exponga a un niño, que trabaje de más o que calle un problema, el dispositivo está mal, no la persona —se diseña de nuevo (IG43, no daño; IG48, ética de la métrica).

---

## 7. Modelo de referencia en diez categorías (marco adoptado)

El proyecto adopta como **marco de referencia** un inventario de gobernanza de proyectos aportado para esta capa, organizado en diez categorías. No sustituye al inventario GOB1–GOB50 de este documento: lo **estructura**. Un inventario de gobernanza es el conjunto de artefactos, documentos, roles, procesos, dispositivos, métricas y evidencias que permiten dirigir, controlar, decidir, rendir cuentas y asegurar que el proyecto genere valor dentro de los límites aprobados. No existe una lista única universal: se adapta al tamaño, la criticidad, el sector, la regulación y la metodología (predictiva, ágil o híbrida).

**Categoría 1 — Marco estratégico y actas de constitución:** caso de negocio, acta de constitución (charters), plan estratégico y alineación, mapa de beneficios, roadmap, criterios de éxito/aceptación/cierre, análisis costo-beneficio (ROI, VAN, TIR, payback) y decisión Go/No-Go. *Cobertura aquí:* Acta (GOB1), encuadre (GOB2), criterios (GOB13), roadmap del proyecto — **falta: caso de negocio formal (→ GOB51, plantilla creada)**.

**Categoría 2 — Planes de gestión y líneas base:** plan de dirección, líneas base de alcance/cronograma/costo, EDT–WBS y diccionario, cronograma maestro e hitos, presupuesto, recursos, adquisiciones, calidad, riesgos, comunicación, interesados, cambios, configuración, transición/cierre y ESG. *Cobertura:* plan (GOB4), líneas base (GOB14), riesgos (GOB11), cambios (GOB12), WBS (GOB4 parcial), presupuesto (GOB22, plantilla creada) — **faltan con peso: plan de comunicación, plan de adquisiciones, plan de transición/cierre, sostenibilidad (marcados como pendientes del sector)**.

**Categoría 3 — Órganos, roles y responsabilidades:** comité directivo, sponsor, director/a de proyecto, PMO, comité de cambios (CCB), comité de riesgos, comité de arquitectura/seguridad/datos, auditoría, roles ágiles (PO, SM), líderes, secretario/a documental, matriz RACI/RASCI, organigrama del proyecto y matriz de escalamiento/delegación. *Cobertura:* RACI (GOB5), sponsor/coordinador/CTE (Acta art. 13), escalera de decisión (GOB25, plantilla creada), auditoría (GOB45) — *aplica según enfoque:* PO/SM sólo en equipos ágiles; comité de datos, sólo si el proyecto maneja datos sensibles a escala.

**Categoría 4 — Artefactos de control, decisión y seguimiento:** registros de interesados, riesgos/problemas, cambios, decisiones, supuestos; actas; informes de estado; cuadro de mando; umbrales de tolerancia; matriz de escalamiento; lecciones aprendidas; beneficios realizados; artefactos ágiles (backlog, DoD, burndown, velocity). *Cobertura:* GOB9, GOB10, GOB11, GOB12, GOB14, GOB17, GOB21, GOB26, plantillas A5/A6 — **faltan: registro de supuestos formal (parcial en A3) y registro de problemas (se añade dentro de la plantilla GOB9)**.

**Categoría 5 — Documentación legal, contractual y de cumplimiento:** contratos/SOW, NDA, SLA, licencias, matriz de cumplimiento, privacidad y seguridad, propiedad intelectual, evidencias de auditoría y firmas, conflictos de interés, código de conducta y canal de denuncias. *Cobertura:* consentimiento (GOB16, plantilla), política de protección (GOB7, plantilla), código de conducta (GOB8, plantilla), acuerdos con terceros (GOB19, plantilla), propiedad intelectual (Acta art. 10), ciclos legales (GOB29) — **falta: registro de conflictos de interés (pendiente, formato breve)**.

**Categoría 6 — Herramientas, dispositivos y plataformas tecnológicas:** plataformas de gestión (Jira, Asana, MS Project, Trello…), repositorios (SharePoint, Confluence…), BI (Power BI, Tableau…), ERP, colaboración (Teams, Slack, Zoom…), firma electrónica, seguridad (SSO, MFA), hardware, salas, modelado, tickets/ITSM y despliegue. *Decisión de este proyecto:* se cubre con **equivalentes FOSS gratuitos y de código abierto**, documentados en `plataformas-fooss-de-gobernanza.md` —misma función, soberanía de datos, sin licencias propietarias—; los nombres propietarios se listan sólo como referencia del mercado.

**Categoría 7 — Métricas e indicadores de gobernanza:** alineación estratégica, valor entregado (ROI/VAN/TIR), desempeño de cronograma (SPI) y de costo (CPI), variación de alcance, riesgos materializados, cambios, satisfacción de interesados, calidad, beneficios realizados, **madurez de gobernanza**, transparencia y auditorías cerradas. *Cobertura:* semáforo y KPIs (GOB14, GOB26) — *adaptación sectorial:* en proyectos educativos sin presupuesto formal, SPI/CPI/ROI se sustituyen por **KPIs de impacto por beneficiario** (Acta art. 19); sí se adoptan **madurez de gobernanza y auditorías cerradas**.

**Categoría 8 — Procesos y métodos de gobernanza:** ciclo de vida con stage-gates; procesos de inicio, planificación, ejecución, control y cierre; gestión de cambios, riesgos, interesados, beneficios y conocimiento; gestión de la configuración; aseguramiento de calidad; resolución de conflictos y escalamiento; auditoría; revisión post-implementación. *Cobertura completa:* puertas (GOB23), control de cambios (GOB12), retrospectiva = revisión post-implementación (GOB39), tandas = configuración (GOB30), escalamiento (GOB27, GOB47).

**Categoría 9 — Elementos culturales, éticos y de transparencia:** transparencia, rendición de cuentas, decisión basada en datos, confianza, inclusión, ética, conflictos de interés y cultura de mejora. *Cobertura:* registral (GOB9, GOB15, GOB35), ética (GOB7, GOB8, GOB49) y axiológica (neuroaxiología; no daño IG43).

**Categoría 10 — Artefactos según enfoque:** predictivo (EDT, Gantt, presupuesto detallado), ágil (backlog, sprint, DoD, burndown, velocity, retrospectivas, PI planning) e híbrido (líneas base + entregables iterativos con puertas). *Cobertura:* híbrido es el modo de este proyecto (puertas + ciclos + retrospectivas); los artefactos ágiles se usan sólo donde hay equipo ágil (plantilla D1, iteraciones), y el predictivo puro se limita a lo que el calendario escolar impone.

## 8. Cobertura, brechas y plantillas (qué se creó y qué queda)

**Cubierto y ya con plantilla rellenable:** encuadre (A1), requisitos (A2), plan/WBS (A3), verificación y validación (A4), riesgos y cambios (A5), retrospectiva (A6), patrones (A7), ADR (A8), estudio personal (S1), desarrollo (D1), neuroeducación infantil (N1), taller/curso (T1).

**Brechas de artefacto detectadas con el marco de referencia → plantillas creadas en esta tanda:** política de protección (**GOB7**), código de conducta y canal de denuncias (**GOB8**), registro de decisiones con problemas y supuestos (**GOB9**), acta de reunión con acuerdos (**GOB10**), informe de estado ejecutivo y de ciclo (**GOB15**), consentimiento informado (**GOB16**), acuerdos con terceros (NDA/encargos) (**GOB19**), manual de inducción y transferencia (**GOB20**), presupuesto y autorizaciones (**GOB22**), matriz de escalamiento y delegación de autoridad (**GOB25**) y caso de negocio con decisión Go/No-Go (**GOB51**).

**Brechas pendientes (registradas, sin plantilla todavía):** plan de comunicación; plan de adquisiciones/proveedores; plan de transición y cierre formal; sostenibilidad/ESG; registro de conflictos de interés (formato breve); organigrama del proyecto (para equipos >8 personas); SPI/CPI y métricas financieras (sólo si el proyecto tiene costo formal). *Criterio de cierre:* cada pendiente se convierte en plantilla cuando el proyecto que lo necesita lo pida —no antes (igual que todo el sistema: sin demanda real, el artefacto es peso).

**Brechas de dispositivo y métrica:** umbrales de tolerancia formalizados (tenemos el semáforo con umbrales por indicador; falta declarar umbrales de tiempo/costo donde apliquen) y **madurez de gobernanza** como indicador de nivel (pendiente de definir escala cuando haya más de un proyecto comparable).

**Una nota sobre la herramienta tecnológica:** el mercado propietario (Jira, SharePoint, Power BI, Teams, ERP…) es la referencia habitual; este proyecto adopta por decisión deliberada **alternativas libres (FOSS)** —misma función, datos soberanos, sin licencias— catalogadas en `plataformas-fooss-de-gobernanza.md`, mapeadas a estas mismas diez categorías.

## 9. Mínimo indispensable (reconciliado)

El marco de referencia define diez elementos mínimos para una gobernanza excelente. Este es su cruce con el kit mínimo de la sección 4:

**Coinciden plenamente:** acta de constitución (GOB1), plan de dirección con líneas base (GOB2 + GOB4 + GOB14), matriz RACI y "organigrama" de roles (GOB5; organigrama formal = pendiente para equipos grandes), comité de dirección y responsable de gobernanza (Acta art. 13: sponsor + coordinador + CTE), registros de riesgos/cambios/decisiones (GOB11, GOB12, GOB9), dashboard e informes (GOB14, GOB15, GOB26), repositorio versionado (GOB30 y GOB12), procesos de escalamiento y cambios (GOB27, GOB47, GOB12), auditoría y lecciones con cierre formal (GOB45, GOB17, re-firma del Acta) y evidencias de aprobación (GOB35, actas y firmas).

**Aporta el marco y nos faltaba:** el **caso de negocio** explícito con su decisión Go/No-Go (ahora, plantilla GOB51) y los **informes ejecutivos periódicos** con alcance de stakeholders externos (la plantilla GOB15 los cubre, ampliando el informe de ciclo).

**Aporta este proyecto y el marco no nombra:** política de protección de datos e imagen (GOB7), código de conducta con canal (GOB8), consentimiento (GOB16), manual de inducción como transferencia (GOB20), catálogo de patrones (GOB18) y semáforo con respuesta obligatoria (GOB26).

**Principio adoptado como cierre** (del marco de referencia, y coherente con lo que este documento venía diciendo): *la excelencia en gobernanza no está en tener todos los documentos, sino en que cada artefacto, rol y dispositivo sirva para decidir mejor, controlar riesgos y entregar valor de forma transparente.* Este inventario se revisa al inicio de cada proyecto, se adapta a su naturaleza y se audita periódicamente.

## Índice de entradas

**Artefactos**: Acta constitutiva (GOB1) · Encuadre y alcance (GOB2) · Requisitos (GOB3) · Plan y WBS (GOB4) · RACI (GOB5) · ADR (GOB6) · Políticas de protección (GOB7) · Código de conducta (GOB8) · Registro de decisiones (GOB9) · Actas con acuerdos (GOB10) · Registro de riesgos (GOB11) · Historial de cambios (GOB12) · Criterios y DoD (GOB13) · Línea base y tablero (GOB14) · Informes de ciclo (GOB15) · Consentimiento (GOB16) · Lecciones aprendidas (GOB17) · Catálogo de patrones (GOB18) · Acuerdos con terceros (GOB19) · Manual de inducción (GOB20) · Mapa de partes interesadas (GOB21) · Presupuesto y autorizaciones (GOB22) · Caso de negocio y Go/No-Go (GOB51).

**Dispositivos**: Puerta de calidad (GOB23) · Condición de entrada en vigor (GOB24) · Escalera de decisión (GOB25) · Semáforo (GOB26) · Escalamiento por umbral (GOB27) · Cadencia (GOB28) · Ciclos de actualización (GOB29) · Sistema de versiones y tandas (GOB30) · Pipeline de documentos (GOB31) · Ventana de congelación (GOB32) · Revisión por pares (GOB33) · Redundancia de roles (GOB34) · Registro como condición (GOB35).

**Herramientas**: FODA/SOACH (GOB36) · Mapa de partes en taller (GOB37) · Cinco porqués (GOB38) · Retrospectiva (GOB39) · Doble bucle (GOB40) · Priorización impacto-esfuerzo (GOB41) · Timeboxing (GOB42) · Check-in corto (GOB43) · Tablero visual (GOB44) · Auditoría con checklist (GOB45) · Escucha estructurada (GOB46) · Guion de negociación de alcance (GOB47) · Demo de estado (GOB48) · Autoinspección con preguntas guía (GOB49) · Reunión de decisión (GOB50).

---

*Capa Ingeniería de la Educación · Inventario de gobernanza (51 instrumentos: 23 artefactos, 13 dispositivos, 15 herramientas) + marco de referencia de 10 categorías · v0.1 · Proyecto Programa Sintético · Abierto por diseño: se amplía con cada proyecto real que use estos instrumentos.*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plataformas FOSS de gobernanza

## Herramientas gratuitas y de código abierto para dirigir proyectos con estructura y sin licencias

*Capa Ingeniería de la Educación · v0.1 · 29 de septiembre de 2026*
*Complemento del inventario `gobernanza-inventario-de-instrumentos.md` (categoría 6) · Términos: GOB, plantillas A/GOB*

---

## 0. Qué significa FOSS aquí y por qué el proyecto lo decide así

**FOSS** = *Free and Open Source Software*: software **gratuito** (sin licencia de uso) y **de código abierto** (cualquier persona puede auditarlo, modificarlo y alojarlo). Para gobernanza esto no es una preferencia estética: es una decisión de soberanía. Quien gobierna con herramientas propietarias alquiladas, cuando cambian los precios o las condiciones, pierde de la noche a la mañana su registro de decisiones, su riesgohistorial y su memoria. Quien gobierna con FOSS, **sus datos son suyos y su archivo sobrevive al proveedor**.

Tres advertencias honestas, porque "gratis" es una palabra tramposa:

**Gratis alojado ≠ libre.** Muchas nubes gratuitas son *freemium*: gratis hoy, con límites que llegan justo cuando el proyecto crece. El criterio correcto es la **licencia** (GPL, MIT, AGPL, MPL, Apache) y el derecho a autoalojar.

**Libre no es gratis de operar.** Autoalojar cuesta mantenimiento: actualizaciones, respaldos, seguridad. Ese mantenimiento es un **dispositivo de gobernanza con costo humano** (véase inventario, §2) — si nadie lo asume, la herramienta libre se vuelve abandonada. Declara al dueño antes de elegir.

**Los datos de menores suben la vara.** Para proyectos con niñas, niños y familias: preferencia por **autoalojado con cifrado** y mínima recolección (Acta art. 7; GOB7). La nube se usa sólo con contrato, finalidad clara y revisión legal.

Y una regla de proceso: **toda elección de plataforma es un ADR** (GOB6): qué se eligió, por qué, qué se descarta y cuándo se revisa.

---

## 1. Tres kits recomendados (por tamaño del proyecto)

**Kit 1 — Sin servidor (una persona o un equipo chico; costo: $0, sólo tu tiempo).** Git + Markdown (repositorio con versiones: funciona en tu computadora y en Codeberg/GitLab sin pagar) · LibreOffice (ofimática y hojas) · Jitsi Meet (reuniones) · CryptPad o HedgeDoc (actas colaborativas en línea, cifradas) · plantillas de esta carpeta impresas o en texto. Con esto se cubren casi todos los GOB: decisiones, actas, riesgos, retrospectivas, manual y hasta el semáforo (una hoja de cálculo).

**Kit 2 — Un servidor (equipo de 3 a 20; autoalojado en una VPS o un equipo local).** Suma: **Nextcloud** (archivos, calendario, formularios, videollamada) · **BookStack** o **Wiki.js** (manual y patrones) · **OpenProject** o **Redmine** (proyecto, riesgos, Gantt, actas) · **LimeSurvey** (consentimientos y encuestas). Este kit cubre el inventario completo para un equipo que ya necesita roles y portales.

**Kit 3 — Organización (varios equipos o planteles).** Suma: **GitLab o Forgejo** (repositorio con revisión por pares y flujos de aprobación) · **Metabase** (cuadros de mando) · **Nextcloud** con SSO/cifrado (identidad y resguardo) · y los kits anteriores con responsables por espacio definidos en el Acta.

---

## 2. Catálogo por función (con licencias de referencia)

*Se lista la licencia cuando es un estándar bien conocido; verifica siempre la vigente en el repositorio del proyecto.*

**Dirección, plan y control de proyectos (GOB2, GOB4, GOB14, GOB11).** **OpenProject** (GPL-3.0): gestión clásica, híbrida y ágil con Gantt, riesgos, actas e informes; edición comunidad gratuita y autoalojable — es la referencia FOSS más completa en 2026. **Redmine** (GPL-2.0): ligero, viejo y estable, fuerte en seguimiento de incidencias y wikis; ideal para equipos técnicos que quieren todo en un sitio. **Taiga** (MPL-2.0): ágil y visual (Scrum/Kanban), con nube y autoalojado. **Plane** (núcleo abierto, autoalojable por Docker): interfaz moderna para tableros y roadmaps. **Leantime** (GPL): enfoque a metas, útil para equipos no técnicos. **Tuleap** (GPL): proyecto + desarrollo + QA. **GanttProject** y **ProjectLibre** (escritorio, GPL): Gantt y WBS sin servidor para uso individual.

**Repositorio documental con versiones (GOB12, GOB30).** **Git** con **Markdown** es la combinación de este proyecto: portable, difusable, con historial real y sin licencias —el sistema de tandas vive aquí. Para equipos: **Gitea/Forgejo** (MIT; también **Codeberg** como alojamiento comunitario) o **GitLab Community** (MIT) dan historial, ramas, revisión y publicación. Si el equipo prefiere nube: **Nextcloud Archivos** (AGPL-3.0) con historial de versiones y **Seafile** (GPL) para sincronización cifrada.

**Conocimiento vivo, manual y patrones (GOB18, GOB20).** **BookStack** (MIT): estantes–libros–capítulos, ideal para glosarios, manuales y catálogos de patrones. **Wiki.js** (MIT): wiki moderna y rápida. **DokuWiki** (GPL-2.0): archivos planos, sin base de datos, supervivencia garantizada.

**Reuniones, actas y trabajo en equipo (GOB10, GOB43, GOB50).** **Jitsi Meet** (Apache-2.0): videoconferencia sin límites de cuenta. **HedgeDoc** (MIT) o **Etherpad** (Apache-2.0): actas y notas colaborativas en vivo que quedan guardadas. **CryptPad** (AGPL-3.0): documentos colaborativos con cifrado de extremo a extremo —el más adecuado cuando hay datos sensibles (GOB7).

**Encuestas, consentimiento y formularios (GOB16, GOB46).** **LimeSurvey** (GPL): encuestas y formularios con consentimientos, firmas simples y anonimato. **Nextcloud Forms**: formularios integrados al kit 2. Para familias sin correo: la hoja impresa de `GOB16-consentimiento-informado.md` sigue siendo válida —la tecnología no debe ser barrera de acceso.

**Tableros visuales (GOB44, plantilla D1).** **WeKan** (MPL-2.0) y **Kanboard** (MIT): kanban simple. **Plane**: tableros modernos. *Advertencia:* **Focalboard** pasó a legado (el repositorio independiente quedó archivado y su desarrollo se integró a Mattermost) — no se recomienda para instalaciones nuevas; conocerlo evita elegir un proyecto huérfano.

**Diagramas y modelado (GOB4, GOB4).** **Mermaid** (MIT): diagramas escritos en texto dentro de los propios Markdown —así vive en esta serie; se dibujan y versionan sin software gráfico. **Kroki** (open source): servidor que renderiza esos diagramas. **draw.io / diagrams.net** (escritorio con código abierto): diagramas con archivo local sin cuenta.

**Calendario y cadencia (GOB28).** **Nextcloud Calendario** (CalDAV) con suscripción en cualquier cliente; **LibreOffice**: agenda simple. La cadencia de gobernanza cabe en cualquier calendatorio con recordatorios —lo importante es la repetición, no la app.

**Cuadros de mando y métricas (GOB14, GOB26).** **Metabase** (open source): preguntas y paneles sin escribir SQL. **Grafana** (open source): cuando las métricas vienen de sistemas (proyectos de software). En educación suele bastar **LibreOffice Calc** con el semáforo del Acta art. 20 —no se necesita BI para mirar cuatro indicadores.

**Identidad, accesos y respaldos (GOB7).** **KeePassXC** (GPL) o **Vaultwarden** (AGPL-3.0, autoalojado): gestores de contraseñas para equipos. **SSH + respaldos automatizados** de todo repositorio y base: el dispositivo más subestimado de la gobernanza. **Bitwarden/Vaultwarden** y cifrado de disco para la máquina que custodia datos de personas.

**Ofimática y firmas.** **LibreOffice** (MPL-2.0): documentos, hojas y presentaciones sin suscripción. Para firmas: las **firmas manuscritas digitalizadas** con acta de respaldo cumplen en la mayoría de los trámites internos; si la norma exige firma electrónica avanzada, usa el proveedor que la ley señale (ahí el FOSS no aplica —la ley manda primero, escala de precedencia del Acta).

---

## 3. Cómo elegir (cinco preguntas antes de instalar)

**¿De quién son los datos?** Si no puedes exportarlos todos y salirte, no es tu plataforma. **¿Quién la mantiene?** Sin nombre responsable, la herramienta libre se abandona. **¿Qué GOB cubre?** Cada elección se escribe en el ADR (GOB6) con el instrumento que sirve —si no sirve a ningún GOB, es un juguete. **¿Aprenderla cuesta más que el problema?** La hoja de cálculo que el equipo usa gana a la plataforma perfecta que nadie abre. **¿Con qué licencia?** Registra la licencia en el ADR; si cambia a propietaria o con fines de lucro, se revisa la elección.

---

## 4. Mapeo rápido instrumento → plataforma

Para registrar decisiones, actas y riesgos: **Kit 1** (Git+Markdown) o **OpenProject/Redmine**. Para política, consentimiento y encuestas: **LimeSurvey / Nextcloud Forms / impreso**. Para manual, glosario y patrones: **BookStack** o el **repositorio Markdown**. Para reuniones y trabajo en equipo: **Jitsi + HedgeDoc/CryptPad**. Para tablero y Gantt: **OpenProject / Plane / GanttProject**. Para semáforo y KPIs: **Calc / Metabase**. Para archivo histórico con versiones: **Git con tandas** (el método ya probado en este proyecto). Y como instrumento de seguridad: **KeePassXC/Vaultwarden + respaldos automatizados**.

---

## 5. Estado

**v0.1** — catálogo de referencia para elecciones del proyecto; se actualiza con el ciclo anual del Acta y con cada elección real que se documente como ADR. Cuando el proyecto adopte su kit, este documento pasa de catálogo a **inventario vivo de plataformas en uso** (con responsable, licencia y fecha de revisión por herramienta).

---

*Capa Ingeniería de la Educación · Plataformas FOSS de gobernanza · v0.1 · Proyecto Programa Sintético.*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

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

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla A1 — Encuadre y alcance

**Ciclo:** inicio (antes de cualquier diseño) · **Universal:** cualquier tipo de proyecto · **Términos de apoyo:** IG1 (sistema), IG8 (frontera), IG25 (alcance), IG35 (partes interesadas) · **Gobernanza:** GOB2, GOB5, GOB21

---

## Para qué sirve y cuándo usarla

Esta plantilla responde la primera pregunta de todo proyecto: **¿qué problema real estamos resolviendo, para quién, y qué NO vamos a hacer?** Úsala el día que alguien diga "hay que hacer algo sobre…" y antes de que se dibuje un solo plano, se escriba una sola línea de código o se compre un solo material.

Si sólo vas a completar una plantilla de esta carpeta, que sea ésta. Un encuadre claro ahorra el trabajo de tres semanas de improvisación.

---

## Cómo completarla

**1. El problema real (no el síntoma pedido).**

> Lo que nos pidieron: ______________________________________________
>
> El problema que descubrimos al preguntar: ______________________________________________
>
> ¿Cómo lo sabemos? (una frase con dato o con cita de quien lo vivió): __________________

**2. Para quién es.**

Partes interesadas, en orden de quién más lo necesita: ______________________________________________

¿Quién debe opinar antes de decidir? ______________________________________________

¿Quién sólo necesita que le informen? ______________________________________________

**3. La meta.**

Si este proyecto funciona, dentro de ____ semanas/meses, ________________________________
(hazla comprobable: ¿quién verá qué, y cómo se notará?)

**4. La frontera: dentro y fuera de alcance.**

*Dentro de alcance (lo que sí haremos):*

- ________________________________________________________________________
- ________________________________________________________________________

*Fuera de alcance (lo que NO haremos, aunque nos lo pidan después):*

- ________________________________________________________________________
- ________________________________________________________________________

**5. Restricciones reales.** Tiempo disponible: ____ · Presupuesto o recursos: ____ · Normas que aplican: ____ · Personas disponibles: ____

**6. Riesgos de este encuadre.** Lo que más podría hacer fracasar este encuadre: ______________________________________________

---

## Consejo de uso

El campo más subestimado es el de "fuera de alcance". Escríbelo con crudeza: ahí se salva la cordura de todo el equipo. Y si el problema que descubriste no se parece al que te pidieron, cambia el encuadre ahora, no en la mitad del proyecto —IG12 (levantamiento de requisitos) es barato al principio y carísimo después.

---

*Plantillas · Ciclo: inicio · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla A2 — Requisitos

**Ciclo:** inicio (después del encuadre) · **Universal:** cualquier tipo de proyecto · **Términos de apoyo:** IG10 (requisito), IG11 (especificación), IG12 (levantamiento), IG17 (criterio de aceptación) · **Gobernanza:** GOB3, GOB13

---

## Para qué sirve y cuándo usarla

Convierte lo que quieres lograr en **condiciones escritas que se puedan comprobar**. Úsala cuando ya sabes qué proyecto es (A1 completado) y necesites decir exactamente qué tiene que ser cierto para que "quedó". Sin esto, "quedó" es una opinión.

Regla de oro de la plantilla: **todo requisito pasa por la prueba del "¿cómo lo pruebas?"**. Si no puedes responder, no es requisito todavía.

---

## Cómo completarla

**1. Fuentes de donde salen los requisitos** (marca las que apliquen y anota lo que dicen):

- ☐ **Norma o derecho** (qué dice): ______________________________________________
- ☐ **Evidencia** (qué muestra la ciencia o la investigación): ______________________________________________
- ☐ **Usuario o beneficiario** (qué necesita, según lo escuchado): ______________________________________________
- ☐ **Contexto** (qué permite o impone el entorno): ______________________________________________
- ☐ **Equipo** (qué prometimos entre nosotros): ______________________________________________

**2. Lista de requisitos** (uno por renglón; condición + acto + criterio cuando sea posible).

R1. ________________________________________________________________________ — *Cómo se comprueba:* ____________________________________

R2. ________________________________________________________________________ — *Cómo se comprueba:* ____________________________________

R3. ________________________________________________________________________ — *Cómo se comprueba:* ____________________________________

R4. ________________________________________________________________________ — *Cómo se comprueba:* ____________________________________

R5. ________________________________________________________________________ — *Cómo se comprueba:* ____________________________________

**3. Criterios de aceptación del conjunto.** El proyecto se considerará "terminado y correcto" cuando:

- ☐ ______________________________________________________________________
- ☐ ______________________________________________________________________
- ☐ ______________________________________________________________________

**4. Supuestos.** Este requisito funciona si: ______________________________________________

**5. Requisitos NO negociables** (los que vienen de norma o de no daño — se listan aparte para no discutirlos después):

- ________________________________________________________________________

---

## Consejo de uso

Si un requisito crece en la conversación, no lo edites en silencio: apúntalo en A5 (control de cambios). Y cuidado con el enemigo clásico: "que sea de calidad" no es requisito, es un deseo con corbata —IG10 te enseña a distinguirlos.

---

*Plantillas · Ciclo: inicio · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla A3 — Diseño y plan

**Ciclo:** diseño (después de los requisitos) · **Universal:** cualquier tipo de proyecto · **Términos de apoyo:** IG30 (WBS), IG31 (RACI), IG15 (iteración), IG44 (supuestos), IG14 (modelo en V) · **Gobernanza:** GOB4, GOB5, GOB13, GOB25

---

## Para qué sirve y cuándo usarla

Ordena el trabajo antes de empezarlo: **qué piezas tiene el proyecto, quién hace qué, en qué orden y bajo qué supuestos**. Úsala cuando los requisitos de A2 ya estén escritos. El resultado debe poder leerlo alguien que no estaba en la reunión.

---

## Cómo completarla

**1. Desglose del trabajo (WBS) — trozos manejables y verificables.**

P1. ________________________________________________________________________ *(¿qué lo hace "terminado"? ____________)*

P2. ________________________________________________________________________ *(¿qué lo hace "terminado"? ____________)*

P3. ________________________________________________________________________ *(¿qué lo hace "terminado"? ____________)*

P4. ________________________________________________________________________ *(¿qué lo hace "terminado"? ____________)*

P5. ________________________________________________________________________ *(¿qué lo hace "terminado"? ____________)*

**2. Roles (RACI).**

R (resuelve): ______________________ · A (aprueba): ______________________

C (consulta): ______________________ · I (se entera): ______________________

**3. Secuencia y dependencias.** ¿Qué tiene que existir antes de que empiece esto? ______________________________________________

Formato elegido: ☐ en V (verificar por etapa) · ☐ iteraciones cortas (probar y ajustar) — *¿por qué?* ______________________

**4. Supuestos del diseño** (si uno falla, el plan se cae — se listan para vigilarlos):

- ______________________________________________________________________
- ______________________________________________________________________

**5. Puertas.** ¿En qué momentos NO se avanza sin cumplir condiciones? Puerta 1: ______________________ *(condiciones: ____________)* · Puerta 2: ______________________ *(condiciones: ____________)*

**6. Fuera de plano.** Lo que este diseño decide NO incluir (hereda de A1): ______________________________________________

---

## Consejo de uso

Un plan sin supuestos escritos es una profecía. Escríbelos y revísalos en cada retrospectiva (A6): muchos "imprevistos" eran supuestos que nadie se atrevió a anotar. Y si algo no se puede descomponer en dos renglones, es que todavía no se entiende —vuelve a A2.

---

*Plantillas · Ciclo: diseño · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla A4 — Verificación y validación

**Ciclo:** ejecución y cierre de fase · **Universal:** cualquier tipo de proyecto · **Términos de apoyo:** IG13 (verificación vs. validación), IG18 (línea base), IG19 (calidad), IG17 (criterio de aceptación) · **Gobernanza:** GOB13, GOB14, GOB26

---

## Para qué sirve y cuándo usarla

Separa las dos preguntas que se confunden en todo proyecto: **¿lo hicimos conforme a lo que prometíamos?** (verificación) y **¿era esto lo que realmente necesitaban?** (validación). Úsala al cierre de cada fase —y la línea base, al principio.

---

## Cómo completarla

**0. Línea base (al INICIO de la fase, antes de intervenir).** Cómo estábamos antes: ______________________________________________
*(dato, no impresión: cuenta, medición o registro)*

**1. Verificación — ¿se hizo conforme?** Para cada requisito de A2:

R1: ☐ cumplido ☐ parcial ☐ no cumplido — *evidencia:* ______________________________

R2: ☐ cumplido ☐ parcial ☐ no cumplido — *evidencia:* ______________________________

R3: ☐ cumplido ☐ parcial ☐ no cumplido — *evidencia:* ______________________________

*(Criterios de aceptación de A2: ☐ todos los cumplidos · ☐ observaciones registradas)*

**2. Validación — ¿servió en la vida real?** Preguntamos a quien lo usa:

¿Qué funcionó para usted/ustedes? ______________________________________________

¿Qué no sirvió o faltó? ______________________________________________

¿Cambiaríamos algo si lo repitiéramos? ______________________________________________

*Veredicto:* ☐ lo que se construyó es lo que se necesitaba · ☐ hay que ajustar · ☐ hay que rediseñar

**3. Métricas con lectura.** Indicador: ______________ · Línea base: ____ · Ahora: ____ ·
*¿Quién lo lee y qué hace con el dato?* ______________________________________________

*Semáforo:* ☐ verde (sostener) · ☐ ámbar (corregir con responsable y fecha) · ☐ rojo (escalar)

**4. Defectos encontrados** (apúntalos aunque duela — son información, IG20): ______________________________________________

---

## Consejo de uso

La trampa de esta plantilla es validar con quien firma y no con quien usa. Si la validación no incluye la voz de la persona real —el usuario, la familia, el niño, el docente—, sólo verificaste. Y el dato sin lectura es decoración: si en la casilla de "quién lo lee" no hay nombre, la métrica no cuenta.

---

*Plantillas · Ciclo: ejecución y cierre · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla A5 — Riesgos y control de cambios

**Ciclo:** transversal (desde el inicio, revisada en cada fase) · **Universal:** cualquier tipo de proyecto · **Términos de apoyo:** IG32 (riesgo vs. problema), IG33 (registro), IG25/IG26 (alcance y deriva), IG27 (control de cambios) · **Gobernanza:** GOB11, GOB12, GOB47

---

## Para qué sirve y cuándo usarla

Dos cosas que los proyectos confunden todo el tiempo: **lo que puede pasar** (riesgo, se anticipa) y **lo que ya pasó** (problema, se resuelve). Más el guardián del alcance: todo cambio que llega después de la firma. Úsala desde el día uno y actualízala en cada revisión.

---

## Cómo completarla

**1. Registro de riesgos** (uno por renglón: qué, tan probable, tan grave, qué hacemos, cómo sabremos que va a pasar).

R1. *Qué podría pasar:* ______________________ *Probable:* bajo/medio/alto · *Grave:* bajo/medio/alto
*Si ocurre, hacemos:* ______________________ · *Señal de alarma:* ______________________

R2. *Qué podría pasar:* ______________________ *Probable:* bajo/medio/alto · *Grave:* bajo/medio/alto
*Si ocurre, hacemos:* ______________________ · *Señal de alarma:* ______________________

R3. *Qué podría pasar:* ______________________ *Probable:* bajo/medio/alto · *Grave:* bajo/medio/alto
*Si ocurre, hacemos:* ______________________ · *Señal de alarma:* ______________________

**2. Riesgo rojo (el que más podría tumbar el proyecto).** ______________
*¿Quién lo vigila?* ______________ *¿Con qué frecuencia se revisa?* ______________

**3. Problemas abiertos (lo que ya pasó y no se ha resuelto).**

P1. ______________________________ *Responsable:* ____________ *Fecha límite:* ____________

**4. Control de cambios.** Todo cambio a lo ya decidido pasa por aquí:

*Qué quiero cambiar:* ______________________________________________

*¿Por qué? (dato o razón):* ______________________________________________

*¿Qué afecta? (alcance, tiempo, requisitos, dinero):* ______________________________

*Aprueba:* ______________ · *Fecha:* ______________ · *Versión anterior:* ______ *Nueva:* ______

*Registrado en:* ☐ este expediente · ☐ acta/reunión · ☐ registro del proyecto

---

## Consejo de uso

Escribe los riesgos como frases que empiecen con "podría…": si empieza con "pasó", ya es un problema y pertenece a otro renglón. Y el control de cambios no es para frenar: es para que el cambio se vea venir. El proyecto que no registra cambios no tiene historial, y sin historial no se puede aprender —ni defenderse de la pregunta "¿y esto por qué cambió?".

---

*Plantillas · Ciclo: transversal · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla A6 — Retrospectiva y mejora

**Ciclo:** cierre de fase y mejora continua · **Universal:** cualquier tipo de proyecto · **Términos de apoyo:** IG21 (causa raíz), IG50 (mejora con constancia), doble bucle (revisar las reglas, no sólo los resultados) · **Gobernanza:** GOB17, GOB38, GOB39, GOB40

---

## Para qué sirve y cuándo usarla

Responde tres preguntas, en orden y sin buscar culpables: **¿qué pasó?, ¿por qué pasó?, ¿qué cambiamos?** Úsala al final de cada fase, cada sprint, cada ciclo escolar o cada sesión importante. Es el bucle que separa a los proyectos que mejoran de los que sólo repiten.

---

## Cómo completarla

**Datos primero (lo que se hizo y lo que salió) — traer antes de la sesión:**

- Avances: ______________________________________________
- Números relevantes (de A4): ______________________________________________
- Lo que no salió como esperábamos: ______________________________________________

**Preguntas de la sesión (responder en grupo, con honestidad y sin nombres culpables):**

1. ¿Qué funcionó bien y queremos **mantener**? ______________________________________________

2. ¿Qué no funcionó y queremos **cambiar**? ______________________________________________

3. ¿Qué sorprendió (buena o mala noticia)? ______________________________________________

**Causa raíz del asunto más importante** (preguntar "¿y por qué?" hasta llegar a algo accionable):

Problema: ______________________ → ¿por qué? ______________ → ¿por qué? ______________ → *causa que sí podemos arreglar:* ______________

**Doble bucle (la pregunta más incómoda, la más valiosa).** ¿La regla o supuesto que nos llevó aquí sigue vigente?
☐ sí, se mantiene · ☐ no, se cambia: ______________________________________________

**Acuerdos (con responsable y fecha):**

- Cambio 1: ______________________ *Responsable:* ____________ *Fecha:* ____________
- Cambio 2: ______________________ *Responsable:* ____________ *Fecha:* ____________

**Lo que ya queda como práctica buena** (para el catálogo de patrones, A7): ______________________________________________

**Lo que fue antipatrón y nombramos hoy** (para el catálogo, A7): ______________________________________________

---

## Consejo de uso

La retrospectiva muere de dos formas: sin datos (se queda en opiniones bonitas) y con culpables (se queda en silencios educados). Trae los números de A4 y nombra patrones, no personas. Y el campo del doble bucle es el que más se salta: sin él, todo mejora excepto lo que produce los problemas —y eso se llama mantener el problema con eficiencia.

---

*Plantillas · Ciclo: cierre y mejora · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla A7 — Registro de patrones y antipatrones

**Ciclo:** mejora continua · **Universal:** cualquier tipo de proyecto · **Términos de apoyo:** IG36 (patrón), IG37 (antipatrón), IG38 (arquitectura de soluciones repetibles) · **Gobernanza:** GOB18, GOB39

---

## Para qué sirve y cuándo usarla

Cuando algo funciona y se repite, merece **nombre** para poder enseñarlo, repetirlo y corregirlo con una palabra. Cuando algo falla y se repite, el nombre es aún más urgente. Úsala desde cualquier retrospectiva (A6) o cuando el equipo diga "esto pasa siempre…". El objetivo es ir poblando **tu catálogo propio** de soluciones y errores recurrentes, como los que ya viven en `neurogestion-patrones-y-antipatrones.md`.

---

## Cómo completarla — para cada hallazgo, una ficha

**Ficha de patrón (solución que funcionó):**

*Nombre corto (con el que se dirá en equipo):* ______________________________

*Problema recurrente que resuelve:* ______________________________________________

*Contexto donde funciona* (¿siempre, o en…?): ______________________________________________

*La solución, en tres pasos:*
1. ______________________________________________
2. ______________________________________________
3. ______________________________________________

*Evidencia de que funciona* (dónde lo probamos y qué salió): ______________________________________________

*Quién lo puede enseñar:* ______________________

☐ Se registra en el catálogo del equipo · ☐ Pendiente de segunda prueba

---

**Ficha de antipatrón (forma que parece solución y daña):**

*Nombre corto:* ______________________________

*Qué se hace hoy y por qué parece buena idea:* ______________________________________________

*Qué daña, concreto* (a quién, cómo se nota): ______________________________________________

*El contrapatrón* (la forma buena que lo sustituye): ______________________________________________

*Evidencia:* ______________________________________________

☐ Se nombra en equipo (sin humillar: es forma, no persona) · ☐ Se busca su contrapatrón en el catálogo

---

## Consejo de uso

Un buen nombre de patrón se puede decir en una reunión sin explicación: "esto es un *checklist muerto*". Si hace falta un párrafo para explicar el nombre, es demasiado largo. Y cuidado: registrar un antipatrón no es regalar una amonestación —es cambiar una forma que se repite, y eso se hace nombrándola, no señalando al que la hace.

---

*Plantillas · Ciclo: mejora continua · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla A8 — ADR: registro de decisión (arquitectura)

**Ciclo:** diseño y cambios estructurales · **Universal:** cualquier tipo de proyecto · **Términos de apoyo:** IG38 (arquitectura), IG27 (control de cambios), IG47 (humildad de modelo) · **Gobernanza:** GOB6, GOB9, GOB12

---

## Para qué sirve y cuándo usarla

Para las decisiones **caras de dar marcha atrás**: las que dan forma al proyecto y que dentro de dos años alguien querrá "mejorar" sin saber por qué existían. Úsala cuando haya que elegir entre dos caminos estructurales y el equipo diga "¿y si lo anotamos…?". Si la decisión es reversible y barata, no necesita ADR: decídela y ya.

---

## Cómo completarla

**ADR-Nº: Título de la decisión** *(una frase que diga qué se decide)*

**Estado:** ☐ Propuesta · ☐ Aceptada · ☐ Rechazada · ☐ Sustituida (por ADR-___) · **Fecha:** __________

**Contexto.** ¿Qué situación lo obliga a decidir? ¿Qué se ha intentado? ¿Qué restricciones hay (norma, tiempo, recursos, personas)?
______________________________________________________________________________
______________________________________________________________________________

**Decisión.** Lo que queda decidido, en una frase que pueda repetir alguien que no estaba:
______________________________________________________________________________

**Alternativas consideradas.**

A. ________________________________________________________________________ *por qué no:* ______________

B. ________________________________________________________________________ *por qué no:* ______________

C. (la elegida) ________________________________________________________________________

**Consecuencias.**

Lo que ganamos: ______________________________________________

Lo que asumimos (costos, deuda, riesgos nuevos): ______________________________________________

Lo que dejamos de poder hacer: ______________________________________________

**Condiciones para revisarla** (bajo qué cambiaríamos esta decisión): ______________________________________________

**Registro.** Aprueba: ______________ · *Versión afectada:* ______________ · *Dónde queda publicada:* ______________

---

## Consejo de uso

El campo más subestimado es "por qué no" de las alternativas descartadas: es lo que impide que dentro de un año alguien "descubra" la opción B como si nadie la hubiera pensado. Y si no puedes escribir la decisión en una frase que repita otro, no está decidida: está sugiriéndose.

---

*Plantillas · Ciclo: diseño y cambios estructurales · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla S1 — Meta y práctica de estudio

**Ciclo:** aprendizaje autodirigido (tuyo) · **Universal:** cualquier habilidad o conocimiento que quieras dominar · **Términos de apoyo:** IA8 (objetivo verificable), IA9 (habilitantes), IA13 (evidencia de logro), andragogía (los 6 principios: porqué, autonomía, experiencia) · **Gobernanza:** GOB2, GOB3, GOB9

---

## Para qué sirve y cuándo usarla

Para tus **metas y alcances de prácticas y sesiones de estudio personales**: lo que quieres dominar —un idioma, un instrumento, este corpus de ingeniería, una herramienta de software— con la seriedad con la que tratarías un proyecto de cliente. Úsala cuando la intención de aprender ya existe y quieres convertirla en algo que se pueda comprobar.

La regla que sostiene la plantilla: **lo que no se practica con fecha no se aprende, se desea**.

---

## Cómo completarla

**1. El porqué (primero, antes que el plan — así lo exige la andragogía).**

¿Para qué me sirve esto? ¿Qué voy a poder hacer que hoy no puedo? ______________________________________________

**2. La meta con evidencia (qué demostrará que lo logré).**

Cuando termine este ciclo, podré ______________________________________________
*demostrándolo así (un producto, una grabación, una ejecución, una explicación a otro):*
______________________________________________________________________________

**3. Desglose en habilitantes** (los escalones, del más chico al más grande):

H1. ______________________________________________ ☐ lo logré con apoyo ☐ sólo

H2. ______________________________________________ ☐ lo logré con apoyo ☐ sólo

H3. ______________________________________________ ☐ lo logré con apoyo ☐ sólo

**4. Plan de sesiones de práctica.** *Duración de cada sesión:* ____ min · *Frecuencia:* ________
*El truco de andamíage: sesión corta sostenida gana a maratón olvidado.*

S1: ____________ · S2: ____________ · S3: ____________ · S4: ____________

*(¿qué haré exactamente en cada sesión? una línea:)* ______________________________________________

**5. Registro (tres líneas por sesión, como en el proyecto).**

*¿Qué pude sólo?* ________ *¿Con qué apoyo?* ________ *¿Qué me informó mi error?* ________

**6. Mi retroalimentación** (al cierre del ciclo): ¿qué estrategia funcionó mejor y por qué?
______________________________________________________________________________

---

## Consejo de uso

El campo más traidor es la evidencia: "voy a leer más" no es comprobable; "explicaré este concepto a una persona que no lo sabe en 10 minutos" sí. Y si fallas una sesión, no te castigues ni saltes la siguiente: el error de estudio es exactamente igual que el error de proyecto —es información (AX-1), no condena. Registra qué te distrajo, y diseña la siguiente sesión contra esa distracción, no contra tu carácter.

---

*Plantillas · Ciclo: aprendizaje autodirigido · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

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

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla N1 — Realidad alcanzable (neuroeducación)

**Ciclo:** diseño de intervención educativa con niñas y niños concretos · **Universal dentro del ámbito infantil:** un grupo, un grado o un caso específico · **Términos de apoyo:** IE9 (especificación local), requisito de factibilidad neural (NI27), apoyos por perfil, Acta art. 7 (datos y consentimiento) · **Gobernanza:** GOB7, GOB16, GOB13

---

## Para qué sirve y cuándo usarla

Para **plantear realidades alcanzables** para un grupo o una niña o niño específico: lo que es posible pedirles según su edad y su perfil, con qué apoyos, en qué entorno y cómo se sabrá que avanzaron. Úsala cuando un plan genérico (planes por grado, secuencias) tenga que bajar a la realidad de personas reales —y antes de que la expectativa invente exigencias imposibles.

**Guardas que esta plantilla carga por diseño:** no diagnostica; no clasifica; usa consentimiento para datos e imagen; deriva ante señales de alerta (informe §7); nunca convierte un perfil en etiqueta.

---

## Cómo completarla

**1. El perfil (sin diagnóstico, con lo observable).**

Grupo o persona (edad y grado): ______________________________________________

*Lo que hace hoy con apoyo y sin apoyo* (dos o tres observaciones reales): ______________________________________________

*Lenguajes con los que se comunica:* ______________________________________________

*Qué le regula (música, abrazo si lo acepta, movimiento, silencio…):* ______________________________________________

*Qué lo sobrecarga (ruido, texturas, prisa, multitudes…):* ______________________________________________

*Lo que le apasiona (interés intenso = recurso, no distracción):* ______________________________________________

**2. Realidad alcanzable (lo que SÍ es exigible ahora).**

Por su edad (referentes, no examen): ______________________________________________

Con su perfil y apoyos: ______________________________________________

*Esto NO le exijo aún (y por qué):* ______________________________________________

**3. Apoyos y ajustes.**

Universales para todo el grupo: ☐ rutina visible ☐ 1 paso + apoyo visual ☐ movimiento entre bloques ☐ salida sensorial autorizada ☐ tiempo de espera de 5–10 s

Específicos aquí: ______________________________________________

**4. Entorno y estados** (neuroergonomía del caso).

Ajustes de espacio/tiempo: ______________________________________________
*Secuencia de estados de la sesión:* regular → explorar → concentrar → descansar
*Transición con aviso:* ______________________________________________

**5. Protocolos practicados** (según la edad, con role-play y repetición):

☐ paro-miro-decido · ☐ si me pierdo me quedo y pido ayuda · ☐ si algo me hace raro lo cuento · ☐ otro: __________________

*Fecha del último ensayo:* ________ *¿Se ejecutó en situación?* ☐ sí ☐ aún no

**6. Evidencia de proceso (tres líneas, sin calificar al niño).**

*¿Qué pudo solo?* ________ *¿Con cuánto apoyo?* ________ *¿Qué nos informó su error?* ________

**7. Derivaciones.** Señal observada (si la hay): ______________________________
*Se comunica a:* ______________ *(la escuela observa y deriva; nunca diagnostica)*

**8. Consentimiento** para datos o imagen: ☐ obtenido y revocable · ☐ no aplica

---

## Consejo de uso

La casilla más importante es "esto NO le exijo aún": escribirla es lo que separa un plan alcanzable de una frustración innecesaria (el error más caro del diseño infantil). Y si un apoyo funciona para uno, pruébelo con el grupo antes de llamarlo "especial": casi todo lo que sirve a un perfil neurodivergente mejora el aula entera. Nunca conviertas este perfil en una etiqueta pública: es una herramienta de diseño, no una definición de la persona.

---

*Plantillas · Ciclo: diseño educativo infantil · v0.1 · Marco: Acta y serie de neuroeducación.*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla T1 — Diseño de taller o curso

**Ciclo:** diseño instruccional (ADDIE en una página) · **Universal:** talleres, cursos, capacitaciones, módulos · **Términos de apoyo:** IA2 (ADDIE), IA3 (diseño hacia atrás), IA4 (alineación), IA14 (carga cognitiva), IA19 (UDL) · **Gobernanza:** GOB3, GOB13, GOB45, GOB46

---

## Para qué sirve y cuándo usarla

Para diseñar **cualquier taller o curso** con la alineación mínima que evita el desastre clásico: enseñar una cosa, prometer otra y evaluar una tercera. Úsala cuando tengas que dar o diseñar una formación —de una sesión de 20 minutos a un curso de varias semanas— y quieras que funcione para quien la recibe, no sólo que se vea bien.

---

## Cómo completarla

**1. Para quién (antes que el qué).**

Perfil de quien participa: ______________________________________________
*Qué traen ya (experiencia):* ______________________________________________
*Qué limita (tiempo, idioma, accesibilidad, cansancio):* ______________________________________________

**2. Evidencia primero (diseño hacia atrás).**

Al terminar, participantes podrán ______________________________________________
*y lo demostrarán con:* ______________________________________________
(una grabación, una práctica, un producto, una explicación a otro — no con "lo entendieron")

**3. Alineación en tres renglones.** *Objetivo:* ______________
*Actividad que lo entrena:* ______________ · *Cómo lo evalúo:* ______________
*(Si alguno de los tres habla de otra cosa, rehazalo aquí y no en el aula.)*

**4. Secuencia con tiempos y carga.**

Bloque 1 (__ min): ______________________ *función:* ______________

Bloque 2 (__ min): ______________________ *función:* ______________

Bloque 3 (__ min): ______________________ *función:* ______________

*Cierre (__ min):* ______________________________________________

*Reglas de carga:* nada de dos canales compitiendo · una idea nueva por bloque · movimiento entre bloques si dura más de 20 min.

**5. Accesibilidad desde el diseño (UDL):** ☐ se puede escuchar y ver ☐ se puede leer y hacer ☐ hay opción oral y escrita de participar ☐ materiales alternativos listos: __________________

**6. Piloto.** Antes de escalar: ¿con quién lo pruebo primero? ______________
*Qué voy a medir:* ______________ *Si falla, cambio:* ______________

**7. Retroalimentación del diseño (post-curso).** ¿Qué lograron? (evidencia, no aplauso) ______________
¿Qué ajusto para la próxima? ______________

---

## Consejo de uso

La trampa más frecuente es diseñar actividades antes que la evidencia: primero escribe cómo sabrás que aprendieron, y recién entonces la secuencia. Y cuidado con el horario de la última tarde: si el cierre se cae por prisa, se cae también la evidencia —reserva los últimos 10 minutos como intocables. Evaluación y satisfacción son dos preguntas distintas: el "me encantó" no es logro (IA27).

---

*Plantillas · Ciclo: diseño instruccional · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla GOB7 — Política de protección (datos, imagen, IA y no daño)

**Ciclo:** inicio, antes de tocar personas o datos reales · **Universal:** cualquier proyecto con participantes · **Términos:** GOB7 (políticas de protección), Acta art. 7, consentimiento (GOB16)

---

## Para qué sirve

Las reglas no negociables del proyecto sobre **personas y sus datos**: qué información se recoge, con qué fin, quién la ve, qué nunca se hace. Se escribe una vez, se firma, y toda decisión posterior se mide contra ella. Evita el daño irreversible —los datos de una infancia no se borran—.

---

## Cómo completarla

**1. Qué información manejamos** (y para qué fin exacto):

- ______________________________________________________________________
- ______________________________________________________________________

*Fin declarado de cada dato:* ______________________________________________

**2. Qué NUNCA se hace (líneas rojas):**

- ☐ No se recoge dato de más "por si acaso" (minimización)
- ☐ No se usan perfiles automáticos o clasificaciones algorítmicas de personas
- ☐ No se comparte información con terceros sin autorización expresa
- ☐ No se publica imagen o voz sin consentimiento específico y revocable
- ☐ No se usan datos para comparar o clasificar a personas entre sí

**3. Quién custodia y quién accede.** Custodio: ______________ · Acceso: ______________ · Retención: ______________

**4. Qué hacer si algo se sale.** Detectado un uso indebido, se: ______________________________________________

**5. Revisión.** Esta política se revisa: ☐ semestral ☐ anual ☐ ante cualquier cambio de norma

**Firma:** ______________ *Fecha:* ____________

---

## Consejo de uso

Escríbela antes del primer formulario, no después del primer incidente. Y si tu proyecto usa plataformas externas, exige que también pasen este filtro: la herramienta gratis con datos de personas es una deuda, no una solución (ver `plataformas-fooss-de-gobernanza.md`).

---

*Plantillas · Ciclo: inicio · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla GOB8 — Código de conducta

**Ciclo:** inicio (con la firma del equipo) · **Universal:** cualquier equipo o proyecto · **Términos:** GOB8 (código de conducta), GOB35 (registro como condición), Acta arts. 6 y 9

---

## Para qué sirve

Lo que se espera del comportamiento de cada persona que participa —hacia el trabajo, entre pares y hacia las personas beneficiarias—, con su canal de reporte. Se firma con el equipo y se repite a cada persona nueva (inducción, GOB20). Evita que la convivencia dependa del carácter de los presentes.

---

## Cómo completarla

**1. Nuestros compromisos de trato** (marca los que el equipo adopta y ajusta los que falte):

- ☐ Tratamos con respeto siempre; el error propio y ajeno es información, no vergüenza
- ☐ Cero burlas, humillaciones y comparaciones entre personas
- ☐ Los límites se explican con razón; no se gobierna con amenazas
- ☐ Nadie trabaja expuesto: los problemas de una persona se manejan con privacidad
- ☐ Las diferencias se acomodan (ajustes razonables), no se exigen
- ☐ Las decisiones se discuten con datos y se firman con nombre

**2. Canal de reporte.** Si alguien vive o ve una conducta contraria a esto, ¿a quién lo dice? ______________ · Reserva: ☐ confidencial ☐ formal · Qué pasa después: ______________________________________________

**3. Consecuencias.** Las faltas se atienden con: ☐ conversación y acuerdo de cambio ☐ acción correctiva registrada ☐ (en caso grave) escalamiento a ______________
*Nunca se corrige con humillación pública ni con represalia.*

**4. Revisión con el equipo.** Cada ____ (meses/ciclo) se revisa este código con el equipo: ¿sigue siendo nuestro? ¿algo nos falta? Registro: ______________

**Firma del equipo:** ______________________________________________

---

## Consejo de uso

Un código que nadie lee es decoración: se lee al inicio, se cita cuando algo duele, y se revisa cuando el equipo cambia. La cláusula más importante es la del canal de reporte: si reportar es incómodo o no pasa nada, el código es papel mojado.

---

*Plantillas · Ciclo: inicio · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla GOB9 — Registro de decisiones, problemas y supuestos

**Ciclo:** transversal (desde el día uno) · **Universal:** cualquier proyecto · **Términos:** GOB9 (registro de decisiones), IG29 (trazabilidad), registro de supuestos y problemas

---

## Para qué sirve

La memoria formal de **qué se decidió, qué salió mal y en qué nos apoyamos**. Un solo registro con tres pestañas evita la conversación eterna de "¿y esto quién lo decidió?". Sin registro, la decisión no ocurrió (regla del proyecto); sin supuestos escritos, todo imprevisto parece sorpresa; sin problemas listados, se arrastran invisibles.

---

## Cómo completarla

**1. Decisiones.** *Formato: fecha relativa · decisión · quién aprueba · por qué (fuente).*

- ______________________ · ______________________ · ____________ · ______________________
- ______________________ · ______________________ · ____________ · ______________________
- ______________________ · ______________________ · ____________ · ______________________

*Regla: si cambia una decisión vieja, se anota aquí y se marca la entrada que sustituye.*

**2. Problemas abiertos** (ya pasó, no se ha resuelto).

- P ______________ *responsable:* ____________ *límite:* ____________ *estado:* ____________
- P ______________ *responsable:* ____________ *límite:* ____________ *estado:* ____________

**3. Supuestos que vigilamos** (si alguno cae, se re-planifica).

- S ______________ *¿cómo sabríamos que ya no es cierto?* ______________________
- S ______________ *¿cómo sabríamos que ya no es cierto?* ______________________

**4. Cierre mensual (tres preguntas).** ¿Alguna decisión sin efecto? ____________ ¿Algún problema sin dueño? ____________ ¿Algún supuesto desmentido? ____________

---

## Consejo de uso

Una entrada buena de decisión cabe en dos renglones. Si necesitas un párrafo para justificarla, probablemente no esté decidida todavía. Y el orden de lectura importa: quien llegue nuevo al proyecto debe poder recorrer el registro de arriba hacia abajo y entender cómo llegó hasta aquí sin preguntarle a nadie.

---

*Plantillas · Ciclo: transversal · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla GOB10 — Acta de reunión con acuerdos

**Ciclo:** transversal (cada reunión de gobernanza) · **Universal:** cualquier equipo · **Términos:** GOB10 (actas), GOB50 (reunión de decisión), GOB35 (registro como condición)

---

## Para qué sirve

El formato mínimo para que una reunión **cierre en decisiones y no en sensaciones**. Cinco minutos al final bastan para que, dos semanas después, nadie tenga dos versiones de lo acordado. Evita el antipatrón de la reunión sin decisión: hablar y salir sin cambiar nada.

---

## Cómo completarla

**Reunión de:** ______________________ *Fecha (relativa):* ____________ *Quién facilita:* ____________

**Presentes:** ______________________ **Ausentes (y por quién se enteran):** __________________

**1. ¿Es reunión de información o de decisión?** ☐ información (sólo se entera) ☐ decisión (se cierra hoy)

**2. Contexto mínimo** (sólo lo necesario para decidir — dos renglones):

______________________________________________________________________________

**3. Acuerdos y decisiones** (lo único que de verdad importa registrar):

- A1 ______________________ *responsable:* ____________ *fecha:* ____________
- A2 ______________________ *responsable:* ____________ *fecha:* ____________

**4. Puntos que quedaron abiertos** (y quién los trae la próxima): ______________________

**5. Información que se lleva cada quien** (para quién se enterará y cómo): ______________________

**Distribución:** ☐ al registro de decisiones (GOB9) ☐ al equipo ☐ al sponsor

---

## Consejo de uso

Si en el punto 1 marcaste "decisión" y el punto 3 quedó vacío, la reunión no terminó: sigue hasta que haya acuerdos con nombre y fecha. Y la regla de oro del acta buena: **cada acuerdo tiene un solo responsable** —"el equipo" no es responsable de nada, es el lugar donde los acuerdos se pierden.

---

*Plantillas · Ciclo: transversal · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla GOB15 — Informe de estado ejecutivo y de ciclo

**Ciclo:** periódico (estado) y de cierre (ciclo) · **Universal:** cualquier proyecto · **Términos:** GOB15 (informes de ciclo), GOB14 (tablero), GOB26 (semáforo), rendición de cuentas

---

## Para qué sirve

Un solo formato para **informar a quien decide y a quien espera resultados**, en dos modalidades: el **estado** (¿dónde vamos?) periódico y breve; y el **informe de ciclo** (¿qué cambió en el entorno y qué afecta al proyecto?) de cierre o de revisión legal/científica. Evita dos males: el informe que nadie lee (por largo) y el que nadie produce (por no tener forma).

---

## Cómo completarla

**Bloque A — Estado ejecutivo (una página, al cierre de cada período).**

*Período:* ____________ *Dirigido a:* ____________

**1. En una frase:** cómo va el proyecto. ______________________________________________

**2. Semáforo por indicador** (copiar los del tablero GOB14): indicador · estado (verde/ámbar/rojo) · avance desde el período anterior: ______________________________________________

**3. Riesgos en rojo o ámbar** (uno por línea, con su mitigación activa): ______________________________________________

**4. Decisiones que espera el lector** (si las hay): ______________________________________________

**5. Lo que se necesita de usted:** ______________________________________________

---

**Bloque B — Informe de ciclo (semestral o anual).**

*Tipo:* ☐ legal (norma cambió) ☐ científico (evidencia cambió) ☐ de fase (ciclo terminó)

*Qué cambió en el entorno:* ______________________________________________

*Qué documento o práctica del proyecto afecta:* ______________________________________________

*Acción que se abre (con responsable):* ______________________________________________

*Umbrales que se tocaron:* ______________________________________________

*Conclusión:* ☐ sin cambios ☐ enmienda menor ☐ requiere revisión mayor (revisión trienal)

---

## Consejo de uso

El bloque A tiene una página y se manda siempre con la misma periodicidad —la regularidad vale más que la extensión. Si un período no trae ninguna decisión que pedir ni ningún riesgo nuevo, escríbelo igual: el "todo tranquilo" documentado también es rendición de cuentas. Y nunca entres en detalle técnico que el lector no pidió: el ejecutivo decide con una frase, un semáforo y una petición.

---

*Plantillas · Ciclo: periódico y de cierre · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla GOB16 — Consentimiento informado

**Ciclo:** inicio, antes de capturar cualquier dato o imagen · **Universal:** cualquier proyecto con personas (especialmente niñas, niños y familias) · **Términos:** GOB16 (consentimiento), GOB7 (política de protección), Acta art. 7 y 26

---

## Para qué sirve

El permiso **específico, explicado, escrito y revocable** para usar datos, imagen o voz de una persona en el proyecto. En menores, lo da quien ejerce la patria potestad. Es el contrato de confianza que hace posible todo lo demás: sin él, el sistema pierde legitimidad con un solo uso indebido.

---

## Cómo completarla (versión para familias — lenguaje llano, sin letra chica)

**Proyecto:** ______________________ **Fecha:** ____________

**Para qué queremos usar sus datos o la imagen de su hijo/a** (elegir y explicar en una frase cada uno):

☐ Fotos o video **dentro del proyecto** (registrar avances y compartir con la familia): para ______________

☐ Publicar en sitio, red o exhibición **del proyecto**: para ______________

☐ Datos de participación y observación (registros del aula): para ______________

☐ Nada de lo anterior (sólo participación presencial)

**Qué NO haremos nunca:** vender o compartir sus datos con terceros sin permiso nuevo · usarlos para clasificar o comparar a su hijo/a · conservarlos más tiempo del necesario · darlos por hecho de forma permanente.

**Sus derechos:** sabe en qué lo usaremos · puede preguntar en cualquier momento · **puede retirar este permiso cuando quiera, sin consecuencia alguna** para su hijo/a en el proyecto (escribe o avisa a: ______________).

**Firma de quien ejerce la patria potestad:** ______________________ *Fecha:* ____________

**Si el niño o la niña es mayor y puede opinar:** también se le explica en su lenguaje y su opinión se registra: ______________________

---

## Consejo de uso

Este formulario se explica **en voz alta y en reunión**, no se entrega en una bolsa con más papeles. Si una familia no firma, su hijo/a participa igual de todo lo educativo: el consentimiento sólo regula datos e imagen, nunca el derecho a estar. Y si el uso cambia después (por ejemplo, se decide publicar), se firma **otro** consentimiento: el que no cubre eso no lo cubre nunca.

---

*Plantillas · Ciclo: inicio · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla GOB19 — Acuerdos con terceros

**Ciclo:** inicio, antes de que un tercero toque el proyecto o a sus personas · **Universal:** proveedores, colaboradores, voluntarios, visitantes, familias en rol especial · **Términos:** GOB19 (acuerdos), GOB16 (consentimiento), GOB8 (código aplicable)

---

## Para qué sirve

Cuando alguien de fuera entra al proyecto —un proveedor, un profesional invitado, un voluntario, una familia en rol de taller— hace falta un acuerdo claro: qué se espera de él, qué no puede hacer, qué recibe y cómo se resuelve un desacuerdo. Evita la dependencia verbal y las visitas sin reglas, que es como suelen entrar los problemas difíciles de arreglar.

---

## Cómo completarla

**Parte:** ______________________ **Rol:** ☐ proveedor ☐ colaborador ☐ visitante/experto ☐ voluntario
**Qué aporta:** ______________________ **Vigencia:** de ____________ a ____________

**1. Qué se compromete cada quien.**

*La parte externa se compromete a:* ______________________________________________

*El proyecto se compromete a:* ______________________________________________

**2. Límites.** Acceso a información: ☐ ninguna ☐ sólo la necesaria (cuál: ______________)
Acceso a personas menores: ☐ no aplica ☐ sólo con supervisión de ______________ y consentimiento vigente (GOB16)
Marca, propiedad intelectual y créditos: ______________________________________________

**3. Código aplicable.** La parte externa conoce y acepta: ☐ código de conducta (GOB8) ☐ política de protección (GOB7) — *fecha de entrega:* ____________

**4. Confidencialidad.** Compromiso de reserva sobre lo que vea o escuche: ☐ sí ☐ no aplica (cuando sí aplica, ¿harás falta NDA breve? ☐ sí → redactar anexo: ______________)

**5. Salida ordenada.** ¿Cómo se entregan materiales, accesos y avances al terminar? ______________________________________________

**6. Desacuerdos.** Primero: conversación con el responsable (__________) · después: escalamiento (__________) · marco aplicable: ______________________________________________

**Firmas:** ______________________ (externa) · ______________________ (proyecto)

---

## Consejo de uso

Cuanto más amistosa la relación, más importante es escribirlo: los acuerdos claros protegen la amistad, no la dañan. Y la casilla más olvidada es la de salida: todo acuerdo debe decir cómo termina, aunque no quiera terminarse —lo que no tiene salida escrita se convierte en permanencia por inercia.

---

*Plantillas · Ciclo: inicio · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla GOB20 — Manual de inducción y transferencia

**Ciclo:** continuo (se mantiene con cada cambio mayor) · **Universal:** cualquier proyecto que dependa de más de una persona · **Términos:** GOB20 (manual de inducción), GOB30 (versionado), IE39 (herencia y transferencia)

---

## Para qué sirve

Que alguien nuevo —o alguien que sustituye a otro— pueda operar el proyecto **sin el fundador y sin preguntas de leyenda**. Es la prueba suprema de un sistema sostenible: lo que sólo una persona entiende, todavía no es un proyecto. Se escribe temprano y se actualiza con cada cambio mayor; si se deja para "después", nunca se escribe.

---

## Cómo completarla

**1. Bienvenida y mapa.** Qué es este proyecto, para quién y por qué existe (dos párrafos):

______________________________________________________________________________

*Estructura de carpetas o espacio de trabajo:* ______________________________________________

*Documentos clave y dónde viven:* ______________________________________________

**2. Roles hoy.** Quién decide (sponsor): ____________ · Quién coordina: ____________ · Quién participa: ____________ · Quién es consultado: ____________

**3. Cómo se trabaja aquí (el ritmo).** Reuniones: ______________ · Decisiones: se toman en ______________ · Registro: en ______________ · Cambios: pasan por ______________

**4. Lo que no se toca sin permiso.** Políticas vigentes (GOB7, GOB8): ______________________________________________

**5. Primeros pasos de quien llega** (lista para ejecutar):

☐ Lee este manual y el acta (o su resumen) ☐ Recibe los accesos de ______________ ☐ Conoce al equipo en ______________ ☐ Lee un registro de decisiones reciente ☐ Acompaña una sesión antes de intervenir ☐ Firma su adherencia

**6. Estado del proyecto al día de hoy.** Versión: ______ · Fase: ______ · Decisiones recientes (últimas3): 1. ______________ 2. ______________ 3. ______________

**Actualización.** Última revisión: ____________ *Responsable:* ____________ *(se actualiza con cada cambio mayor registrado)*

---

## Consejo de uso

La parte que más se subestima es la 5: la inducción es una **lista que se ejecuta**, no un saludo. Y la 6 es la que impide que el manual mienta: un manual sin estado actualizado es una foto de alguien que ya se fue. Si tu proyecto cabe en una carpeta, este manual puede ser el README; si no cabe, es el mejor documento que puedes regalar a quien llegará después de ti.

---

*Plantillas · Ciclo: continuo · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla GOB22 — Presupuesto y autorizaciones

**Ciclo:** inicio (con el alcance) y control continuo · **Universal:** cualquier proyecto con gasto · **Términos:** GOB22 (presupuesto), GOB12 (historial), A5 (control de cambios)

---

## Para qué sirve

Cuánto dinero hay, en qué se va, quién autoriza cada gasto y qué pasa si se acaba. El dinero es una restricción real como cualquier otra: nombrarla a tiempo evita que el proyecto muera a media obra. Aplica igual a un proyecto con presupuesto institucional que a uno personal con recursos limitados.

---

## Cómo completarla

**1. Disponible.** Total aprobado: ____________ · Fuente: ____________ · Restringido a: ____________

**2. Comprometido y pendiente.** Ya comprometido: ____________ · Disponible: ____________

**3. Destinos del gasto** (principal, secundario y "lo que no se toca"):

Principal: ______________ *monto:* ________

Secundario: ______________ *monto:* ________

**Fondo de imprevistos:** ________ *(si no existe, créalo: un proyecto sin margen es un proyecto a la espera de un susto)*

**4. Autorizaciones.** Hasta ________ autoriza: ______________ · Por encima: ______________
*Regla: sin autorización registrada, no hay gasto (y sin gasto registrado, no hay presupuesto que valer).*

**5. Gastos realizados** (fecha relativa · concepto · monto · autorizó):

- ____________ · ______________ · ________ · ____________
- ____________ · ______________ · ________ · ____________

**6. Señal de alerta.** Si el disponible baja del ____% o hay gasto sin registrar → se revisa el alcance (A1) antes de seguir: ______________________________________________

---

## Consejo de uso

El error clásico es presupuestar sólo lo obvio y descubrir el costo de la formación, del tiempo y de los imprevistos en el camino. Reserva entre un 10 y un 15% para lo que no previste —y si el proyecto crece, crece el presupuesto o se mueve el alcance: nunca uno sin el otro (A5, control de cambios). Este documento es uno de los puestos como "pendiente explícito" en el Acta (art. 11): llenarlo es cerrar esa deuda de gobernanza.

---

*Plantillas · Ciclo: inicio y control · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla GOB25 — Escalera de decisión y delegación de autoridad

**Ciclo:** inicio (con el acta) y ante cada decisión incierta · **Universal:** cualquier equipo · **Términos:** GOB25 (escalera de decisión), GOB5 (RACI), GOB12 (control de cambios)

---

## Para qué sirve

Responde la pregunta que paraliza a los equipos: **¿quién decide esto?** Una escalera clara evita dos extremos: el cuello de botella de todo al sponsor, y la improvisación de quien no debería decidir. Se define al inicio, se cita cuando hay duda, y se revisa cuando el equipo cambia.

---

## Cómo completarla

**Nivel 1 — Decisión operativa (sin consultar).** Quién decide: ______________
*Ejemplos:* orden del día, formato de registro, elección de material entre los ya aprobados.
*Se comunica después, en la próxima reunión.*

**Nivel 2 — Decisión de equipo (consulta breve).** Quién decide con insumos del equipo: ______________
*Ejemplos:* cambios de secuencia, ajuste de actividades, uso del espacio.
*Se registra en el acta (GOB10).*

**Nivel 3 — Decisión de dirección (aprueba el sponsor).** Quién propone y quién aprueba: propone ______________ · aprueba ______________
*Ejemplos:* cambios de alcance, uso de recursos, acuerdos con terceros (GOB19).
*Se registra con control de cambios (GOB12).*

**Nivel 4 — Decisión estructural (cambia el marco).** Quién decide: ______________ (con el equipo y registro formal)
*Ejemplos:* acta, políticas, arquitectura del sistema, métricas maestras.
*Exige escrito, versión anterior conservada y difusión al equipo.*

**Regla de salto.** Si alguien debe saltar un nivel (urgencia), lo hace y **avisa por escrito en las siguientes 24 horas** —la urgencia justifica el salto, no el silencio.

**Mapa de escalamiento externo.** Con ______________ (rol) se escala cuando: ☐ hay desacuerdo de niveles ☐ hay riesgo materializado ☐ hay conducta contraria al código (GOB8).

---

## Consejo de uso

La escalera se pega en la pared (o en la primera página del manual) y se cita en voz alta cuando empiece la duda: "¿esto es nivel 1 o nivel 3?". Y cuidado con la tentación de subir todo al nivel 4 "por seguridad": eso no es rigor, es miedo con formato —y convierte al sponsor en cuello de botella y al equipo en espectador.

---

*Plantillas · Ciclo: inicio · v0.1*

```{=openxml}
<w:p><w:r><w:br w:type="page"/></w:r></w:p>
```

# Plantilla GOB51 — Caso de negocio y decisión Go / No-Go

**Ciclo:** inicio (antes del acta o del compromiso de recursos) · **Universal:** cualquier proyecto que exige inversión de tiempo o dinero · **Términos:** GOB51 (caso de negocio), GOB14 (línea base), decisión Go/No-Go

---

## Para qué sirve

Responder, antes de comprometer recursos, las tres preguntas incómodas: **¿vale la pena?, ¿podemos?, ¿debe ser ahora?** El caso de negocio reúne el valor esperado, el costo total y el riesgo; la decisión Go/No-Go es el sí, el no o el "no todavía" formal que evita que un proyecto arranque por inercia o por entusiasmo de una reunión.

---

## Cómo completarla

**1. El caso (una página, sin adornos).**

*Problema y quién lo padece:* ______________________________________________

*Si lo resolvemos, qué cambia (valor concreto):* ______________________________________________

*Si NO lo hacemos, qué pasa:* ______________________________________________

*Alternativa descartada y por qué:* ______________________________________________

**2. Costo total (no sólo el dinero).** Tiempo: ________ personas × ________ horas
Dinero: ____________ · Materiales/plataformas: ______________ · Atención directiva: ______________

**3. Valor esperado.** ¿Para quién? ______________ · ¿Cómo lo mediremos (indicador con línea base)? ______________
*(Si el proyecto es educativo o social: valor por beneficiario, no ROI monetario — medir impacto donde manda el propósito.)*

**4. Riesgos del sí.** Los dos que más pesan: 1) ______________ 2) ______________
*Mitigación mínima:* ______________________________________________

**5. Factibilidad.** Recursos: ☐ sí ☐ ajustados ☐ no · Personas: ☐ sí ☐ parcial ☐ no · Norma: ☐ compatible ☐ requiere ajuste · Momento: ☐ oportuno ☐ apurado ☐ prematuro

**6. DECISIÓN GO / NO-GO / NO TODAVÍA.**

☐ **GO** — con condiciones: ______________________________________________

☐ **NO-GO** — motivo: ______________________________________________

☐ **NO TODAVÍA** — lo que haría falta: ______________________ *fecha de revisión:* ____________

*Quién decide (según escalera GOB25):* ____________ · *Firma:* ____________

---

## Consejo de uso

El valor se escribe **desde el que lo va a vivir**, no desde quien lo propone: un caso de negocio que sólo enumera ventajas para el equipo es propaganda con hoja de cálculo. Y "no todavía" es una decisión madura, no un fracaso: la mayoría de los proyectos que se arrancan sin estar listos se arruinan por eso mismo, y el "no" temprano cuesta una conversación, mientras que el "sí" tarde cuesta el proyecto entero.

---

*Plantillas · Ciclo: inicio · v0.1*

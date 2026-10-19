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

# Glosario de Ingeniería (General)

## El vocabulario de la disciplina, como si te lo contara un colega — nivel 1 de 4

*Capa Ingeniería de la Educación · v0.1 · 28 de septiembre de 2026*
*Compañero: `compendio-ingenieria-general.md` · Prefijo: **IG***

**Cómo usarlo.** Este glosario no se lee de corrido: se consulta, se vuelve, se marca. Cada entrada te explica un término en palabras de todos los días, con un ejemplo pegado a la vida real, y te dice para qué te sirve. Los códigos (IG1, IG2…) existen para citar sin ambigüedad en el proyecto.

---

## A. Sistemas y modelos

**IG1 · Sistema.** Piensa en una orquesta: músicos, director, partituras, el tiempo que dura el concierto. Eso es un sistema, un conjunto de partes que trabajan juntas para un fin. El clima de afuera no es parte: es su entorno. Cuando un sistema falla, la gente grita al músico ruidoso; el pensamiento de sistema te hace otra pregunta: ¿está mal la pieza, la forma en que se coordinan, o el entorno? casi siempre arreglas más cambiando la relación entre las partes.

**IG2 · Subsistema y componente.** Todo sistema se parte en piezas más chicas hasta que ya puedes hacer, medir y arreglar algo concreto. En una casa: la cocina es un subsistema, y la resistencia del horno es un componente. Es la forma de no ahogarse: un problema enorme que se parte en partes manejables deja de ser amenaza y se vuelve tarea.

**IG3 · Interfaz.** El punto donde dos cosas se tocan y se pasan información o responsabilidad. El enchufe entre la pared y la lámpara. La entrega de una tarea entre aula y familia. Casi todos los fallos ocurren en las juntas, no en el centro: por eso las interfaces se especifican con cuidado y no se dejan a la buena voluntad improvisada.

**IG4 · Entrada, salida y retroalimentación.** Lo que entra al sistema, lo que sale y —la parte que lo hace inteligente— lo que regresa para corregirse. El termostato mide la temperatura y decide cuándo parar. Sin ese regreso, la casa se quema o se congela sin que nadie lo note a tiempo: un proyecto sin retroalimentación es un horno sin termostato.

**IG5 · Entorno.** Todo lo que rodea al sistema y lo condiciona sin que lo controle: el mercado para un negocio, la familia y el barrio para una escuela. Diseñar contra el entorno es una derrota cara; diseñar con él, anticipándolo y aprovechándolo, es la señal de madurez de cualquier sistema.

**IG6 · Modelo.** Una versión simple de la realidad que usas para razonar: un plano, un esquema, una lista. El plano de tu casa no trae el color de las cortinas, y está bien. Lo que no está bien es olvidar que lo dejaste fuera: todo modelo omite algo a propósito, y el bueno declara lo que omitió.

**IG7 · Abstracción.** Decidir qué detalles importan ahora y cuáles pueden esperar. Un mapa de metro no dibuja las calles, dibuja conexiones, que es lo que necesitas para moverte en tren. Elegir qué ignorar sin perder lo que importa es buena parte del arte de este oficio.

**IG8 · Frontera del sistema.** La línea que trazas entre lo que diseñas y lo que sólo consideras. En una boda, la lista de invitados está dentro; el clima ese día está fuera. Si metes el clima como requisito, te comprometes con algo imposible. Frontera mal trazada da requisitos imposibles y problemas sin dueño.

## B. Ciclo de vida y requisitos

**IG9 · Ciclo de vida.** El recorrido completo: problema, requisitos, diseño, construcción, verificación, validación, operación y mejora. Es lo mismo que hacer un plato nuevo para una cena importante: primero preguntas quiénes vienen y qué comen, luego buscas la receta, luego compras, pruebas el sazón, sirves, preguntan qué tal y anotas qué cambiarías. Saltarse pasos no ahorra tiempo: lo presta con intereses.

**IG10 · Requisito.** Lo que el sistema debe poder hacer, escrito de forma que se pueda comprobar. "Que sea amable" no es requisito: nadie sabe cómo probarlo. "Que una persona mayor complete el trámite en 5 pasos sin ayuda" sí lo es. Lo que no se puede verificar se vuelve discusión eterna; el requisito bien escrito ahorra años de conversaciones que no terminan.

**IG11 · Especificación.** El documento que fija requisitos y diseños con precisión suficiente para construir y para juzgar. Es la receta con medidas, tiempos y temperatura: sin ella, "un poco de harina" depende del humor de quien cocina. Sirve como contrato interno del equipo: lo que no está especificado, mañana se recordará distinto.

**IG12 · Levantamiento de requisitos.** Salir a preguntar y observar qué se necesita de verdad. Te piden "una app para pedir comida" y al entrevistar descubres que el problema era que los repartidores no saben a qué puerta ir. El problema pedido casi nunca es el problema real, y esta fase humilde es la más barata de todo el ciclo.

**IG13 · Verificación frente a validación.** Verificar es preguntar: ¿lo hice conforme a lo que prometí? Validar es preguntar: ¿era esto lo que realmente necesitaban? Entregaste el pastel con los números correctos, verificado; pero era para un cumpleañeros alérgico al huevo y llevaba huevo, no validado. Puedes cumplir tu promesa al ciento por ciento y seguir fallando a la gente.

**IG14 · Modelo en V.** El ciclo dibujado como V, donde cada etapa de diseño se enfrenta con su etapa de verificación: requisitos contra prueba de aceptación, diseño contra prueba de integración. No esperas al final de la obra para probar si los cimientos aguantan: los pruebas el día que los haces. Encontrar el error tarde es caro; verificar temprano es barato.

**IG15 · Iteración.** Ciclos cortos de diseñar, probar, medir y ajustar, para cuando el problema todavía no se entiende bien. Haces una sesión, la pruebas con el grupo, corriges y sigues. Es la humildad hecha método: tu primera idea es una hipótesis, no un oráculo.

**IG16 · Prototipo.** Una versión parcial hecha para aprender, no para entregar. La maqueta de cartón antes de la pared de verdad; la sesión piloto antes del curso completo. El prototipo barato evita el error caro. Y si no cambia nada tras medirlo, sólo fue un gasto con buena cara.

**IG17 · Criterio de aceptación.** La condición explícita y comprobable que dice cuándo algo está terminado y correcto: "la reunión queda lista cuando hay acta con decisiones y responsables", no "cuando se sintió productiva". Sin criterio, "ya quedó" es opinión con fecha; con criterio, la conversación sobre calidad se vuelve posible y corta.

**IG18 · Línea base.** La medición del estado inicial antes de intervenir: pesarse antes de la dieta, contar cuántas crisis había por semana antes del programa. Sin ella sólo hay opinión: no puedes demostrar avance, sólo contarlo.

## C. Calidad y verificación

**IG19 · Calidad.** Cumplir lo acordado, con pocos defectos y dentro de tolerancia. No es "el mejor pastel del mundo": es el pastel que pedí, bien hecho y a tiempo. Calidad es la promesa escrita y verificable, no el "quedó más o menos bien" de pasillo. Lo perfecto es un espejismo que agota equipos y retrasa obras.

**IG20 · Defecto y falla.** El defecto es la imperfección en el producto; la falla es cuando se manifiesta en el uso. Un tornillo mal apretado es defecto; la estantería que cae con la lluvia es falla. Se puede vivir con defectos latentes; lo que hay que prevenir es la falla en el momento crítico, y en educación ese momento siempre involucra personas.

**IG21 · Causa raíz.** Seguir preguntando "¿y por qué?" hasta llegar a algo que sí puedas arreglar. El niño "no atiende"; quizá no durmió; quizá hay ruido en casa; y así hasta donde sea actionable sin invadir la vida familiar. Corregir sólo el síntoma es reprogramar la falla para el miércoles que viene.

**IG22 · Prueba y muestreo.** Verificación sistemática; cuando probar todo es imposible o invasivo, se muestrea con criterio y no al azar perezoso. Aplicado a personas hay una regla mayor: probarlo todo en niñas y niños no es rigor, es irresponsabilidad. Se verifica en situaciones seguras y acordadas.

**IG23 · Tolerancia y margen.** La capacidad de resistir variación sin fallar: un puente calculado para más peso del que pasará un día cualquiera. En sistemas humanos se traduce en holguras reales, tiempos y descansos. Trabajar siempre al límite no es eficiencia: es un accidente a punto de ocurrir.

**IG24 · Capacidad de proceso (Cp/Cpk).** Qué tan estable es un proceso dentro de sus límites permitidos: una máquina que produce piezas casi iguales tiene alta capacidad. Mide el proceso, no a la persona, y por eso nunca se aplica a seres humanos como si fueran piezas. Sí sirve para preguntarnos si nuestro proceso de enseñanza es estable.

## D. Gestión y configuración

**IG25 · Alcance.** Qué se entrega y qué no: "pintamos la sala, techo y paredes; no el marco de la puerta". Es la paz entre las partes; sin él, cada conversación amenaza con crecer y el proyecto muere de sobredosis de buenas ideas.

**IG26 · Deriva de alcance.** La ampliación silenciosa de lo que se hace, sin que nadie la decidiera: "como ya estábamos, agreguemos también el jardín". Es el modo en que proyectos sanos se enferman. Se combate con control de cambios: todo aumento pasa por la pregunta de quién lo aprueba y qué se mueve para caber.

**IG27 · Control de cambios.** El proceso formal para modificar algo ya aprobado: quién propone, quién aprueba, qué impacta, qué versión queda. Sin él, los cambios pasan por el canal de "a mí se me ocurrió", que no deja rastro ni responsables.

**IG28 · Configuración y versionado.** Saber exactamente qué versión de cada pieza está viva, con fecha y dueño. La carpeta donde conviven "borrador", "final" y "final-final" es el caos; el versionado es saber que la v3 firmada es la oficial. Te permite reconstruir qué se sabía y qué se decidió en cualquier momento.

**IG29 · Trazabilidad.** Poder rastrear una decisión hasta su origen. Si alguien pregunta por qué esta pared está acá, abres el plano y ves: porque la luz entra por acá y el niño duerme allá. Es el antídoto contra la pregunta más cansadora de los proyectos: "¿y esto por qué está así?".

**IG30 · WBS (estructura de desglose del trabajo).** Partir el trabajo en paquetes pequeños y verificables. "Organizar la exposición" es opaco; "elegir obras, preparar cartelas, montar muros, invitar familias" ya es accionable. Si algo no se puede descomponer, es que todavía no se entiende.

**IG31 · RACI.** Quién resuelve, quién aprueba, quién consulta y quién se entera. En la mudanza: el hermano elige, el papá aprueba el presupuesto, la mamá consulta, la abuela se entera. Cierra el vacío más caro del trabajo en equipo: "creía que lo hacías tú".

**IG32 · Riesgo frente a problema.** Un riesgo puede pasar y se mitiga anticipándose: "podría llover el día de la mudanza". Un problema ya pasó: "está lloviendo y se mojó el sofá". Los equipos maduros trabajan los riesgos antes de tener problemas; vivir apagando incendios no es intensidad, es falta de anticipación.

**IG33 · Registro de riesgos.** La lista viva de riesgos con probabilidad, impacto, mitigación y disparador. Se revisa en ciclo, no se archiva tras el taller de motivación: un registro que nadie mira es un diario de deseos.

**IG34 · Hitos y DoD.** Los hitos son puntos de control sin duración ("el Analítico aprobado"); el DoD son las condiciones que dicen cuándo algo está de verdad terminado. El proyecto avanza por condiciones cumplidas, no por fechas transcurridas: las fechas llegan, las condiciones se construyen.

**IG35 · Partes interesadas.** Las personas o grupos afectados o con influencia: en una escuela, niñas y niños, familias, docentes, dirección, autoridad, vecinos. Mapearlas temprano evita el descubrimiento tardío de quien tenía derecho a decir que no, y ese descubrimiento suele llegar el día de la entrega.

## E. Patrones y arquitectura

**IG36 · Patrón.** Una solución que ya funcionó ante un problema que se repite, con nombre propio. "El maestro modela antes de pedir" es un patrón: se repite, funciona y se puede nombrar en una palabra. Con nombre, lo enseñas, lo repites y lo corriges; sin nombre, cada generación vuelve a inventar la rueda con entusiasmo y sin eje.

**IG37 · Antipatrón.** Una forma recurrente que parece solución y produce daño. "Regañar fuerte delante de todos para que aprendan" parece disciplina y enseña sólo a no ser descubierto. Nombrarlo es el primer paso para dejar de cometerlo: en este proyecto hay un catálogo entero en `neurogestion-patrones-y-antipatrones.md`.

**IG38 · Arquitectura.** Las decisiones estructurales que cuesta mucho dar marcha atrás: dónde va la escalera, no el color de la cortina. Por eso se escriben como decisiones registradas y no viven en la costumbre. Si viven en la costumbre, dentro de dos años nadie sabrá por qué están ahí y alguien las va a querer "mejorar".

**IG39 · Deuda técnica.** El costo futuro de lo que simplificamos hoy a propósito: dejar el cableado simple para entregar más rápido, sabiendo que después habrá que rehacer la pared. Se puede usar si es consciente y con plan de pago; negarla es cómo los proyectos sanos se enferman.

**IG40 · Acoplamiento y cohesión.** El acoplamiento mide cuánto dependen las partes entre sí: mejor si poco. La cohesión mide cuánto hace cada parte una sola cosa: mejor si mucho. Si cambiar la cortina obliga a rehacer la ventana, hay acoplamiento malo. Los sistemas buenos son piezas que hacen una cosa bien y no se arrastran unas a otras cuando algo falla.

**IG41 · Redundancia.** Duplicar lo crítico para sobrevivir fallas: dos llaves del generador; en proyectos, un suplente del rol clave y la documentación viva. No es duplicar trabajo rutinario, eso es desperdicio; es asegurar que la ausencia de una persona no apague el sistema.

**IG42 · Resiliencia (ingenieril).** Tres cosas distintas y valiosas: robustez (resiste el golpe), recuperación (vuelve después del golpe) y resiliencia (funciona distinto, pero funciona). El árbol que se dobla con el huracán y sigue dando fruta. Los sistemas humanos necesitan las tres, y en educación la recuperación se diseña con apoyo, no con la orden de "párate solo".

## F. Ética y límites

**IG43 · No daño (ingeniería).** La restricción previa a cualquier optimización. No se ahorra en refuerzo sísmico para invertir en la fachada. Cuando el sistema toca personas, esta regla manda siempre: es uno de los dos rieles del oficio.

**IG44 · Competencia declarada.** No se diseña ni se verifica fuera de lo que se domina; se consulta o se deriva. El electricista no regla la tubería, aunque sea su casa. Reconocer el límite no quita autoridad: la da, y separa a la ingeniería de la improvisación con confianza.

**IG45 · Seguridad por diseño.** La seguridad se diseña en la arquitectura, no se agrega al final: las salidas de emergencia se piensan en el plano, no cuando ya hay humo. Añadida después cuesta órdenes de magnitud más, y casi nunca funciona del todo.

**IG46 · Fallo seguro (fail-safe).** El estado por defecto que protege a las personas cuando el sistema falla: la puerta que se abre sola si se corta la luz, el freno que responde sin electricidad. Todo sistema que toque cuerpos o decisiones de otros necesita su presupuesto de fallo pensado antes de que falle.

**IG47 · Humildad de modelo.** Declarar los supuestos y el margen de cada modelo usado para decidir: "esta proyección asume que no hay crisis; si la hay, se cae". La certeza sin supuestos es ignorancia con formato, y en proyectos es la más peligrosa porque nadie la discute.

**IG48 · Ética de la métrica.** Lo que se mide orienta: si premias la cantidad de fichas, tendrás fichas apuradas y aprendizaje flojo. Elegir indicadores es elegir conductas, por eso todo indicador se revisa por su efecto colateral, no sólo por su número.

**IG49 · Documentación viva.** La documentación es parte del sistema, no su decoración: el manual que nadie actualiza y que contradice a la máquina que cambiaron hace un año. Si la documentación miente, el sistema se administra con leyendas, y las leyendas no resuelven fallas.

**IG50 · Mejora continua con constancia.** Cada mejora deja registro de qué cambió, por qué y con qué evidencia: el cuaderno de recetas donde escribes "más canela, menos azúcar" en lugar de "queda mejor la próxima" mental. Sin constancia, la mejora es sólo anécdota de una buena semana.

---

## Índice

**A. Sistemas y modelos**: Sistema (IG1) · Subsistema y componente (IG2) · Interfaz (IG3) · Entrada, salida y retroalimentación (IG4) · Entorno (IG5) · Modelo (IG6) · Abstracción (IG7) · Frontera del sistema (IG8). **B. Ciclo de vida y requisitos**: Ciclo de vida (IG9) · Requisito (IG10) · Especificación (IG11) · Levantamiento de requisitos (IG12) · Verificación frente a validación (IG13) · Modelo en V (IG14) · Iteración (IG15) · Prototipo (IG16) · Criterio de aceptación (IG17) · Línea base (IG18). **C. Calidad y verificación**: Calidad (IG19) · Defecto y falla (IG20) · Causa raíz (IG21) · Prueba y muestreo (IG22) · Tolerancia y margen (IG23) · Capacidad de proceso (IG24). **D. Gestión y configuración**: Alcance (IG25) · Deriva de alcance (IG26) · Control de cambios (IG27) · Configuración y versionado (IG28) · Trazabilidad (IG29) · WBS (IG30) · RACI (IG31) · Riesgo frente a problema (IG32) · Registro de riesgos (IG33) · Hitos y DoD (IG34) · Partes interesadas (IG35). **E. Patrones y arquitectura**: Patrón (IG36) · Antipatrón (IG37) · Arquitectura (IG38) · Deuda técnica (IG39) · Acoplamiento y cohesión (IG40) · Redundancia (IG41) · Resiliencia (IG42). **F. Ética y límites**: No daño (IG43) · Competencia declarada (IG44) · Seguridad por diseño (IG45) · Fallo seguro (IG46) · Humildad de modelo (IG47) · Ética de la métrica (IG48) · Documentación viva (IG49) · Mejora continua con constancia (IG50).

---

*Capa Ingeniería de la Educación · Glosario IG (50 términos) · v0.1 · Abierto por diseño.*

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

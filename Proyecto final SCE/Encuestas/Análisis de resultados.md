# Análisis exploratorio de la encuesta SCE

## ¿Qué se analizó?

Se leyeron los diez campos abiertos de 194 envíos en la [copia anonimizada](<Respuestas anonimizadas.xlsx>). La pestaña **Preguntas** conserva el cuestionario. Esta lectura identifica problemas y solicitudes para discutir el alcance; no constituye una medición de rendimiento ni una estimación estadística de prevalencia.

Los ejemplos siguientes son **paráfrasis** de celdas concretas. Para consultarlos, filtrar la pestaña **Respuestas** por ID y leer la columna P indicada. No se publican datos demográficos ni se relacionan los IDs con personas.

## Necesidades que vale la pena discutir

| ID de hallazgo | Evidencia en la copia pública | ¿Qué expresa el testimonio? | Propuesta para analizar | Responsables relacionados |
|---|---|---|---|---|
| H01 | `R-1AC44D861D`, P1 y P10; `R-9C0CF89188`, P1 | Dificultad para ver y seleccionar elementos desde el celular, comparada con computadora. | Definir tareas y tamaños de pantalla para evaluar navegación y presentación; preparar wireframes. No se fija un umbral arbitrario. | Todos; coordinación de interfaz por acordar. |
| H02 | `R-9C0CF89188`, P2 y P4; `R-186C0DCA17`, P2 y P10 | Cruces de horario, información de cupo que cambia y falta de vista previa de la selección. | Acordar cómo se consulta oferta, se valida traslape y se confirma el cupo; distinguir escasez real de plazas frente a información desactualizada. | E2, E4, E5; E3 como fuente docente. |
| H03 | `R-1AC44D861D`, P4; `R-A717CB703E`, P4 | Se reportan interrupciones o pérdida de la selección durante la reinscripción. | Describir flujo alternativo y resultado esperado al fallar una confirmación; estudiar vigencia de sesión y continuidad del proceso. Las causas están por verificar. | E1, E2 y coordinación de calidad. |
| H04 | `R-6F8F41E9AC`, P3; `R-19B366344C`, P10 | Dificultad para localizar salones y la información del horario. | Definir dónde se muestra cada dato y cuál módulo lo produce; relacionar grupo, materia, docente y aula. | E2, E3, E4, E5. |
| H05 | `R-19B366344C`, P5; `R-186C0DCA17`, P5 | La información de exámenes se recibe por profesores o redes; se solicita claridad sobre aulas. | Acordar consulta del calendario de exámenes y responsable de actualización. Los avisos adicionales necesitan acuerdo de alcance. | E5 y E6; consumidores E1/E3. |
| H06 | `R-BA84E6EB33`, P7; `R-276D908BE9`, P7 | Algunos envíos reconocen estados visibles o un apartado de estatus. Otros manifiestan desconocimiento. | Investigar qué trámites tienen seguimiento y qué estados significan; no afirmar que nunca existe seguimiento. | Responsable del trámite; coordinación por acordar. |
| H07 | `R-19B366344C`, P9; `R-6F8F41E9AC`, P9 | Se solicitan constancias, trayectorias, pagos o documentos en línea para evitar traslados. | Registrar como solicitudes adicionales y decidir cuáles caben en los módulos actuales. No crear nuevos módulos sin acuerdo. | Representantes de todos los equipos y docente. |
| H08 | `R-7E6D0A47C9`, P4; `R-19B366344C`, P6 | Se relatan demoras de pagos o captura de resultados que afectan trámites o evaluaciones. | Validar reglas y fuentes con administración; distinguir registro académico, pago y elegibilidad. | E6 y responsables institucionales; pago fuera de asignación actual por aclarar. |

## Evidencia que limita una conclusión uniforme

- `R-BCF9D421B7`, P1: valora la interfaz como intuitiva y fácil de utilizar, aunque propone mejorar su presentación en P10.
- `R-508A33D1FE`, P1–P4: declara facilidad de uso y no haber experimentado las dificultades consultadas.
- `R-A717CB703E`, P3 y P10: expresa claridad de información y no propone un cambio, pese a describir inconvenientes de reinscripción en otra respuesta.
- `R-5AAF777CE0` contiene varias respuestas de “no me ha ocurrido”. No equivalen automáticamente a aprobación de todas las funciones ni a ausencia probada de fallas.
- `R-F946DEA863` contiene cadenas sin significado interpretable. `R-CD3F1CA21E` contiene respuestas muy breves y ambiguas. Se conservan y deben recibir una decisión de codificación explícita antes de cualquier conteo temático.

No se excluyeron relatos por ser positivos, negativos, ambiguos o poco útiles. La selección de ejemplos busca mostrar necesidades y contraejemplos; **no es un ranking de frecuencia**.

## Límites del estudio

1. **Unidad y cobertura:** se cuenta un envío, no una identidad única validada. No consta un muestreo probabilístico, tasa de respuesta ni cobertura de carreras o planteles; no se extrapola al conjunto del alumnado.
2. **Preguntas abiertas con ejemplos:** P2 menciona expresamente cupos y cruces de horario; P3 menciona materias, horarios, salones y calificaciones. Las menciones pueden estar influidas por esos ejemplos. No se interpretan como prioridades espontáneas sin esa aclaración.
3. **Autorreporte:** los relatos no verifican la causa de un cierre de sesión, la capacidad de servidores, el código de una aplicación o la normativa de un trámite. En particular, `R-7F4128948F`, P4, afirma un problema de HTTPS que no se comprobó técnicamente.
4. **Heterogeneidad:** algunos envíos describen grupos elegidos por alumnos y otros asignados por coordinación. No debe imponerse un único proceso a todos los espacios académicos sin delimitar el sistema propuesto.
5. **Instrumento y fuentes:** la encuesta consulta experiencia estudiantil. No permite determinar por sí sola permisos de administradores, estructura del registro docente o reglas oficiales de evaluación. La anonimización limita además los cruces demográficos.
6. **Cuantificación pendiente:** no se calculan porcentajes temáticos porque aún no se ha acordado ni aplicado un código de categorías con tratamiento de negaciones, ambigüedades y respuestas múltiples. El total de 194 no es un denominador automático para cualquier afirmación.

## ¿Cómo convertir estos hallazgos en trabajo con propósito?

| Paso | Producto y criterio |
|---|---|
| Validar la necesidad | Para cada H, reunir IDs, pregunta y una paráfrasis que respete el testimonio; contrastar con otras fuentes cuando sea institucional o técnico. |
| Acordar el alcance | Determinar qué módulo atiende el problema, cuáles consultan sus datos y qué solicitudes quedan fuera. |
| Proponer el requisito | Dar ID, actor, condición, resultado esperado y relación con el hallazgo; marcarlo como propuesta hasta revisarlo. |
| Precisar datos y flujos | Identificar datos de entrada, salida, reglas, permisos y alternativas; coordinar con los módulos afectados. |
| Modelar y revisar | Producir modelos que representen las mismas decisiones; mantener fuente UML e imagen según plantilla. |

Si después se requieren frecuencias, acordar primero las categorías, unidad de codificación, denominadores, exclusiones y revisión de casos ambiguos. Una codificación por palabras clave, por sí sola, no distingue “no he tenido cruces” de “he tenido cruces”.

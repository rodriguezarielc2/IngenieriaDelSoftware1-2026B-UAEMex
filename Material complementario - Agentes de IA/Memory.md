# Memory.md — Memoria del proyecto final

La memoria conserva decisiones del proyecto con su fuente y estado. No reemplaza el template vigente ni convierte una propuesta de clase en una decisión final del equipo.

## Estado de las decisiones

Usa estas etiquetas al registrar información:

- **Confirmado en clase:** se indicó explícitamente en una sesión.
- **Confirmado por el usuario:** decisión de organización o trabajo solicitada expresamente; no implica aprobación del grupo o del docente.
- **Verificado en archivos/repositorio:** hecho comprobado en la versión y fecha que se indican; volver a consultar si puede haber cambiado.
- **Propuesto o por validar:** se discutió como posible solución, módulo o necesidad, pero su incorporación final requiere confirmación.
- **Pendiente:** se identificó trabajo que todavía debía completarse.
- **Ejemplo:** sirve para explicar un concepto y no se aplica al sistema escolar sin una decisión explícita.

Anota la fecha o número de clase y distingue siempre la instrucción del docente de la inferencia del agente. Agrega entradas nuevas al final; si una instrucción posterior cambia una anterior, conserva el antecedente y marca cuál está vigente.

## Contexto confirmado del proyecto

### Clase 13 — 2 de octubre de 2026

- El proyecto común trata de un sistema de control escolar organizado por módulos y documentado en Markdown dentro de GitHub.
- La distribución inicial asignó seis módulos: alumnos; inscripciones; profesores; asignaturas y materias; calendario de exámenes; y registro de calificaciones.
- El producto debía ser integrado: los equipos acuerdan las entradas, procesos, salidas e intercambios entre módulos. Cada integrante debe conocer y explicar el sistema completo.
- La estructura inicial del documento contemplaba introducción, objetivo, requisitos funcionales y no funcionales, módulos, datos de entrada y salida, interacciones y propuestas de mejora.
- Las contribuciones en GitHub y la comprensión individual del proyecto forman parte de la evaluación descrita en esa clase.

### Clase 15 — 14 de octubre de 2026

- El análisis de información debe preceder a la definición de soluciones. Se mencionaron entrevistas, encuestas o cuestionarios, grupos focales, análisis documental, observación, muestreo y triangulación.
- Al revisar las dependencias de los módulos, se identificó la posible necesidad de periodos escolares, grupos y aulas, y un catálogo de exámenes. Esta ampliación debe contrastarse con el módulo final aprobado por el equipo y el docente.
- Los problemas atribuidos al sistema actual —como saturación, exceso de pasos o falta de claridad— se trataron como hipótesis que requieren evidencia, no como hechos comprobados.

### Clase 20 — 4 de noviembre de 2026

- El alcance, los actores y los requisitos deben ser coherentes entre módulos. Se observó que autenticación e inicio de sesión son funciones comunes y se propuso manejarlas como un módulo o servicio compartido.
- No atribuyas una función a un módulo sin justificar su responsabilidad y sus dependencias.

### Clase 21 — 11 de noviembre de 2026

- Se definieron requisitos de nivel 0 para el sistema completo, nivel 1 para módulos y nivel 2 para el detalle de funciones o procesos. La sesión indicó profundizar como máximo hasta nivel 2.
- El README general debía servir de índice y contener la vista general, el contexto y los requisitos de nivel 0; cada módulo debía enlazarse y documentarse por separado.
- La plantilla revisada solicitó actores y funciones, casos de uso, componentes, secuencias, estados y clases, además de tablas generales de actores, roles y permisos.
- En esa sesión se indicó que el diccionario de datos, el diagrama relacional y la estructura global todavía debían completarse. Este estado corresponde a lo registrado entonces; verifica el repositorio y las instrucciones actuales antes de presentarlo como pendiente.

## Puntos que requieren verificación

- La lista inicial de seis módulos se amplió durante el análisis y la autenticación se trató como función transversal. No uses el listado inicial como catálogo definitivo sin revisar la organización más reciente.
- La clase 19 registró una instrucción sobre diagramas de actividad y secuencia por caso de uso; la actualización de la clase 21 menciona componentes y secuencia. Sigue el template vigente y señala la discrepancia si todavía no se resolvió.
- Los diagramas y funciones de la aplicación de credenciales de las clases 16–19 son ejemplos didácticos, no requisitos del proyecto escolar.
- Los materiales de clase deben mantener descripciones visuales breves y anonimizadas en lugar de incorporar capturas originales. Esta regla para apuntes no impide crear los diagramas que el proyecto final requiera, sujetos a su formato vigente y legibilidad.

## Registro de decisiones nuevas

Agrega aquí criterios confirmados por el docente o por el equipo, con fecha, alcance, excepción y fuente. No registres como decisión un supuesto del agente.

### Clase 22 — 13 de noviembre de 2026

**Estado:** confirmado en clase, registrado en esta memoria el 19 de noviembre.\
**Fuente:** [transcripción y resumen de clase 22](<../Clase 22 - Datos, metadatos y reglas del proyecto - 2026-11-13/README.md>).\
**Alcance:** documentación de cada módulo y coherencia del modelo de datos general.

- Se pidió definir el dato principal, sus metadatos y las reglas o condiciones de validación por módulo, y complementar el diagrama entidad-relación general.
- Se deben justificar los campos y distinguir identificadores internos de datos visibles como la matrícula.
- La generación/activación de matrícula y la clasificación de “recursos” no quedaron resueltas de manera inequívoca en la fuente. Permanecen como acuerdos por validar; no inventar responsables ni reglas definitivas.

### Clase 23 — 18 de noviembre de 2026

**Estado:** confirmado en clase, registrado en esta memoria el 19 de noviembre.\
**Fuente:** [transcripción y resumen de clase 23](<../Clase 23 - Patrones de análisis - 2026-11-18/README.md>).\
**Alcance:** integración documental y revisión de aportaciones.

- Se reiteró completar módulos y README, atender observaciones de PR y mantener una presentación homogénea en Markdown.
- Los diagramas deben acompañarse de código fuente UML e imagen. El estado actual de un PR debe consultarse en GitHub; la mención oral de aceptados o rechazados no lo prueba.
- Se trataron patrones de análisis, técnicas de negocio/sistemas/objetos/datos y reusabilidad. Los ejemplos didácticos no agregan por sí mismos nuevas funciones al SCE.
- La clase se preparó a partir de TXT y collage; la transcripción no se cotejó contra audio. Las capturas originales no se publicaron y los nombres de participantes se omitieron en la transcripción de consulta.

### Organización del trabajo — 19 de noviembre de 2026

**Estado:** confirmado por el usuario y verificado en los archivos publicados previamente.\
**Fuentes:** acuerdos de este chat y [Proyecto final SCE](<../Proyecto final SCE/README.md>).\
**Alcance:** repositorio personal de materiales y propuestas; no sustituye decisiones del grupo.

- El repositorio personal es `rodriguezarielc2/IngenieriaDelSoftware1-2026B-UAEMex`. La carpeta `Proyecto final SCE/` contiene plan, diagnóstico, pautas, evidencia y paquetes de cambios propios.
- La entrega oficial se integra en `wichis/26b_is1_proyecto-final`, rama `develop`. El análisis inicial se refiere al commit `553104011ece92aeeeecfe54298173bfb88e102f`; consultar la rama actual antes de actuar sobre ella.
- El usuario eligió conservar enlaces y versión de origen sin publicar un espejo completo de los documentos del profesor. Esta decisión sustituye la idea inicial de copiar una instantánea a la carpeta personal.
- Las clases permanecen en carpetas de la raíz. La clase 23 puede citarse en las fuentes del plan, pero no debe aparecer como entregable en el índice de `Proyecto final SCE/`.
- Las tareas se proponen según la distribución de `teams-info.md`. Los responsables de actividades compartidas y la fecha oficial siguen por confirmar. El E3 no se convierte automáticamente en coordinador de todo el proyecto.

### Encuesta y propuestas preparadas — 19 de noviembre de 2026

**Estado:** verificado en los archivos de esta preparación; la aceptación de las propuestas está pendiente.\
**Fuentes:** [encuesta y método](<../Proyecto final SCE/Encuestas/README.md>), [paquetes de cambios](<../Proyecto final SCE/Propuestas de cambios/README.md>) y publicación [1144095](https://github.com/rodriguezarielc2/IngenieriaDelSoftware1-2026B-UAEMex/commit/11440957582fd62ad28c30c334f62c3b1a710834).\
**Alcance:** preparación documental y evidencia exploratoria.

- Se publicó una copia anonimizada de 194 envíos con diez respuestas abiertas por envío. No se verificó que cada envío corresponda a una persona distinta. El análisis es exploratorio; no fija prevalencia, causas técnicas ni umbrales de calidad.
- El original identificable y la correspondencia privada entre filas e IDs quedan fuera del repositorio. Las omisiones y generalizaciones se explican en el método de anonimización. No reincorporar los datos retirados.
- Se prepararon PR-001 (índice), PR-002 (problemas con evidencia) y PR-003 (datos de Profesores). Son identificadores locales de paquetes; no son PR enviados al profesor ni cambios integrados en el repositorio oficial.
- El diagnóstico y el plan conservan sus decisiones pendientes y dependencias. Antes de modificar un módulo o enviar una aportación, revisar allí qué necesita acuerdo con otros equipos y comprobar los PR actuales.

### Corrección de presentación y continuidad — 19 de noviembre de 2026

**Estado:** confirmado por el usuario; aplicado a las instrucciones y los documentos de esta actualización.\
**Fuentes:** correcciones de este chat, [README del proyecto](<../Proyecto final SCE/README.md>), [pautas](<../Proyecto final SCE/Pautas de presentación.md>) y [entrada para IA](../AGENTS.md).\
**Alcance:** presentación de la carpeta y memoria compartida de este repositorio.

- El usuario primero pidió reducir la saturación del README. La versión reducida a propósito e índice, publicada en [16079da](https://github.com/rodriguezarielc2/IngenieriaDelSoftware1-2026B-UAEMex/commit/16079dabd7b7354b234a27808edbc2c326f27663), resultó demasiado escueta y fue rechazada como presentación suficiente. La pauta vigente es un punto medio: contexto del proyecto, organización, documentos y orientación breve para colaborar, evitando repetir el plan.
- Se solicitó mantener actualizada la memoria del material complementario. Al cerrar trabajo relevante, registrar decisiones/correcciones confirmadas, avances comprobados y pendientes con fecha, estado, fuente y alcance. Conservar antecedentes y no añadir entradas de relleno.
- `AGENTS.md` en la raíz remite al manual y a esta memoria para su lectura al comenzar. Las herramientas que no leen instrucciones del repositorio automáticamente requieren que se les proporcione esa entrada; no afirmar que cualquier IA lo hará por sí sola.
- Las pautas de presentación siguen siendo una propuesta común sujeta a acuerdo del grupo; la plantilla e indicaciones vigentes del docente tienen prioridad.

**Siguiente paso útil:** revisar con los equipos el plan y los tres paquetes, aceptar responsables y resolver las decisiones de alcance/datos necesarias antes de preparar los modelos y los envíos oficiales. No hay evidencia en este registro de que esos acuerdos ya se hayan tomado.

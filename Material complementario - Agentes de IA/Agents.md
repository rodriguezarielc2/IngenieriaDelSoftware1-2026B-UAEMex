# Agents.md — Agente de IA para el proyecto final

## Rol

Apoya el análisis y la documentación del proyecto final de Ingeniería de Software I: un sistema integrado de control escolar. Trabaja con las fuentes disponibles, ayuda a mantener coherencia entre módulos y prepara documentación que el equipo pueda revisar y defender.

Este agente no presupone que deba programar o desplegar el sistema. Su tarea principal, de acuerdo con las clases registradas, es contribuir al análisis, los requisitos, los modelos y la documentación del proyecto. Solo implementa software si el usuario lo solicita y define el alcance.

## Inicio de cada sesión

El punto de entrada es [AGENTS.md de la raíz](../AGENTS.md). Antes de planear o editar, leer este manual y [Memory.md](Memory.md); después, los documentos pertinentes del encargo. Para el proyecto SCE, consultar su [README](<../Proyecto final SCE/README.md>) y las [pautas de presentación](<../Proyecto final SCE/Pautas de presentación.md>). No es necesario releer todas las clases para una tarea que no las utiliza.

Si la herramienta no carga instrucciones de repositorio automáticamente, el usuario debe proporcionarle el archivo de entrada o pedirle que lo lea. La presencia de `AGENTS.md` no garantiza que cualquier IA lo consulte por sí sola.

## Fuentes y prioridad

1. Las instrucciones más recientes del docente y el template vigente del proyecto.
2. Las transcripciones originales de las clases pertinentes.
3. Los resúmenes y archivos `Contexto complementario.md` de cada clase.
4. `../README.md` y `Memory.md`, como contexto de trabajo.
5. Conocimiento general de ingeniería de software, solo para explicar conceptos; nunca para inventar requisitos de la asignatura.

Si dos fuentes discrepan, señala la diferencia y sigue la instrucción vigente. Si no se puede determinar cuál está vigente, pregunta antes de cerrar el diseño.

## Reglas de trabajo

- Separa lo **confirmado**, lo **propuesto**, lo **pendiente** y lo que aparece solo como **ejemplo**.
- Pregunta cuando falte información necesaria; no inventes actores, funciones, reglas de negocio, datos, permisos, módulos ni criterios de calidad.
- Trata las quejas sobre el sistema actual como hipótesis hasta que una entrevista, encuesta, observación o documento las respalde.
- No conviertas los ejemplos de otras clases —como la aplicación de credenciales— ni los ejemplos del video sobre agentes —presupuestos de reformas y recorridos 3D— en requisitos del sistema escolar.
- Mantén separados el contexto general del sistema, las decisiones de cada módulo, la memoria de decisiones y los archivos propios de cada proyecto.
- Protege los datos de estudiantes y otras personas. Usa datos ficticios o anonimizados en ejemplos y documentos de trabajo.
- Escribe la documentación en español claro y en Markdown, salvo que el template vigente indique otra cosa.
- Revisa puntuación, tildes y signos de interrogación/exclamación de apertura y cierre en español de México, incluidos títulos y tablas. No añadas signos a las interrogativas indirectas. Las correcciones puntuales de transcripciones deben conservar las palabras y señalarse como revisión de puntuación; no equivalen a cotejo contra audio. Las respuestas de encuesta se conservan literales.
- No afirmes que un archivo se actualizó, que un diagrama es correcto o que una habilidad fue validada sin comprobarlo.

## Estructura del agente

- **Contexto:** descripción de la materia y fuentes del proyecto disponibles en este repositorio.
- **Skills:** procedimientos como `Skills/documentar-modulo-control-escolar/SKILL.md`.
- **Memoria:** decisiones y dudas registradas en `Memory.md`, conservando su fuente y estado.
- **Proyectos:** documentos y datos de cada módulo o versión del proyecto, en su repositorio designado.

La carpeta `GiitHub` contiene materiales de clase. No asumas que es el repositorio de entrega del proyecto final: antes de crear o modificar documentos de módulos, identifica el repositorio o carpeta que el usuario indique.

La ubicación acordada para la planeación y las propuestas propias es `Proyecto final SCE/`, dentro de este repositorio. La entrega oficial se integra en `wichis/26b_is1_proyecto-final`, rama `develop`. Se enlazan los documentos oficiales y se registra su versión; el usuario decidió no publicar un espejo completo de esos documentos.

Las clases permanecen en carpetas de la raíz. La memoria y la documentación de referencia pueden citarlas por su contenido; no se agregan como entregables al índice de `Proyecto final SCE/`.

## Flujo

1. Lee las instrucciones de entrada, este manual y la memoria; después el README de la tarea y las fuentes pertinentes.
2. Identifica el módulo, la versión del template y las fuentes que justifican el trabajo.
3. Aplica la habilidad correspondiente. Registra en memoria solo decisiones con fuente y alcance claros.
4. Revisa entradas, procesos, salidas, actores y dependencias con los módulos relacionados.
5. Entrega los archivos en la ubicación acordada, enlázalos desde el índice cuando corresponda y reporta preguntas abiertas.
6. No hagas commits, pushes ni publicaciones sin una petición explícita para esa operación.

## Presentación y continuidad

El README del proyecto debe dar contexto suficiente para que una persona nueva entienda propósito, organización y forma de colaborar. Evita los dos extremos señalados por el usuario: repetir el plan completo o reducirlo a un índice sin explicación. Los detalles se desarrollan en sus documentos y se enlazan desde la entrada.

Al redactar propuestas y módulos, seguir las pautas comunes. Las instrucciones de formato de los apuntes de clase se conservan por separado. Las reglas comunes son una propuesta de coordinación hasta que el grupo las acuerde; no deben atribuirse al profesor.

## Mantenimiento de la memoria

El usuario autorizó mantener actualizada la memoria del proyecto al cerrar trabajo relevante. No hace falta volver a solicitar esa actualización en cada sesión. Registrar únicamente información que ayude a continuar:

- Decisiones y correcciones explícitas del usuario o del docente, indicando quién las confirmó.
- Cambios y comprobaciones realizados, con enlaces a los archivos o commits que los respaldan.
- Acuerdos pendientes, responsables por confirmar y el siguiente paso útil.

Cada entrada debe indicar **fecha, estado, fuente y alcance**. Diferenciar **Confirmado por el usuario**, **Confirmado en clase**, **Verificado en archivos/repositorio**, **Propuesto o por validar** y **Pendiente**. Una petición individual del usuario no equivale a un acuerdo de todo el grupo.

Agregar registros al final y conservar la historia. Si una decisión se sustituye, señalar cuál la reemplaza. Mantener las explicaciones extensas en los documentos correspondientes y enlazarlas. No almacenar datos personales de encuestas, credenciales ni transcripciones completas en la memoria. Para hechos cambiantes, registrar el corte de verificación y volver a consultar la fuente antes de actuar.

Antes de cerrar, comprobar que la memoria describe lo realmente realizado y que sus enlaces abren. Una propuesta escrita no es una aprobación del equipo, un PR enviado ni una integración oficial. Actualizar la memoria tampoco autoriza por sí solo un commit, push o envío externo.

## Mejora a partir del trabajo

Al abordar por primera vez un tipo de tarea, resuélvelo con las fuentes y reglas disponibles. Después de recibir correcciones, separa las decisiones propias de ese módulo de los criterios que aplican a tareas repetibles. Registra las decisiones confirmadas en `Memory.md`; cuando se autorice ajustar un procedimiento repetible, actualiza la habilidad correspondiente. Distingue entre un procedimiento documentado y uno aplicado y comprobado. No afirmes que el agente aprendió o quedó validado por haber editado estos archivos.

# Clase 22: Datos, metadatos y reglas del proyecto final

### 1️⃣ 📘 Identificación

- **Tema principal:** definición de los datos y reglas de los módulos del proyecto integrador de control escolar.
- **Subtemas y actividades:** revisión del examen; coherencia y coordinación entre módulos; definición de recursos; datos, metadatos, identificadores y condiciones; relaciones entre alumnos, materias, inscripciones y aulas; diagrama entidad-relación; uso crítico de herramientas de inteligencia artificial.
- **Propósito de aprendizaje:** documentar cada módulo con suficiente precisión para que sus datos, reglas y relaciones sean entendibles, consistentes y defendibles.

### 2️⃣ 📝 Resumen explicativo

La sesión comenzó con la revisión de algunos conteos y calificaciones del examen. Se pidió comprobar los aciertos de las secciones objetivas y revisar las respuestas abiertas. El profesor comentó que distintas formas de organizar una idea podían ser válidas, pero pidió mayor precisión al explicar los conceptos.

Después se retomó la evaluación del proyecto final. La revisión sería por equipos y cada integrante tendría que responder preguntas sobre el proyecto integrado, no únicamente sobre el módulo que le tocó. La documentación debe ser consistente entre módulos; por ejemplo, las decisiones de acceso y seguridad deben considerar autenticación, autorización, roles y permisos de forma congruente. También se pidió que los equipos revisaran sus commits, resolvieran conflictos de integración y avanzaran hacia un primer borrador común.

Se insistió en que el proyecto debe explicar qué problema resuelve, cuáles son sus límites y por qué incluye cada requisito. Se mencionaron los requisitos funcionales y no funcionales, el contexto del sistema y los diagramas de casos de uso y secuencia. La explicación relacionó el nivel 0 con el sistema completo y el nivel 1 con sus módulos.

Al revisar el módulo de aulas, se cuestionó qué significaba “recursos disponibles”. Se propusieron ejemplos como proyectores, controles y computadoras, y se señaló que el proyecto debe definir y clasificar esos recursos. También se discutió si conviene tratarlos como parte de aulas o como un módulo aparte. Los datos de un aula —por ejemplo, nombre, ubicación, capacidad o equipamiento— deben incluirse cuando apoyen una necesidad del sistema. El equipo debe explicar por qué un campo sería obligatorio u opcional y bajo qué condiciones se asignaría.

La conversación pasó a las relaciones entre módulos. Para alumnos se mencionaron nombres, apellidos y matrícula; para materias, nombre, modalidad y ubicación; para aulas, nombre, ubicación e identificador. La inscripción relaciona al alumno con una materia. Se distinguió la matrícula visible para las personas de los identificadores internos que permiten relacionar entidades en una base de datos. La generación de la matrícula se discutió entre distintos roles y apartados del proyecto, pero la transcripción no deja una decisión final inequívoca sobre quién la activa ni cómo debe quedar expresada en el caso de uso.

Como ajuste a la documentación, se pidió agregar en cada módulo una definición del dato principal, sus metadatos y las reglas o condiciones que deben cumplir. Por ejemplo, no basta con incluir “fecha de nacimiento”: hay que especificar el tipo de dato y el formato esperado. También se comentó que nombres y fechas pueden requerir reglas de representación compatibles con distintos contextos; la sesión no eligió un estándar concreto.

Para integrar los módulos, se pidió complementar el diagrama entidad-relación del sistema con las entidades, atributos e identificadores acordados. Las relaciones deben permitir que los equipos compartan una estructura de datos coherente. En particular, las decisiones locales de un módulo deben revisarse frente a las necesidades de los módulos que consumen su información.

La sesión también relacionó el análisis de requisitos con el uso de inteligencia artificial. El profesor describió herramientas capaces de producir planes, modelos y software a partir de instrucciones. La habilidad enfatizada fue especificar bien la necesidad y evaluar críticamente el resultado: una respuesta generada debe comprobarse, porque puede omitir requisitos o interpretar de otra forma una descripción ambigua. También se habló de agentes que intercambian resultados y de adaptar el lenguaje técnico al dominio del usuario.

### 3️⃣ 🧩 Conceptos teóricos y técnicos relevantes

- **Dato:** entidad o elemento principal que el módulo estudia y administra, como alumno, aula, materia o inscripción.
- **Metadatos:** información que describe las propiedades del dato; para un alumno pueden ser nombre, apellidos, matrícula y fecha de nacimiento.
- **Reglas o condiciones:** especificaciones que determinan qué valores son válidos, qué campos son obligatorios y cómo se captura o relaciona la información.
- **Identificador interno:** clave utilizada para distinguir y relacionar registros dentro del sistema. Se diferenció de la matrícula, que tiene significado para quienes consultan los datos.
- **Diagrama entidad-relación:** modelo que representa las entidades, sus atributos y las relaciones entre ellas para organizar los datos del sistema.
- **Autenticación y autorización:** conceptos de seguridad mencionados al revisar la coherencia de inicio de sesión, roles y permisos entre módulos.
- **Niveles del modelo:** se habló del nivel 0 para el sistema completo y del nivel 1 para sus módulos.
- **Commit y conflicto de integración:** cambios registrados en el repositorio y discrepancias que el equipo debe resolver al combinar aportaciones.
- **Agentes de inteligencia artificial:** herramientas que pueden encadenar tareas y pasar resultados entre agentes; sus resultados requieren revisión humana frente a los requisitos.

### 4️⃣ ⚠️ Problemas, errores o aclaraciones del profesor

- “Recursos” era demasiado amplio para usarlo sin definición. El equipo debe precisar qué incluye, cómo se clasifica y si corresponde al módulo de aulas o a uno separado.
- No deben agregarse campos solo porque parezcan útiles: cada dato obligatorio u opcional debe justificarse por el propósito del sistema y sus reglas.
- La generación de la matrícula quedó como decisión por acordar: la transcripción discute el rol responsable y el lugar donde documentar el caso de uso, pero no fija una solución única.
- Las relaciones entre módulos no deben depender de nombres ambiguos ni contradecir el modelo general. Hay que distinguir los identificadores internos de los datos que tienen significado para el usuario.
- Se compararon distintas representaciones de fechas y nombres, pero no se seleccionó un formato o estándar definitivo. El proyecto debe especificar sus reglas sin dar por resuelta esa decisión.
- Los conflictos de integración y las definiciones diferentes entre equipos pueden producir un sistema inconsistente; deben revisarse en el contexto del conjunto.
- Se corrigieron conteos del examen durante la sesión. Las respuestas abiertas podían expresarse de distintas maneras, pero se pidió cuidar la precisión conceptual.

### 5️⃣ 🧠 Conclusión de la clase

El proyecto final debe explicar qué representa cada dato, cuáles son sus metadatos y qué condiciones se aplican, además de mostrar cómo se relaciona con los demás módulos. Se pidió complementar el diagrama entidad-relación y la estructura documental, integrar los cambios del equipo y resolver conflictos de colaboración. La revisión del proyecto considerará que cada integrante pueda argumentar el sistema completo; las herramientas de inteligencia artificial pueden apoyar el trabajo, pero sus resultados deben contrastarse con los requisitos. La fecha del ordinario se corrigió durante la sesión a 10 de diciembre y se mencionó que podía ajustarse; conviene confirmar el aviso vigente del docente.

### 6️⃣ ✅ Síntesis final

Cada módulo debe definir su dato principal, metadatos y reglas de validación.
Los campos y recursos se justifican por las necesidades y límites del sistema.
El diagrama entidad-relación debe conectar los módulos con identificadores coherentes.
El equipo debe integrar sus cambios y poder explicar el proyecto completo.
La inteligencia artificial apoya el análisis, pero sus resultados requieren revisión.

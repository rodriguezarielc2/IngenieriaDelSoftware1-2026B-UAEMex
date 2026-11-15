# Ingeniería de Software I — UAEMex, 2026B

Materiales de apoyo para estudiar y trabajar los temas de la asignatura.

## Descripción de la materia

Ingeniería de Software I estudia cómo transformar una necesidad real en una solución de software bien planteada. Para ello, primero se analiza el problema y el contexto donde ocurre: quiénes participan, qué procesos existen, qué información se necesita, qué recursos están disponibles y qué límites o restricciones debe respetar el sistema. La materia promueve justificar las decisiones con información y necesidades identificadas, en lugar de comenzar directamente por una solución técnica.

En los materiales disponibles hasta la clase 22 se desarrollan varios ejes relacionados:

- **Sistemas y organizaciones:** componentes, entradas, procesos, salidas, retroalimentación, límites y relación con el entorno; también se estudian sistemas de información dentro de las organizaciones.
- **Procesos de software:** ciclo de vida, modelos de desarrollo y enfoques iterativos. Se revisan prácticas y marcos como Scrum, Kanban y DevOps.
- **Análisis y requisitos:** recopilación de información, entrevistas, identificación de usuarios y necesidades, definición del alcance, requisitos funcionales y no funcionales, viabilidad y criterios de calidad.
- **Diseño y modelado:** representación de actores, procesos, datos, componentes y comportamiento mediante casos de uso y diagramas de contexto, flujo de datos, clases, secuencia, estados y actividades. También se trabaja la definición de entidades, metadatos, reglas de datos y relaciones entre módulos para el proyecto de control escolar.
- **Verificación y colaboración:** pruebas y aspectos de calidad como rendimiento y disponibilidad, organización modular del trabajo y uso de control de versiones para coordinar e integrar aportaciones. Se enfatiza revisar la consistencia de los módulos y evaluar críticamente los resultados de herramientas de inteligencia artificial.

En conjunto, la asignatura busca desarrollar la capacidad de analizar antes de diseñar, comunicar necesidades con claridad, expresar una solución mediante requisitos y modelos, considerar su calidad y restricciones, y colaborar en su integración. Esta descripción se basa en los materiales disponibles hasta la clase 22 y no sustituye el programa oficial ni las instrucciones vigentes del docente.

## Proyecto final: sistema de control escolar

El proyecto final consiste en analizar y documentar en equipo un sistema integrado de control escolar. El trabajo parte de comprender el problema, su contexto y las necesidades de sus usuarios; después se delimitan el alcance y las exclusiones, se especifican requisitos y se representan la información, los procesos y las relaciones entre los módulos. El sistema sirve como caso común para aplicar los temas de análisis, requisitos, modelado, organización y colaboración vistos en la asignatura.

### Módulos y coordinación

La distribución inicial de clase asignó seis módulos: alumnos, inscripciones, profesores, asignaturas y materias, calendario de exámenes y registro de calificaciones. En el análisis posterior también se discutió la necesidad de periodos escolares, grupos y aulas, un catálogo de exámenes y autenticación compartida. Por tanto, la lista inicial no debe tomarse como el catálogo definitivo: el equipo debe confirmar la organización vigente con el repositorio del proyecto y las indicaciones más recientes del docente. Cada módulo tiene responsabilidades propias, pero el producto debe funcionar como un sistema homogéneo: los equipos deben identificar qué información intercambian, cómo se relacionan sus procesos y qué dependencias existen entre módulos. Por ello, cada integrante debe poder explicar el propósito general del sistema y la interacción entre módulos, no solo la parte asignada a su equipo.

### Documentación del proyecto

Las indicaciones registradas hasta la clase 22 plantean mantener el trabajo en un repositorio común de GitHub y documentarlo en Markdown. El README principal funciona como entrada e índice del sistema: presenta el problema, los objetivos, el contexto general y los requisitos de nivel 0, además de enlazar la documentación de los módulos. En cada módulo se detallan sus actores, funciones, casos de uso, requisitos de nivel 1 y modelos pertinentes; el análisis puede profundizar hasta el nivel 2. Entre los modelos solicitados para describir los módulos se mencionan diagramas de componentes, secuencia, estados y clases, además de casos de uso y tablas de actores, roles y permisos. En la clase 22 se pidió precisar, por módulo, el dato principal, sus metadatos y las reglas o condiciones aplicables, así como complementar el diagrama entidad-relación general.

La colaboración también forma parte del proyecto: los cambios se integran mediante commits y pull requests, y la documentación de cada módulo debe quedar enlazada desde el índice común. La evaluación considera tanto las aportaciones registradas como la capacidad individual de explicar y justificar decisiones del sistema completo.

La estructura del entregable sigue evolucionando. En la clase 21 se anticiparon el diccionario de datos y el diagrama relacional; en la clase 22 se solicitó agregar por módulo la definición del dato, sus metadatos y sus reglas o condiciones, además de completar el diagrama entidad-relación general. Esta sección resume indicaciones de las clases 13, 21 y 22; para preparar la entrega se debe revisar la versión más reciente del formato y las instrucciones del docente.

## Materiales

- Las transcripciones están dentro de la carpeta de su clase.
- Cuando existe, `Contexto complementario.md` amplía los temas tratados en esa sesión.

## Recursos para agentes de IA

Archivos configurados para apoyar el proyecto final de control escolar, aplicando la separación entre instrucciones, memoria y habilidades sin convertir los ejemplos del video en requisitos del sistema:

- [Manual del agente del proyecto final](<Material complementario - Agentes de IA/Agents.md>)
- [Memoria del proyecto final](<Material complementario - Agentes de IA/Memory.md>)
- [Habilidad para documentar un módulo de control escolar](<Material complementario - Agentes de IA/Skills/documentar-modulo-control-escolar/SKILL.md>)

## Nota de lectura

Las transcripciones pueden contener errores de reconocimiento o fragmentos incompletos. El contexto complementario sirve como apoyo y no sustituye la transcripción ni convierte los ejemplos de clase en requisitos oficiales del proyecto.

# Contexto de Ingeniería de Software I

## 1. 📘 Identificación

Este documento organiza el contexto de las clases 1–21 para orientar el trabajo posterior sobre los materiales y la forma de presentarlos. Se basa en las 21 transcripciones `.txt` incluidas en esta copia y en las notas de contexto complementario ubicadas en las carpetas correspondientes. El orden se tomó del número de clase; las fechas se conservan solo cuando aparecen en el nombre de la carpeta (clases 5–21).

El eje de la materia es analizar problemas y organizaciones como sistemas, levantar y especificar necesidades, diseñar modelos, construir soluciones por módulos y comprobarlas. El proyecto que se va perfilando en las sesiones es un sistema de control escolar.

## 2. 📝 Recorrido explicativo

### Clases 1–4: introducción y pensamiento sistémico

- **Clase 1 — Organización del curso:** dinámica del curso, entregas y participación. Se insiste en que el trabajo debe poder demostrarse con evidencia y en analizar el problema antes de asumir que ya está resuelto.
- **Clase 2 — Sistemas y datos responsables:** sistemas, software y manejo responsable de datos. Se propone usar datos ficticios para probar sistemas en vez de recopilar datos personales reales sin necesidad.
- **Clase 3 — Panorama de la asignatura:** panorama de unidades y vocabulario de la materia; conecta el análisis de sistemas, sus componentes y los problemas que el software busca resolver.
- **Clase 4 — Teoría general de sistemas:** teoría aplicada a organizaciones y software: entradas, transformación, salidas, retroalimentación, límites, entorno y subsistemas. También aparecen relaciones y cardinalidades que luego se conectan con bases de datos. Se recalca que una respuesta de IA necesita análisis humano.

### Clases 5–9: clasificación y análisis del problema

- **Clase 5 — Clasificación de sistemas:** propiedades, atributos y clasificación de sistemas; ejemplos de información, aplicaciones y restricciones de un sistema.
- **Clase 6 — Sistemas de información:** sistemas usados en organizaciones, con ejemplos como TPS, CRM e inteligencia de negocios; entradas, salidas, usuario, diseño e interfaz.
- **Clase 7 — Ciclo de desarrollo:** ciclo de desarrollo de software y sus fases; diferencia entre requisitos funcionales y no funcionales; se comenta el modelo en V y la verificación y validación.
- **Clase 8 — Problema de horarios:** formulación del problema de asignación de horarios: profesores, aulas, horas disponibles e hipótesis. La clase pasa de una percepción general del problema a identificar variables y restricciones.
- **Clase 9 — Modelado de horarios:** continúa el análisis con datos, relaciones entre variables y escenarios; se discute cómo las restricciones cambian el resultado del sistema.

### Clases 10–12: procesos y metodologías

- **Clase 10 — Procesos de software y DevOps:** inicia la unidad II, sobre modelos de procesos y metodologías de desarrollo. Se conectan análisis, diseño, desarrollo, pruebas, despliegue y mantenimiento, y se explica la automatización de despliegues con DevOps.
- **Clase 11 — Requisitos, viabilidad y pruebas:** documentos del análisis, especificación de requisitos y viabilidad; tipos de pruebas, incluidas pruebas de rendimiento, carga y resistencia; se asigna investigar y exponer frameworks.
- **Clase 12 — Scrum y Kanban:** metodologías ágiles, trabajo iterativo e incremental, sprints, valor para el cliente, mejora continua y coordinación entre desarrollo y pruebas.

### Clases 13–21: proyecto, colaboración y modelado

- **Clase 13 — Proyecto de control escolar:** organización de equipos y del proyecto; módulos que deben comunicarse, estándares de comunicación y uso de GitHub para observar aportaciones individuales.
- **Clase 14 — Git y GitHub:** integración de cambios: commits, push, pull requests y resolución de conflictos entre cambios de varios integrantes.
- **Clase 15 — Análisis de información:** recolección de información antes de proponer requisitos o soluciones; se aterriza el análisis al control escolar y sus módulos.
- **Clase 16 — Entrevistas y calidad:** cuestionarios y entrevistas abiertas para conocer la experiencia de usuarios; atributos de calidad del sistema y cálculo de disponibilidad, por ejemplo 99.9 % y 99.999 %.
- **Clase 17 — Casos de uso y contexto:** vista externa de la organización y diagramas de casos de uso: actores, límite del sistema y asociaciones. Se enfatiza presentar el producto con términos que el usuario entienda.
- **Clase 18 — Flujos, clases y componentes:** diagramas de contexto y flujo de datos por niveles 0, 1 y 2; diagramas de clases y componentes, relaciones, visibilidad y multiplicidad. Se comparan ejemplos de componentes y módulos.
- **Clase 19 — Diagramas de comportamiento:** modelado dinámico mediante diagramas de secuencia, máquina de estados y actividades; se relaciona el comportamiento del sistema con los flujos que sigue el usuario.
- **Clase 20 — Organización y requisitos:** repaso del modelado dinámico y avance a modelos organizacionales. Se revisan organigramas, una plantilla de requisitos para un módulo de alumnos y un diagrama de aulas.
- **Clase 21 — Organización y proyecto final:** modelos de organización y organigramas, incluidos modelos lineales, por proyecto y funcionales. La sesión cierra la unidad III y anticipa una unidad IV breve enfocada en el proyecto final.

### Hilo conductor del proyecto

El caso parte de problemas de control escolar, en particular la asignación de horarios y recursos. Las sesiones llevan ese planteamiento hacia la investigación con usuarios, la delimitación del alcance, la definición de requisitos y la separación del sistema en módulos. Después se practican modelos de interacción, estructura y organización, junto con trabajo colaborativo en GitHub. El criterio recurrente es justificar las decisiones con necesidades y evidencia, no solo con una solución técnica.

## 3. 🧩 Conceptos técnicos que se repiten

- **Sistemas:** entradas, procesos, salidas, retroalimentación, límites, entorno y subsistemas.
- **Requisitos:** funcionales y no funcionales; alcance, actores, necesidades del usuario y viabilidad.
- **Proceso de software:** planificación, análisis, diseño, construcción, pruebas, despliegue y mantenimiento; modelos predictivos y ágiles; DevOps.
- **Calidad:** pruebas unitarias, integración y rendimiento; disponibilidad expresada con porcentajes y tiempo de interrupción.
- **Modelado:** casos de uso, contexto y flujo de datos, clases, componentes, secuencia, estados, actividades y organigramas.
- **Colaboración:** módulos con contratos de comunicación, commits, pull requests, integración y conflictos de cambios.

## 4. ⚠️ Aclaraciones y puntos por confirmar

- Las transcripciones tienen repeticiones, frases fragmentadas y posibles errores de reconocimiento. Los términos técnicos dudosos deben comprobarse contra el material original antes de corregirlos como si fueran seguros.
- Hay una diferencia en la cantidad de entrevistas: la clase 16 menciona seis personas por estudiante; la clase 17 menciona diez personas por estudiante, manteniendo diez preguntas abiertas. Conviene confirmar cuál instrucción quedó vigente antes de usarla como requisito del proyecto.
- Los ejemplos de modelado de las clases 17–21 sirven para practicar; no se deben tratar todos como entregables o requisitos oficiales del proyecto.
- Cuando una clase incluye contexto complementario, este se encuentra dentro de su carpeta y amplía la transcripción sin sustituirla.
- Las clases 1–4 no tienen fecha en el nombre de archivo. No se les asigna una fecha por inferencia.

## 5. 🧠 Conclusión

Hasta la clase 21, el curso avanza desde fundamentos de sistemas y análisis de problemas hacia metodologías, levantamiento de requisitos, colaboración y modelado de una solución. La unidad III termina con modelos organizacionales; según esa sesión, la siguiente unidad se concentra en integrar lo aprendido en el proyecto final.

## 6. ✅ Síntesis final

La secuencia va del problema y sus usuarios a requisitos, modelos y módulos.
El caso de trabajo es un sistema de control escolar.
GitHub se usa para colaborar e identificar aportaciones al proyecto.
Las transcripciones contienen incertidumbre que debe conservarse hasta verificarla.
La unidad IV queda orientada al proyecto final, según la clase 21.

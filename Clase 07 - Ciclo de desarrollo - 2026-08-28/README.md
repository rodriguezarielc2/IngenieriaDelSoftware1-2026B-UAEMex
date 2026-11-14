# Clase 07 — Ciclo de desarrollo

### 1️⃣ 📘 Identificación

- **Tema principal:** modelos del ciclo de vida del software y herramientas para analizar, diseñar, construir y operar sistemas.
- **Subtemas y actividades:** requisitos funcionales y no funcionales; cascada, iterativo, incremental, espiral y ágil; roles de equipo; verificación y validación; herramientas de colaboración, diseño, código, pruebas y despliegue; análisis de una aplicación de contraseñas.
- **Propósito:** comparar formas de organizar un proyecto de software y aplicar los conceptos del ciclo de vida al análisis de un sistema existente.

### 2️⃣ 📝 Resumen explicativo

**Fases y requisitos.** Se repasaron planificación, análisis, diseño, construcción, pruebas, despliegue y mantenimiento. La planificación estima alcance, objetivos, tiempo, costos y personas. El análisis establece qué requiere el usuario y qué condiciones técnicas debe cumplir el sistema. Los requisitos funcionales describen acciones y servicios; los no funcionales expresan condiciones como disponibilidad, rendimiento y compatibilidad. El curso se enfocaría hasta el análisis y diseño, dejando la construcción y operación para una continuación.

**Modelos de ciclo de vida.** En cascada se avanza de manera secuencial y cada etapa depende de cerrar la anterior; se presentó como opción para proyectos pequeños y bien delimitados, y lenta para trabajos grandes. El modelo iterativo repite etapas y mejora el sistema en ciclos; el incremental divide el alcance en partes que se entregan progresivamente. El modelo espiral también repite ciclos, con énfasis en prototipos y revisión de riesgos. Los enfoques ágiles organizan entregas y colaboración en ciclos cortos. Se comentaron roles como Product Owner, Scrum Master, desarrolladores, testers, DBA y líderes técnicos, además del valor de comunicarse entre áreas.

**Verificación y validación.** Se comparó lo que se construyó con lo solicitado mediante listas de comprobación. La clase usó la imagen de varias personas interpretando de manera distinta la solicitud de un columpio para mostrar que una instrucción ambigua puede producir resultados diferentes. El análisis y la comunicación con usuarios y equipo deben reducir esas diferencias antes de construir.

**Herramientas.** Se mencionaron plataformas de gestión y documentación (Jira, Confluence), control de versiones (Git y servicios como GitHub, GitLab y Bitbucket), modelado (UML y herramientas de diagramación), editores y entornos de desarrollo, pruebas (unitarias, funcionales y de API) y automatización de integración y despliegue (por ejemplo, GitHub Actions y Jenkins, junto con contenedores). La IA puede generar código y pruebas, pero una persona debe revisar el resultado con conocimiento del sistema.

**Análisis de la aplicación.** El grupo examinó una aplicación móvil para guardar contraseñas. Se identificaron posibles entradas (credenciales, categorías, notas, direcciones web e importación de respaldos) y salidas (listados, favoritos, consulta, exportación y copia al portapapeles). También se discutieron el generador de contraseñas, la base de datos, el entorno Android, la compatibilidad y los límites del sistema. El propósito del ejercicio era analizar lo que hace la aplicación en su contexto, no responder con definiciones generales desconectadas del producto.

### 3️⃣ 🧩 Conceptos teóricos y técnicos relevantes

- **Modelo en cascada:** flujo secuencial entre fases; cambios tardíos pueden exigir regresar a etapas anteriores.
- **Modelo iterativo:** repite el ciclo de trabajo para revisar y mejorar la solución.
- **Modelo incremental:** entrega partes funcionales del alcance en versiones sucesivas.
- **Modelo espiral:** organiza ciclos de desarrollo y prototipos con atención a riesgos.
- **Métodos ágiles:** trabajo colaborativo en entregas breves y adaptables.
- **Verificación:** comprobar que el producto corresponde a especificaciones y diseño.
- **Validación:** comprobar que la solución satisface la necesidad de los usuarios.
- **Product Owner y Scrum Master:** roles que ayudan a priorizar necesidades y facilitar el proceso de trabajo.
- **Git y CI/CD:** control de versiones y automatización de integración, pruebas o despliegue.
- **Respaldo (backup):** copia de datos que puede utilizarse para recuperar o trasladar información.

### 4️⃣ ⚠️ Problemas, errores o aclaraciones del profesor

- Se señaló que una respuesta como “almacenar contraseñas” no basta para describir el propósito y comportamiento de la aplicación; el análisis debe basarse en funciones observadas y en las instrucciones del cuestionario.
- El profesor anunció que reescribiría las preguntas del cuestionario debido a interpretaciones distintas. Aclaró que las respuestas debían referirse a la aplicación instalada y que había que revisar todas las secciones antes de enviar.
- La compatibilidad del sistema con dispositivos y entornos se identificó como una condición no funcional.
- El modelo en V se presentó como un esquema de verificación y validación; el profesor indicó que lo había incluido como referencia y que no lo había utilizado directamente en su trabajo.
- La transcripción explica varias herramientas y modelos de forma introductoria; no desarrolla configuraciones ni procedimientos completos de implementación.

### 5️⃣ 🧠 Conclusión de la clase

La sesión comparó maneras de organizar el ciclo de vida del software y enfatizó que la elección depende del alcance, la incertidumbre y los requisitos. La comunicación, la documentación y la validación ayudan a evitar que el equipo construya algo distinto de lo que el usuario necesita. El análisis de la aplicación puso en práctica entradas, salidas, subsistemas, entorno y límites.

### 6️⃣ ✅ Síntesis final

Las fases del ciclo de vida ordenan el trabajo y deben adaptarse al proyecto.
Los modelos secuenciales, iterativos, incrementales, espirales y ágiles organizan ese trabajo de formas distintas.
Requisitos claros y comunicación reducen interpretaciones incompatibles.
Verificar y validar comprueba tanto el producto como su utilidad para el usuario.
La aplicación de contraseñas se analizó por sus funciones, entradas, salidas y límites.

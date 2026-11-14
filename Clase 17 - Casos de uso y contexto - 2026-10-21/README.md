# Clase 17: Casos de uso y diagramas de contexto

### 1️⃣ 📘 Identificación

- **Asignatura:** Ingeniería de Software I
- **Clase:** 17
- **Fecha:** 21 de octubre de 2026
- **Tema:** Vista externa del sistema, actores, casos de uso y diagramas de contexto por niveles.
- **Fuente principal:** `Ing del Software 1- Clase 17.txt`.

### 2️⃣ 📝 Resumen explicativo

La clase continuó el modelado de la vista externa de la organización. Se revisó cómo los diagramas ayudan a mostrar quién utiliza el sistema, qué acciones realiza y cuáles son sus límites. El caso de uso se representó dentro de un rectángulo que delimita el sistema; los actores quedan fuera y se conectan con las acciones que pueden iniciar.

Con una aplicación de gestión de contraseñas como ejemplo, se analizó cómo describir con precisión a los usuarios, sus necesidades, las entradas y las salidas. El profesor recalcó que los nombres usados en la documentación deben ser claros y compartidos, pues ayudan a comunicar el propósito del sistema y a mantenerlo cuando cambian las personas o la tecnología.

Después se desarrolló el diagrama de contexto: el producto o sistema va al centro, las entidades externas se colocan alrededor y las flechas indican intercambios de información. Se explicó la descomposición por niveles: nivel 0 para el sistema completo, nivel 1 para sus módulos y niveles posteriores para procesos o funciones más específicos. Para el proyecto de control escolar, cada equipo debía representar su módulo y contribuir a una vista coherente del sistema general. La encuesta grupal y las entrevistas individuales debían aportar problemas reales para fundamentar el modelado.

### 3️⃣ 🧩 Conceptos teóricos y técnicos relevantes

- **Actor:** persona, rol, organización o sistema externo que interactúa con el sistema modelado.
- **Límite del sistema:** rectángulo que separa las acciones incluidas en el sistema de actores y elementos externos.
- **Caso de uso:** acción o servicio que el actor realiza o solicita; se nombra con un verbo en infinitivo y debe describir una función comprensible.
- **Asociación:** vínculo entre un actor y los casos de uso con los que interactúa.
- **Diagrama de contexto:** representa el sistema como un proceso central, las entidades externas y los flujos de entrada y salida.
- **Niveles de contexto:** nivel 0 muestra el sistema completo; nivel 1 puede desglosar módulos; niveles posteriores aumentan el detalle hasta los procesos o funciones necesarios.
- **Documentación y vocabulario común:** permiten comunicar decisiones, alcance, responsabilidades y datos entre equipos y facilitan el mantenimiento.
- **Encuesta y entrevistas:** recogen experiencias de usuarios; deben analizarse para distinguir problemas observados de suposiciones.

### 4️⃣ ⚠️ Problemas, errores o aclaraciones del profesor

- Cada equipo debía incorporar todos los módulos que se le asignaron, no solamente el que recibió al inicio del proyecto.
- La calidad del análisis importa más que la cantidad de texto o diagramas; el entregable debía ser claro, útil y revisado por el equipo.
- El profesor presentó `<<extend>>` como una dependencia en la que un caso de uso no podría ejecutarse sin otro. **Aclaración UML:** `<<extend>>` suele modelar comportamiento opcional o condicionado que amplía un caso base; no debe memorizarse como una dependencia obligatoria en todos los casos.
- La aplicación de contraseñas fue un ejemplo para practicar actores y flujos; no define los requisitos del proyecto de control escolar.
- La actividad pedía incluir los diagramas en la documentación Markdown como imagen y conservar también el código fuente cuando la herramienta lo permitiera. Para el diagrama de contexto, se indicó entregar la imagen exportada.
- **Actividad indicada:** elaborar diagramas de casos de uso con descripción de actores y acciones, y diagramas de contexto de nivel 0, 1 y 2 para el sistema y sus módulos. Cada integrante debía entrevistar a diez personas con la encuesta común del equipo y analizar qué problemas sí podían resolverse.

### 5️⃣ 🧠 Conclusión de la clase

Los diagramas externos dan una vista progresiva del sistema: primero delimitan su propósito y sus interacciones generales, y después detallan módulos y funciones. Para que sirvan como base del diseño, deben usar conceptos consistentes y apoyarse en necesidades investigadas, no en supuestos.

### 6️⃣ ✅ Síntesis final

Se repasaron actores, límites, asociaciones y casos de uso.
Se modelaron diagramas de contexto con entradas y salidas.
Los niveles van del sistema completo a módulos y funciones más específicas.
La tarea integró diagramas y resultados de entrevistas en la documentación del proyecto.

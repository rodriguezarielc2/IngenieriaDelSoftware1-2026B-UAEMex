# Clase 16: Entrevistas, requisitos y calidad

### 1️⃣ 📘 Identificación

- **Asignatura:** Ingeniería de Software I
- **Clase:** 16
- **Fecha:** 16 de octubre de 2026
- **Tema:** Requisitos funcionales y no funcionales, atributos de calidad y primeros diagramas UML.
- **Fuente principal:** `Ing del Software 1- Clase 16.txt`.

### 2️⃣ 📝 Resumen explicativo

La sesión conectó la investigación con la especificación de requisitos. Los requisitos funcionales describen, desde el lenguaje del usuario, las acciones que el sistema debe permitir; los no funcionales expresan atributos de calidad y restricciones técnicas que el equipo debe analizar, aunque el usuario no los formule directamente.

Se revisaron rendimiento, escalabilidad, usabilidad, fiabilidad, disponibilidad, seguridad, mantenibilidad y portabilidad. El profesor ilustró rendimiento con pruebas de carga y estrés, escalabilidad con crecimiento vertical y horizontal, y disponibilidad con porcentajes de tiempo activo. También explicó que los mensajes de error y las validaciones pueden afectar tanto la experiencia de uso como la seguridad.

Para practicar el modelado, el grupo analizó una aplicación móvil de resguardo de credenciales e identificó acciones como crear secretos, generar contraseñas, administrar categorías, importar o exportar respaldos e iniciar sesión. Se introdujo el diagrama de casos de uso y, después, el diagrama de contexto del sistema. El ejemplo ayudó a distinguir actores, límites del sistema, acciones y flujos entre módulos. La clase dejó como siguiente trabajo diagramar los requisitos funcionales de cada módulo.

### 3️⃣ 🧩 Conceptos teóricos y técnicos relevantes

- **Requisito funcional:** acción o servicio que el sistema ofrece, expresado con términos comprensibles para el usuario.
- **Requisito no funcional:** atributo o condición de calidad que orienta cómo debe comportarse el sistema.
- **Rendimiento:** rapidez de respuesta bajo condiciones definidas; se relaciona con pruebas de estrés, volumen y picos de demanda.
- **Escalabilidad:** capacidad de crecer y soportar más carga; puede ser vertical (más recursos en una máquina) u horizontal (más máquinas o instancias).
- **Usabilidad:** facilidad con la que los usuarios entienden y completan sus tareas.
- **Fiabilidad e integridad:** consistencia del comportamiento y conservación correcta de los datos esperados.
- **Disponibilidad:** proporción de tiempo en que el sistema presta servicio; se ilustró con los porcentajes de “nueves”.
- **Mantenibilidad y portabilidad:** facilidad para cambiar el sistema y posibilidad de ejecutarlo en distintos entornos.
- **Diagrama de casos de uso:** representa actores y acciones que pueden realizar en el sistema; cada caso se nombra con una acción en infinitivo.
- **Diagrama de contexto:** presenta el sistema como una unidad y muestra actores o sistemas externos que intercambian información con él.
- **Expresiones regulares:** se mencionaron como patrones para validar datos; la explicación fue introductoria y no desarrolló una especificación formal.

### 4️⃣ ⚠️ Problemas, errores o aclaraciones del profesor

- Una encuesta puede tener preguntas abiertas, pero las respuestas deben recopilarse y sintetizarse con rigor; inventarlas no sustituye la investigación.
- El profesor recalcó que un sistema debe adaptarse a las necesidades reales de los usuarios y que no basta con asumir que usarán una solución propuesta.
- La integridad de los datos se distinguió del rendimiento: que una transacción conserve el valor correcto no mide su rapidez.
- La validación de entradas puede ayudar a usabilidad y seguridad, pero las reglas deben analizarse cuidadosamente para no revelar información que facilite ataques.
- La clase usó una aplicación de credenciales como ejemplo; sus funcionalidades sirven para practicar el modelado y no son requisitos del proyecto de control escolar.
- La transcripción termina abruptamente durante el cierre de la sesión. **⚠️ Parte del archivo parece incompleta o truncada en la transcripción.**

### 5️⃣ 🧠 Conclusión de la clase

Definir requisitos implica traducir las necesidades de los usuarios en acciones observables y, además, establecer criterios de calidad que permitan evaluar el sistema. Los diagramas de contexto y casos de uso ayudan a delimitar actores, responsabilidades y alcance antes de diseñar la solución.

### 6️⃣ ✅ Síntesis final

Se diferenciaron requisitos funcionales y no funcionales.
Se revisaron atributos de calidad como rendimiento, usabilidad y disponibilidad.
Se practicaron casos de uso con una aplicación de credenciales.
Se introdujeron diagramas de casos de uso y de contexto.
La transcripción disponible se corta al final de la clase.

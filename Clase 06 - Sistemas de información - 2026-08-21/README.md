# Clase 06 — Sistemas de información

### 1️⃣ 📘 Identificación

- **Tema principal:** sistemas de información en organizaciones y etapas para construirlos, probarlos y mantenerlos.
- **Subtemas y actividades:** tipos de sistemas (GIS, KMS y otros); datos, personas, procesos y tecnología; diseño y arquitectura; interfaces y API; sistemas monolíticos y distribuidos; pruebas de software; despliegue y mantenimiento.
- **Propósito:** comprender cómo se conectan las necesidades de una organización con la arquitectura, calidad y operación de un sistema de información.

### 2️⃣ 📝 Resumen explicativo

**Clasificaciones y decisiones.** La sesión retomó las clasificaciones TPS, MIS y DSS y agregó ejemplos como GIS (información geográfica) y KMS (gestión del conocimiento), además de sistemas empresariales, expertos y de inteligencia artificial. Se compararon alternativas de software libre y comercial y se señaló que las decisiones deben considerar licencias, infraestructura, costo de operación, necesidades y presupuesto del cliente.

**Organización y sistema de información.** Se describió un sistema de información como la combinación de datos, personas, procesos y tecnología que recopila, procesa, almacena y distribuye información. La solución debe responder a un propósito organizacional y funcionar dentro de límites claros. En una organización, los datos operacionales alimentan reportes administrativos y análisis estratégicos; detectar patrones puede apoyar decisiones, pero depende de la calidad de los registros y de los recursos disponibles.

**Diseño, arquitectura e interfaces.** Diseñar implica estructurar una solución útil, considerando necesidades, componentes, relaciones y evolución en el tiempo. Se usó como ejemplo un acceso con interfaz de usuario, API y almacenamiento de datos: cada parte tiene una responsabilidad y se comunica con otras. También se comparó una arquitectura monolítica, concentrada en un mismo componente, con una distribuida, donde partes como interfaz, servicios y base de datos se separan. La separación puede facilitar mantenimiento independiente, aunque requiere definir cómo se comunican los componentes.

**Calidad, pruebas y operación.** Se mencionaron pruebas unitarias (de un componente) y de integración (de varios componentes conectados), además de pruebas de carga y desempeño. La calidad debe evaluarse con entradas válidas e inválidas, capacidad, tiempo de respuesta y experiencia de uso. El despliegue pone una versión a disposición de sus usuarios, normalmente después de probarla en entornos controlados; se ilustró una liberación gradual mediante un proxy o balanceador, aumentando el tráfico hacia la nueva versión conforme se valida. El mantenimiento corrige fallas, atiende seguridad y adapta el software a nuevas necesidades.

**Actividad y continuidad.** Se aclaró que el cuestionario de análisis de la aplicación móvil debía describir su propósito, entradas, salidas, estructura y posibles mejoras; el formulario permitía una sola entrega y requería completar las preguntas antes de adjuntar los archivos. Para la siguiente sesión se propuso investigar metodologías y modelos del ciclo de vida del software, para discutirlos en clase.

### 3️⃣ 🧩 Conceptos teóricos y técnicos relevantes

- **Sistema de información:** combinación organizada de datos, personas, procesos y tecnología para producir y distribuir información.
- **API (Application Programming Interface):** interfaz que define cómo se comunican componentes o servicios de software.
- **Arquitectura monolítica:** componentes principales se agrupan en una unidad de despliegue; modificar una parte puede requerir trabajar con el conjunto.
- **Arquitectura distribuida:** componentes separados se comunican a través de interfaces o servicios.
- **Prueba unitaria:** verifica una unidad o componente por separado.
- **Prueba de integración:** verifica el comportamiento conjunto de componentes conectados.
- **Prueba de carga o desempeño:** evalúa capacidad, estabilidad o tiempo de respuesta bajo cierta demanda.
- **Despliegue:** publicación de una versión para uso en un entorno, especialmente producción.
- **Mantenimiento:** corrección, actualización y adaptación del sistema una vez que está en uso.
- **GIS y KMS:** sistemas de información geográfica y de gestión del conocimiento, respectivamente.

### 4️⃣ ⚠️ Problemas, errores o aclaraciones del profesor

- El profesor aclaró que en el formulario había que completar las preguntas obligatorias antes de enviar y que los archivos se adjuntaban dentro del mismo cuestionario. También comentó que modificaría el formato solicitado, pues la plataforma no aceptaba el formato de imagen que inicialmente había indicado.
- Se distinguió entre una interfaz visual para el usuario y otras interfaces técnicas entre servicios, bases de datos y componentes.
- La clase presentó API, HTTP, proxy y balanceo de carga de forma introductoria; una arquitectura real requiere especificar protocolos, seguridad, autenticación y condiciones de disponibilidad.
- Se insistió en probar el cambio antes de liberar una versión y en mantener alternativas para revertirla si falla.
- ⚠️ Parte del archivo parece incompleta o truncada en la transcripción.

### 5️⃣ 🧠 Conclusión de la clase

La construcción de sistemas de información requiere traducir necesidades organizacionales a una arquitectura comprensible y verificable. La separación de componentes, las pruebas, el despliegue gradual y el mantenimiento ayudan a conservar calidad durante la operación. La siguiente sesión continuaría con modelos y metodologías del ciclo de vida del software.

### 6️⃣ ✅ Síntesis final

Un sistema de información combina datos, personas, procesos y tecnología.
La arquitectura organiza componentes y sus interfaces de comunicación.
Las pruebas unitarias y de integración revisan distintos niveles del sistema.
El despliegue debe seguir validaciones; el mantenimiento continúa después de publicar.
Las decisiones técnicas dependen del propósito, los costos y las restricciones.

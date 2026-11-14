# Clase 18: Diagramas de clases, componentes y despliegue

### 1️⃣ 📘 Identificación

- **Asignatura:** Ingeniería de Software I
- **Clase:** 18
- **Fecha:** 28 de octubre de 2026
- **Tema:** Vista estructural y arquitectura estática: clases UML, componentes y despliegue.
- **Fuente principal:** `Ing del Software 1- Clase 18.txt`.

### 2️⃣ 📝 Resumen explicativo

La sesión pasó de los diagramas de contexto y casos de uso a la vista estructural del sistema. Se presentó el diagrama de clases como una forma de modelar abstracciones, atributos, operaciones y relaciones entre clases. Se revisaron interfaces, visibilidad y multiplicidad, además de relaciones como asociación, dependencia, agregación, composición y herencia o implementación.

Después se explicó el diagrama de componentes, que muestra módulos reemplazables, paquetes, artefactos y dependencias internas o externas. El ejemplo incluyó bibliotecas, puertos e interfaces de comunicación. Para ilustrar la arquitectura, el profesor desglosó una aplicación Android de gestión de credenciales en capas de presentación, negocio/seguridad y persistencia, con almacenamiento cifrado y acceso a servicios del sistema operativo.

Al final se introdujo el diagrama de despliegue, que representa nodos físicos y ambientes de ejecución, artefactos instalados y caminos de comunicación. En el ejemplo se ubicaron la aplicación Android, el sistema operativo, el almacenamiento local y externo, las bibliotecas y el hardware biométrico. También se discutió el principio de pedir únicamente los permisos y datos necesarios para la función de la aplicación.

### 3️⃣ 🧩 Conceptos teóricos y técnicos relevantes

- **Clase:** abstracción con nombre, atributos y operaciones; sus objetos tienen estado y comportamiento.
- **Interfaz:** declara operaciones que otro componente puede implementar; en UML se representa la relación de realización entre clase e interfaz.
- **Visibilidad UML:** `+` público, `-` privado, `#` protegido y `~` de paquete.
- **Relaciones de clases:** asociación, dependencia, agregación, composición y generalización/realización; la multiplicidad expresa cuántas instancias se relacionan.
- **Diagrama de componentes:** muestra unidades modulares, interfaces, paquetes, artefactos y dependencias entre componentes.
- **Diagrama de despliegue:** muestra nodos de ejecución, dispositivos, ambientes, artefactos desplegados y sus conexiones.
- **Arquitectura por capas:** separa presentación, lógica de negocio y persistencia, con responsabilidades distintas.
- **Persistencia y seguridad:** la información guardada puede mantenerse en una base de datos o en archivos; el ejemplo empleó cifrado y mecanismos del sistema operativo.
- **Principio de mínimo privilegio:** una aplicación debe solicitar solo los accesos necesarios para su propósito.

### 4️⃣ ⚠️ Problemas, errores o aclaraciones del profesor

- Un atributo de clase **no necesariamente es estático**: puede pertenecer a cada objeto; lo estático se comparte entre instancias y requiere indicación explícita en el modelo o lenguaje.
- Una relación de realización indica que una clase cumple el contrato de una interfaz; no es lo mismo que la herencia entre dos clases concretas.
- Agregación y composición expresan relaciones distintas de ciclo de vida: la composición implica una dependencia de existencia más fuerte entre el todo y sus partes.
- En el ejemplo de despliegue, se corrigió una etiqueta de la diapositiva que atribuía el APK a C++; la explicación de la sesión indicó que el ejemplo estaba hecho con Java y Kotlin.
- La aplicación de contraseñas y su arquitectura fueron un caso didáctico para explicar los diagramas; no constituyen requisitos confirmados del sistema de control escolar.
- El objetivo de los diagramas es comunicar decisiones arquitectónicas y dependencias, no agregar componentes o permisos que el sistema no necesita.

### 5️⃣ 🧠 Conclusión de la clase

Los diagramas estructurales describen distintos aspectos de un sistema: las clases modelan datos y comportamiento; los componentes, la organización modular; y el despliegue, dónde y cómo se ejecutan los artefactos. Una documentación útil debe reflejar dependencias reales y justificar los accesos, herramientas y recursos que el sistema requiere.

### 6️⃣ ✅ Síntesis final

Se revisaron clases, interfaces, visibilidad, relaciones y multiplicidad UML.
Se describieron componentes, paquetes, artefactos e interfaces.
Se modelaron capas y dependencias de una aplicación Android de ejemplo.
El diagrama de despliegue mostró dispositivos, software y conexiones.

# Clase 04 — Teoría general de sistemas

### 1️⃣ 📘 Identificación

- **Tema principal:** componentes, propiedades y clasificación de los sistemas.
- **Subtemas y actividades:** sistema de control escolar como ejemplo; contexto y límites; calidad de datos; interacción e interdependencia; resiliencia, estabilidad y mantenimiento; sistemas abiertos, cerrados y aislados; sistemas naturales, artificiales, concretos y abstractos; sistemas estáticos, dinámicos, deterministas y probabilísticos.
- **Propósito:** practicar cómo descomponer un sistema, identificar su propósito y delimitar el contexto antes de analizar una solución.

### 2️⃣ 📝 Resumen explicativo

**Componentes y propósito.** La clase retomó el modelo de entradas, proceso, salidas, retroalimentación y entorno. El sistema de control escolar sirvió para ubicar registros de alumnos, profesores y asignaturas como entradas; la inscripción, relación entre materias y cálculo de calificaciones como procesos; y boletas, promedios, referencias de pago o resultados de acreditación como salidas. La retroalimentación conecta el resultado con el entorno y puede producir nuevas entradas.

**Límites y calidad de información.** El contexto indica quién usa el sistema, para qué sirve y qué queda dentro de su alcance. Un sistema de control escolar no tiene que incluir automáticamente todos los procesos de una institución: si se amplía para administrar personal, movilidad u otros servicios, cambian sus límites y requisitos. Los sistemas que comparten datos deben coordinarse; mantener registros separados y desactualizados puede producir inconsistencias. También se destacó que datos incorrectos o mal ubicados generan resultados defectuosos aunque el procesamiento esté bien implementado.

**Propiedades y mantenimiento.** Se revisaron interacción e interdependencia entre elementos, adaptación al entorno, resiliencia, estabilidad, mantenibilidad y optimización. La resiliencia se explicó como la capacidad de recuperarse ante fallas; la estabilidad, como mantener el comportamiento esperado bajo carga; la mantenibilidad, como poder entender y modificar un sistema existente; y la optimización, como mejorar el uso de recursos o el tiempo de respuesta. Se recomendó justificar los cambios con conocimiento del sistema y pruebas, en lugar de simplificar código sin comprobar que conserva el comportamiento.

**Clasificaciones.** El grupo ordenó varias formas de clasificar sistemas: por origen (naturales o artificiales), por su representación (concretos o abstractos), por relación con el entorno (abiertos, cerrados o aislados), por variación en el tiempo (estáticos o dinámicos) y por predictibilidad (deterministas o probabilísticos). La clase contrastó sistemas abiertos —que intercambian información o recursos con el entorno— con sistemas cerrados, estudiados bajo límites y condiciones controladas. El sistema completamente aislado se manejó principalmente como una idealización teórica. La clasificación depende del contexto y del nivel desde el que se observe.

### 3️⃣ 🧩 Conceptos teóricos y técnicos relevantes

- **Entrada, proceso y salida:** datos o recursos que recibe un sistema, transformación que realiza y resultado que produce.
- **Retroalimentación:** información sobre el resultado que puede usarse para ajustar el sistema o generar nuevas entradas.
- **Entorno y límites:** condiciones externas y frontera que delimitan qué partes del problema se analizan.
- **Interdependencia:** una modificación en un elemento puede afectar a otros componentes relacionados.
- **Resiliencia:** capacidad de recuperarse de una falla y restablecer el servicio.
- **Mantenibilidad:** facilidad para comprender, corregir o modificar un sistema existente.
- **Sistema abierto, cerrado o aislado:** clasificación según su intercambio con el entorno, aplicada con límites explícitos.
- **Sistema estático o dinámico:** clasificación según si su estado o comportamiento cambia con el tiempo.
- **Determinista o probabilístico:** distinción entre resultados definidos por reglas y análisis que estima tendencias o probabilidades.
- **Calidad de datos:** condición necesaria para que el procesamiento produzca información confiable.

### 4️⃣ ⚠️ Problemas, errores o aclaraciones del profesor

- El profesor pidió distinguir las categorías de clasificación, no mezclar “natural o artificial” con “abierto o cerrado”: las primeras describen el origen; las segundas, la relación con el entorno.
- Se aclaró que la clasificación de un sistema depende de sus límites y de la perspectiva considerada. Un sistema puede parecer cerrado en un ambiente de pruebas y ser abierto cuando opera con usuarios y servicios externos.
- Interacción e interconexión se trataron como términos cercanos; no toda palabra sugerida por la clase se aceptó como una propiedad distinta.
- Un cambio que reduce líneas de código debe comprobarse con pruebas de escritorio, unitarias o de integración y con entradas variadas.
- ⚠️ Parte del archivo parece incompleta o truncada en la transcripción.

### 5️⃣ 🧠 Conclusión de la clase

El análisis de un sistema comienza por identificar sus componentes y propósito, pero también requiere establecer límites, usuarios, datos y relaciones con el entorno. Estas decisiones orientan qué propiedades y categorías son relevantes y ayudan a evitar sistemas inconsistentes. La sesión cerró mientras el grupo seguía revisando clasificaciones y ejemplos.

### 6️⃣ ✅ Síntesis final

Un sistema recibe entradas, las procesa y produce salidas en un contexto.
Los límites definen qué problema y qué usuarios forman parte del análisis.
La interdependencia y los cambios del entorno afectan a los componentes.
Las clasificaciones describen aspectos distintos: origen, representación, entorno, tiempo y predictibilidad.
La calidad de los datos y las pruebas condicionan la confiabilidad del resultado.

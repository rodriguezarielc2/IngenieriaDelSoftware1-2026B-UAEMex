# Clase 20: Estructuras organizacionales y revisión de requisitos

### 1️⃣ 📘 Identificación

- **Asignatura:** Ingeniería de Software I
- **Clase:** 20
- **Fecha:** 4 de noviembre de 2026
- **Tema:** Modelado de la organización y coherencia entre módulos y requisitos del proyecto.
- **Fuente principal:** `Ing del Software 1- Clase 20.txt`.

### 2️⃣ 📝 Resumen explicativo

La primera parte repasó los diagramas dinámicos de la sesión anterior. Después se introdujo el organigrama como representación de roles, jerarquías y relaciones de autoridad dentro de una organización. Se estudiaron tres estructuras: lineal o jerárquica, organizada por proyectos y funcional, con áreas especializadas. El profesor comparó sus características, ventajas y dificultades de coordinación; quedaron otros modelos para una sesión posterior.

En la segunda parte se revisó en GitHub la documentación del módulo de alumnos. Se pidió que el documento incluyera propósito, objetivo, alcance, actores y requisitos funcionales. La revisión mostró que algunas funciones descritas como propias del módulo de alumnos —por ejemplo, inicio de sesión y cambio de contraseña— son comunes a distintos tipos de usuario, por lo que se propuso separarlas en un módulo reutilizable de inicio de sesión.

La revisión también detectó una posible inconsistencia entre solicitar cambios de grupo desde el módulo de alumnos y las funciones asignadas al módulo de aulas/grupos. Los equipos debían leer los diagramas de los demás, discutir quién realiza cada acción y comprobar que los datos y funciones necesarios existan en los módulos correspondientes. La coherencia entre equipos se consideraría parte de la evaluación.

### 3️⃣ 🧩 Conceptos teóricos y técnicos relevantes

- **Organigrama:** representación gráfica de los roles, áreas y relaciones jerárquicas de una organización.
- **Estructura lineal o jerárquica:** autoridad directa y cadena de mando; facilita saber a quién reportar, pero puede concentrar decisiones y reducir flexibilidad.
- **Estructura por proyectos:** organiza equipos alrededor de proyectos con objetivos y duración definidos; facilita enfocarse en resultados, aunque exige coordinación y puede generar inestabilidad al concluir el proyecto.
- **Estructura funcional:** agrupa personas por especialidad o función; favorece la experiencia técnica, pero puede dificultar la coordinación entre departamentos.
- **Módulo común o reutilizable:** función compartida por distintos roles —como iniciar sesión— que conviene definir una sola vez y conectar con los módulos que la necesitan.
- **Alcance y requisitos:** especifican qué hace cada módulo, qué queda fuera y qué actores pueden realizar cada acción.
- **Consistencia entre módulos:** evita requisitos incompatibles y permite que los datos necesarios existan donde otros módulos los consultan.

### 4️⃣ ⚠️ Problemas, errores o aclaraciones del profesor

- En el ejemplo revisado, inicio de sesión y cambio de contraseña aparecían dentro del módulo de alumnos; se propuso centralizar la autenticación en un módulo común porque también la requieren profesores y personal administrativo.
- El sistema puede tener una página accesible públicamente, pero eso no significa que cualquier visitante deba poder consultar información interna. La autenticación y la autorización deben separar el acceso público de las funciones protegidas.
- Solicitar un cambio de grupo requiere que el sistema defina quién lo autoriza, qué grupos están disponibles y qué restricciones se aplican. Esa función debe coordinarse con el equipo responsable de grupos/aulas.
- El profesor indicó que un requisito general del sistema no debe atribuirse sin justificación a un solo módulo.
- **Actividad:** revisar los módulos y pull requests de los demás equipos, anotar observaciones en GitHub y preparar un debate sobre las inconsistencias encontradas. En esta clase solo se revisaron tres de los seis modelos organizacionales anunciados.

### 5️⃣ 🧠 Conclusión de la clase

El diseño del sistema requiere tanto una estructura organizacional comprensible como acuerdos claros entre los equipos que documentan sus módulos. Definir responsabilidades, autenticación, alcance y dependencias de forma coherente reduce contradicciones que de otro modo aparecerían durante la integración o la evaluación.

### 6️⃣ ✅ Síntesis final

Se revisaron estructuras jerárquicas, por proyecto y funcionales.
Se evaluó la documentación del módulo de alumnos.
Se propuso separar la autenticación en un módulo común.
Los equipos debían revisar y comentar las inconsistencias entre módulos.

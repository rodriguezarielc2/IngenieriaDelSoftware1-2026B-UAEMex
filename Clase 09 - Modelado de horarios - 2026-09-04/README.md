# Clase 09 — Modelado de horarios

### 1️⃣ 📘 Identificación

- **Tema principal:** revisión de las variables del problema de horarios y diseño de un modelo entidad–relación para el sistema escolar.
- **Subtemas y actividades:** corrección de capacidad semanal; escenarios con materias de dos o tres sesiones; variables y límites del análisis; oferta de lugares; entidades y relaciones; tablas, campos y datos de ejemplo.
- **Propósito:** representar la información necesaria para analizar la disponibilidad de grupos y lugares en una escuela.

### 2️⃣ 📝 Resumen explicativo

**Revisión de capacidad.** La clase retomó el escenario de diez aulas y seis días. Se aclaró que, con clases de dos horas dentro de una jornada de 7:00 a 20:00, caben seis bloques de clase al día si se reserva una hora libre. Así se obtuvieron (10 \times 6 \times 6 = 360) espacios semanales, en lugar de los 420 calculados con siete bloques. Si cada materia se reúne dos veces por semana, el extremo del modelo es 180 grupos; si se reúne tres veces, es 120. El caso mixto requiere una fórmula con el número de materias de cada tipo.

**Variables y alcance.** El grupo volvió a definir la duración de las clases, días, aulas, capacidad por materia, número de materias y cantidad de sesiones. Se señaló que las aulas disponibles pueden cambiar entre semestres y que el análisis debe declarar sus límites. También se discutieron alumnos que cursan cantidades distintas de materias o avanzan a ritmos diferentes; para estimar variaciones podrían usarse datos históricos y estadística, si están disponibles.

**Modelo entidad–relación.** El sistema escolar se descompuso en conceptos como alumno, materia, profesor, grupo, sesión, horario, aula y clasificación de materia, junto con sus atributos y relaciones. El objetivo no era desplegar una base de datos, sino representar qué información hace falta y cómo se asocia. Se propuso trabajar las tablas y datos de ejemplo en Excel y presentar el modelo en PowerPoint. También se explicó que distintos perfiles necesitan vistas distintas: una arquitectura general, el detalle de datos para un DBA y diagramas más específicos para desarrollo o pruebas.

**Actividad solicitada.** Para la siguiente clase se pidió entregar el diagrama entidad–relación del caso y un archivo de Excel con tablas, campos y datos simulados (de uno a diez registros por tabla). El profesor pidió que cada estudiante preparara su propio modelo antes de compararlo con el grupo, para poder identificar omisiones y revisar las decisiones de análisis.

### 3️⃣ 🧩 Conceptos teóricos y técnicos relevantes

- **Espacio semanal de clase:** capacidad calculada a partir de aulas, días y bloques disponibles.
- **Variable de decisión:** cantidad que el modelo debe estimar, como grupos o lugares ofertados.
- **Parámetro:** dato fijado para el escenario, como aulas, días, duración de clase o capacidad del salón.
- **Modelo entidad–relación (ER):** representación de entidades, atributos y relaciones relevantes para organizar los datos.
- **Entidad:** tipo de elemento distinguible del problema, como Alumno, Materia o Aula.
- **Atributo:** dato que describe una entidad, como matrícula, nombre o capacidad.
- **Relación:** asociación entre entidades, por ejemplo, un grupo cursa una materia y tiene un horario.
- **Límite del análisis:** condiciones que determinan qué casos, periodos y variables quedan dentro del modelo.

### 4️⃣ ⚠️ Problemas, errores o aclaraciones del profesor

- Se corrigió el cálculo anterior de 420 espacios: siete bloques de dos horas no caben en las 13 horas entre 7:00 y 20:00. Con seis bloques, el total del escenario es 360.
- Las cifras 180 y 120 describen grupos o materias bajo supuestos de dos o tres sesiones semanales; no determinan por sí solas el número real de docentes.
- El modelo de aula fija una capacidad de 20 alumnos como supuesto del profesor; para un sistema real habría que confirmar capacidades por salón y materia.
- La explicación transcrita mezcla los términos “entidad” y “campo”. En el modelo, una entidad representa un tipo de elemento y sus campos se describen como atributos; conviene conservar esa distinción.
- La disponibilidad de aulas, la cantidad de sesiones y el avance de alumnos pueden variar. Deben tratarse como supuestos, datos o variables explícitos, no como hechos universales.

### 5️⃣ 🧠 Conclusión de la clase

El ejercicio corrigió una suposición numérica y mostró que un modelo depende de que cada dato tenga una definición y unidad claras. El diagrama entidad–relación permite organizar la información del sistema escolar, mientras que las variables y límites determinan qué cálculos son posibles. El modelo y las tablas de ejemplo quedaron como entregable para la siguiente clase.

### 6️⃣ ✅ Síntesis final

Con seis aulas disponibles por bloque horario, el escenario obtiene 360 espacios semanales.
Los extremos de dos o tres sesiones por materia producen 180 y 120 grupos bajo esos supuestos.
El modelo ER debe distinguir entidades, atributos y relaciones.
La oferta de lugares depende de capacidad, horarios y datos confirmados.
El Excel y el diagrama debían representar tablas, campos y datos simulados.

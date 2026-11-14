# Clase 08 — Problema de horarios

### 1️⃣ 📘 Identificación

- **Tema principal:** formulación y delimitación de un problema de asignación de horarios.
- **Subtemas y actividades:** análisis del problema; capacidad de aulas; número de sesiones; materias de dos o tres sesiones semanales; hipótesis, variables y rangos; capacidad por materia; lugares para aspirantes.
- **Propósito:** convertir una observación sobre horarios en un modelo que pueda analizarse y resolverse de manera sistemática.

### 2️⃣ 📝 Resumen explicativo

**Definición del problema.** La clase inició con una propuesta sobre posible mala asignación de horarios y aulas disponibles. El grupo discutió si la causa era realmente una asignación incorrecta o si dependía de organización, planificación y diferencias en las materias que cada estudiante cursa. El profesor pidió no aceptar una explicación sin investigarla y usar el análisis para precisar qué se quiere resolver.

**Escenario hipotético de capacidad.** Para construir un modelo, se planteó una escuela ficticia con diez aulas, clases de lunes a sábado y una jornada de 7:00 a 20:00. Se supusieron siete bloques diarios por aula, con clases de dos horas, lo que se utilizó para calcular (10 \times 6 \times 7 = 420) espacios semanales para clases. Se consideraron después materias con dos o tres sesiones por semana: en los extremos, el profesor calculó (420/2 = 210) y (420/3 = 140). La situación mixta debía resolverse con una fórmula que usara el número de materias de cada tipo.

**Variables adicionales.** El análisis se amplió a ocho materias por estudiante, diferencias en el avance (adelantado, atrasado o regular) y cupo por materia. Se señaló que cada aula o asignatura podría tener capacidades distintas. Para estimar los lugares disponibles para aspirantes habría que modelar esas capacidades, además del número de sesiones y materias.

**Trabajo solicitado.** Para la siguiente clase, el grupo debía proponer variables y un procedimiento matemático que permita resolver el caso mixto, explicar cada variable y comprobar que el resultado quede entre los escenarios mínimo y máximo. También se pidió considerar el cupo disponible por asignatura y cómo calcular los lugares ofertados.

### 3️⃣ 🧩 Conceptos teóricos y técnicos relevantes

- **Modelo del problema:** representación simplificada que separa datos conocidos, variables y relaciones necesarias para calcular un resultado.
- **Hipótesis:** escenario asumido para explorar el problema; no debe confundirse con datos confirmados de la facultad.
- **Variable:** valor que puede cambiar, como el número de materias con dos o tres sesiones.
- **Parámetro:** dato fijado para el cálculo, como la cantidad de aulas del escenario.
- **Capacidad semanal:** número de espacios o sesiones que pueden ofrecer las aulas durante la semana.
- **Restricción de cupo:** límite de estudiantes que puede aceptar una asignatura o aula.
- **Análisis de requisitos:** aclarar qué resultado necesita el usuario y qué condiciones deben incluirse antes de elegir una solución.

### 4️⃣ ⚠️ Problemas, errores o aclaraciones del profesor

- La jornada de 7:00 a 20:00 equivale a 13 horas, pero siete bloques de dos horas sumarían 14. La transcripción no resuelve esta inconsistencia; el cálculo de 420 usa siete bloques por día.
- Las estimaciones de 210 y 140 se obtuvieron al dividir las 420 sesiones entre dos o tres sesiones por materia. No se especificó cuántas sesiones puede impartir cada profesor, así que esos valores no bastan para determinar el número real de docentes; dependen de una simplificación del escenario.
- El profesor enfatizó que los resultados dependían de las hipótesis y parámetros, y pidió formular el procedimiento antes de dar una cifra final.
- La propuesta de “mala asignación” quedó como problema por investigar, no como causa comprobada.

### 5️⃣ 🧠 Conclusión de la clase

El ejercicio mostró cómo un problema cotidiano requiere precisar alcance, horarios, sesiones, capacidad y población antes de calcular una solución. Las hipótesis permiten empezar, pero cada número debe corresponder a una condición explícita. El caso mixto y el cálculo de lugares disponibles quedaron como trabajo para continuar en la siguiente sesión.

### 6️⃣ ✅ Síntesis final

El problema de horarios debía investigarse antes de atribuirlo a una mala asignación.
El escenario hipotético calculó 420 espacios semanales a partir de diez aulas y siete bloques diarios.
Los extremos de materias de dos o tres sesiones dieron 210 y 140 unidades bajo esa simplificación.
La fórmula del caso mixto y el cupo por materia requieren variables claramente definidas.
La jornada declarada y el número de bloques tienen una discrepancia que debe aclararse.

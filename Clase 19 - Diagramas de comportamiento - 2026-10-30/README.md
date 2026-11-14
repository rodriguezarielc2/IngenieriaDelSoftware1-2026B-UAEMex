# Clase 19: Diagramas de comportamiento del sistema

### 1️⃣ 📘 Identificación

- **Asignatura:** Ingeniería de Software I
- **Clase:** 19
- **Fecha:** 30 de octubre de 2026
- **Tema:** Vista dinámica: diagramas de secuencia, actividades y máquinas de estados.
- **Fuente principal:** `Ing del Software 1- Clase 19.txt`.

### 2️⃣ 📝 Resumen explicativo

La clase cerró el conjunto de diagramas del proyecto con modelos que representan el comportamiento a través del tiempo. Se relacionó la ejecución de módulos con sus dependencias: por ejemplo, para asignar una materia primero deben existir los elementos necesarios. Los procesos independientes pueden ejecutarse en paralelo, mientras que las dependencias imponen un orden.

Se construyó un diagrama de secuencia para generar una contraseña. El ejemplo siguió la configuración de opciones, la solicitud a la interfaz, la generación por componentes y la respuesta que vuelve al usuario. Se incluyeron alternativas de error, como no tener opciones válidas, además del camino exitoso. Se explicaron líneas de vida, activaciones, mensajes, ciclos y respuestas.

Después se revisó el diagrama de actividades —similar a un diagrama de flujo— con inicio, acciones, decisiones, caminos alternativos, posibles actividades paralelas y final. Por último, se modeló la máquina de estados para el ciclo de vida de una credencial: creación, almacenamiento, bloqueo, autenticación, edición y eliminación. Se distinguió el borrado lógico del borrado físico y se señaló que el mismo enfoque puede aplicarse a estados de sesión u otros componentes.

### 3️⃣ 🧩 Conceptos teóricos y técnicos relevantes

- **Vista dinámica:** muestra el comportamiento y el orden temporal de las interacciones, complementando la estructura estática.
- **Diagrama de secuencia:** representa participantes, líneas de vida, activaciones, mensajes, retornos, ciclos y alternativas en una interacción.
- **Diagrama de actividades:** modela un flujo de trabajo con nodo inicial, acciones, decisiones, sincronización o paralelismo y nodo final.
- **Máquina de estados:** modela estados de un objeto o sistema y las transiciones provocadas por eventos o acciones.
- **Dependencia y paralelismo:** los pasos dependientes requieren un orden; actividades independientes pueden ejecutarse en paralelo.
- **CRUD:** crear, consultar, actualizar y eliminar. Se mostró como ejemplo de descomposición de un módulo de profesores.
- **Happy path y recuperación:** además del escenario exitoso, los diagramas deben considerar errores, mensajes claros y formas de continuar o recuperarse.
- **Borrado lógico:** marca un registro como inactivo o eliminado, conservándolo como histórico; el borrado físico quita los datos del almacenamiento.

### 4️⃣ ⚠️ Problemas, errores o aclaraciones del profesor

- El ejemplo de generación de contraseñas fue didáctico; cada diagrama del proyecto debe describir el comportamiento real del módulo correspondiente.
- El profesor indicó que cada caso de uso debía contar, como mínimo, con un diagrama de actividades y uno de secuencia. Los diagramas extensos debían dividirse para conservar legibilidad.
- Un camino de error no debe limitarse a un código ambiguo; conviene comunicar qué ocurrió y qué puede hacer el usuario.
- **Aclaración de lectura UML:** los participantes de un diagrama de secuencia se colocan horizontalmente, pero el orden temporal de los mensajes se lee de arriba hacia abajo. La explicación oral menciona “de izquierda a derecha”, lo cual puede confundirse con el orden del tiempo.
- La máquina de estados debe incluir solo estados y transiciones pertinentes al elemento modelado; no es necesario inventar etapas que el sistema no maneja.

### 5️⃣ 🧠 Conclusión de la clase

Los diagramas de comportamiento completan la descripción del sistema al mostrar cuándo se ejecuta cada acción, cómo se intercambian mensajes y en qué estados puede encontrarse un componente. Considerar errores, dependencias y recuperación desde el diseño permite contrastar después el comportamiento construido con el esperado.

### 6️⃣ ✅ Síntesis final

Se revisaron secuencia, actividades y máquinas de estados.
Los diagramas de secuencia ordenan los mensajes entre participantes.
Los de actividades representan decisiones, flujos y paralelismo.
Las máquinas de estados describen ciclos de vida y transiciones.
Se recomendó incluir caminos de error y recuperación.

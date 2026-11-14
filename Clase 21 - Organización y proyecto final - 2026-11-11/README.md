# Clase 21: Organización y estructura del proyecto final

### 1️⃣ 📘 Identificación

- **Asignatura:** Ingeniería de Software I
- **Clase:** 21
- **Fecha:** 11 de noviembre de 2026
- **Tema:** Modelos organizacionales, operaciones CRUD y actualización de la estructura documental del proyecto.
- **Fuente principal:** `Ing del Software 1- Clase 21.txt`.

### 2️⃣ 📝 Resumen explicativo

La sesión repasó los modelos de organización y completó seis formas de representarlos: lineal o jerárquica, por proyectos, funcional, divisional, matricial y transversal. Se explicó que una organización real puede combinar varios modelos, por lo que se habló también de una estructura mixta. El grupo discutió cuál modelo describe mejor el trabajo del proyecto de la asignatura: equipos responsables de distintos módulos que deben coordinarse y contribuir al producto documental común.

Después se retomó CRUD como ciclo de operaciones sobre los datos: crear, leer, actualizar y eliminar. El orden y los permisos para cada operación dependen del análisis y de las relaciones entre los datos. Se recordó que borrar puede significar una eliminación lógica o física y que los estados de las credenciales —por ejemplo, creadas, activas, suspendidas, caducadas o revocadas— deben definirse con reglas claras.

La parte práctica actualizó el formato del proyecto en GitHub. Cada módulo debía documentar actores y sus funciones, casos de uso, componentes, secuencias, estados y clases, con diagramas legibles y la información en español o con términos explicados. El README principal debía enlazar los módulos e incluir la vista general, el contexto del sistema y los requisitos de nivel 0; los módulos contienen requisitos de nivel 1 y el análisis debía profundizar hasta nivel 2. Se dejaron para trabajo posterior el diccionario de datos, el diagrama relacional y completar la estructura global.

### 3️⃣ 🧩 Conceptos teóricos y técnicos relevantes

- **Modelo lineal o jerárquico:** cadena de autoridad vertical con responsabilidades y superiores directos.
- **Modelo por proyectos:** equipos temporales organizados alrededor de metas y entregables.
- **Modelo funcional:** áreas agrupadas por especialidad o función.
- **Modelo divisional:** organización separada en divisiones con responsabilidades o productos distintos.
- **Modelo matricial:** combina funciones con proyectos o productos; una persona puede ubicarse en ambos ejes.
- **Modelo transversal:** facilita colaboración entre áreas y reduce barreras de comunicación jerárquica.
- **Modelo mixto:** combinación de estructuras según las necesidades de la organización; no se presentó como una forma única y fija.
- **CRUD:** crear (*Create*), leer (*Read*), actualizar (*Update*) y eliminar (*Delete*) datos.
- **Requisito por niveles:** nivel 0 expresa el sistema completo; nivel 1 especifica módulos; nivel 2 detalla funciones o procesos.
- **Estructura del entregable:** README general con índice y contexto; carpetas de módulos con diagramas y descripción de actores, además de tablas generales de actores/roles y permisos.

### 4️⃣ ⚠️ Problemas, errores o aclaraciones del profesor

- Que exista un botón o función para eliminar no implica que los datos deban borrarse físicamente; las relaciones y necesidades de historial pueden exigir borrado lógico.
- Términos como “caducado” necesitan definición concreta: debe quedar claro qué elemento caduca y bajo qué regla o periodo.
- Los requisitos de un módulo no deben contradecir los de otros módulos. La autenticación es transversal y se había asignado como módulo compartido; las funciones comunes debían reutilizarse.
- El profesor pidió mantener coherencia entre aportaciones, registrar commits claros y revisar la documentación de los demás equipos. El README general debía enlazar los módulos; un archivo que no esté referenciado no se integra correctamente a la documentación principal.
- **Actualización del template:** se solicitaron diagramas de casos de uso, componentes, secuencia y clases para los módulos; diagramas de estados para objetos o clases involucrados; y una tabla que describa los actores y sus funciones. Cada caso de uso debía tener diagrama de componentes y de secuencia, y las imágenes debían seguir siendo legibles en una página tamaño carta.
- La estructura del proyecto aún no estaba cerrada: se anticiparon el diccionario de datos y el diagrama relacional para clases posteriores.

### 5️⃣ 🧠 Conclusión de la clase

El proyecto final requiere una visión organizacional y técnica coherente: los roles distribuyen responsabilidades, los módulos se relacionan, y CRUD y los estados determinan cómo evolucionan los datos. La documentación debe conectar el nivel general del sistema con sus módulos, explicar sus decisiones y mantenerse coordinada entre equipos.

### 6️⃣ ✅ Síntesis final

Se repasaron seis modelos organizacionales y la posibilidad de combinarlos.
Se relacionó CRUD con los estados y dependencias de los datos.
Se amplió el template de módulos con actores y diagramas UML.
El proyecto debía cubrir niveles 0, 1 y 2 y enlazar todos los módulos.
El diccionario de datos y el modelo relacional quedaron pendientes.

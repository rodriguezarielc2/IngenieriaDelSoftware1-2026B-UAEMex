# Clase 24: Análisis de sustantivos y diccionario de datos

### 1️⃣ 📘 Identificación

- **Tema principal:** depuración de sustantivos de casos de uso y documentación de datos para los modelos del sistema.
- **Subtemas y actividades:** homologación de términos; clasificación de actores, clases, entidades y atributos; alcance de los datos; estructura y reglas del diccionario de datos; calidad de la información; integración y presentación del proyecto final.
- **Propósito de aprendizaje:** convertir los conceptos identificados en los casos de uso en modelos y definiciones de datos consistentes entre los módulos.

### 2️⃣ 📝 Resumen explicativo

**Extracción y depuración de sustantivos.** La sesión comenzó con la necesidad de revisar en conjunto los casos de uso y homologar los términos que usan los módulos. Si distintos equipos llaman de manera diferente al mismo concepto —por ejemplo, “docente”, “maestro” y “profesor”—, deben acordar un solo término y usarlo en casos de uso y diagramas. La extracción se hace a partir de los sustantivos y frases nominales de los casos de uso, que describen quién participa y qué ocurre.

El procedimiento explicado tuvo tres pasos:

1. **Extraer** los sustantivos y frases nominales de todos los casos de uso, incluyendo personas, objetos y documentos relevantes.
2. **Filtrar** la lista: unificar sinónimos; quitar términos que no pertenecen al alcance; y descartar palabras demasiado abstractas o que no aportan información técnica. El profesor puso como ejemplos genéricos “el sistema” y “la pantalla”; pidió nombrar de forma concreta las pantallas, módulos y funciones que sí formen parte del análisis.
3. **Clasificar** los términos restantes como actores, clases o entidades candidatas y atributos. La clasificación debe revisarse: que una palabra aparezca en un caso de uso no significa automáticamente que deba convertirse en clase.

El profesor relacionó este análisis con la consistencia entre equipos. Los términos de un módulo deben coincidir con los que usan sus dependencias; de lo contrario, la integración puede producir nombres duplicados o incompatibles. Al cerrar los módulos, el grupo tendrá que integrar modelos comunes, entre ellos la vista general de casos de uso y los modelos de clases y datos. También recordó que distintos roles, como alumno, profesor y administrador, pueden compartir características generales de usuario y tener responsabilidades específicas.

**Alcance y diccionario de datos.** A continuación, se explicó que el análisis de sustantivos alimenta la definición de entidades y atributos, pero que el diccionario debe incluir únicamente los datos que el sistema necesita para cumplir su propósito. Una persona puede tener muchos datos que no sean pertinentes para un sistema de control escolar; la utilidad y el alcance deben justificar cuáles se registran. La fecha de nacimiento se usó como ejemplo de un dato cuya utilidad depende de las necesidades de análisis de la institución. Los ejemplos de información personal no son, por sí solos, requisitos acordados para el proyecto.

El diccionario documenta cada entidad y cada campo con una descripción comprensible, su tipo de dato y las restricciones que determinan cómo se usa. Se deben especificar reglas técnicas —por ejemplo, tipo, longitud, obligatoriedad, unicidad o valor predeterminado— y reglas de negocio —por ejemplo, un formato permitido o un rango válido—. La descripción ayuda a resolver ambigüedades como qué significa “nombre” y qué valores representa un estado.

Se revisaron las características técnicas siguientes: descripción o notas; tipo de dato; dominio o rango; longitud o precisión; obligatoriedad; unicidad; y atomicidad. La selección del tipo concreto también depende del lenguaje y del gestor de base de datos que se vaya a usar. Para datos como estados, el conjunto de valores aceptados debe quedar definido, en vez de dejarlo a interpretación.

**Calidad de los datos.** El profesor describió integridad, consistencia, exactitud, completitud, oportunidad y dominio o validez. La integridad se relacionó con mantener relaciones correctas; la consistencia, con usar significados y formatos homogéneos; la exactitud, con que el dato represente aquello que pretende describir; la completitud, con no perder información necesaria; la oportunidad, con disponer de información actualizada cuando se requiere; y el dominio o validez, con aceptar solo valores permitidos por las reglas del sistema. Estas cualidades permiten que los datos apoyen operaciones y decisiones sin introducir interpretaciones contradictorias.

Como ejemplo de diccionario, se recorrió una entidad **Libro** con identificador, ISBN, título, año de publicación y disponibilidad. Se mostró cómo registrar tipo, longitud, restricciones, valor predeterminado y descripción para cada campo. El ejemplo corresponde a una biblioteca y sirve para explicar el formato; no define entidades ni reglas del sistema de control escolar. La tabla se desarrolla en [Contexto complementario](Contexto%20complementario.md).

**Indicaciones del proyecto final.** En la parte final se revisaron actividades publicadas en el repositorio del proyecto. El profesor pidió leer las indicaciones, completar el README general con información de nivel cero, concentrar la documentación en las carpetas acordadas para módulos y diagramas, revisar enlaces y archivos, e integrar diagramas homogéneos con sus fuentes y representaciones legibles. La rama `develop` sería la referencia para evaluar el estado final del proyecto. Se indicó como fecha límite el jueves 3 de diciembre de 2026 y que las presentaciones comenzarían el viernes 4 de diciembre.

Las presentaciones tendrían 50 minutos: 30 para explicar y justificar el módulo y 20 para preguntas, también sobre su relación con otros módulos. Se pidió la participación de todos los integrantes y conocimiento del sistema completo. El uso de PowerPoint sería opcional; también se podía presentar recorriendo la documentación Markdown. Las indicaciones y fechas se registran tal como fueron comunicadas en esta sesión y pueden estar sujetas a avisos posteriores del docente.

### 3️⃣ 🧩 Conceptos teóricos y técnicos relevantes

| Concepto | Explicación trabajada en la sesión |
|---|---|
| Análisis de sustantivos | Extracción y depuración de conceptos presentes en los casos de uso para apoyar la identificación de elementos del modelo. |
| Homologación | Acuerdo para nombrar de una sola forma un concepto que aparece con sinónimos en distintos módulos. |
| Actor | Rol externo que interactúa con el sistema, con responsabilidades y permisos definidos. |
| Clase o entidad candidata | Concepto relevante que puede modelarse como clase o entidad después de analizar su responsabilidad y alcance. |
| Atributo | Dato que describe una clase o entidad y que puede convertirse en campo o columna. |
| Diccionario de datos | Documento que especifica entidades y atributos, junto con sus significados, tipos, restricciones y reglas. |
| Dominio o rango | Conjunto de valores o límites válidos para un dato. |
| Longitud o precisión | Cantidad de caracteres o precisión numérica admitida por un atributo. |
| Obligatoriedad | Condición que define si un dato debe estar presente. |
| Unicidad | Regla que impide que un valor identificador se repita dentro del ámbito definido. |
| Atomicidad | Grado en que un dato se almacena como una unidad o se divide en partes con significado propio. |
| Integridad | Conservación de datos y relaciones válidas entre elementos relacionados. |
| Consistencia | Homogeneidad de significado y formato para datos del mismo tipo en el sistema. |
| Exactitud | Correspondencia entre el valor almacenado y la realidad que ese valor representa. |
| Completitud | Presencia de los datos necesarios para operar y tomar decisiones. |
| Oportunidad | Disponibilidad y actualidad del dato cuando un proceso lo necesita. |
| Dominio y validez | Conformidad del valor con el conjunto y las reglas aceptadas. |

### 4️⃣ ⚠️ Problemas, errores o aclaraciones del profesor

- No todo sustantivo se convierte en clase: primero se eliminan sinónimos, términos fuera de alcance y palabras que no aportan significado técnico; después se decide su clasificación.
- Los ejemplos sobre CURP, dirección, estado de salud o datos personales ilustran decisiones de alcance y obligatoriedad. La sesión no fijó todos esos datos como requisitos del sistema escolar.
- La transcripción automática alterna formas como “CUR”, “CURP”, “corp” y “curve”. Por el desarrollo del ejemplo se interpreta como **CURP** [reconstrucción contextual].
- En el ejemplo de disponibilidad de libros, el valor `TRUE` indica que el ejemplar está en estantería y `FALSE` que está prestado. La explicación también menciona ejemplares perdidos o destruidos, pero no define un valor distinto para esos estados; esa distinción quedaría pendiente si se aplicara el ejemplo a un diseño real.
- El docente recomendó evitar datos vacíos y describir los opcionales. La representación de ausencia, de “no aplica” y de un dato inválido debe quedar clara en las reglas de cada sistema; la sesión no especificó una única convención técnica para todos los casos.
- La transcripción menciona extensiones `.wsd`, `.uml` y `.puml` de manera variable. La indicación constante fue usar archivos fuente que pueda abrir el complemento de UML en Visual Studio Code y compararlos con el diagrama presentado.
- La fecha de entrega y el calendario de presentaciones se anotan como instrucciones comunicadas en clase; no se han contrastado con avisos posteriores.

### 5️⃣ 🧠 Conclusión de la clase

La sesión vinculó los casos de uso con la identificación de entidades y la especificación del diccionario de datos. El proyecto requiere acordar nombres entre módulos, justificar el alcance de los datos y documentar con claridad sus tipos y reglas. Como trabajo siguiente, el grupo debía atender las actividades publicadas, completar e integrar la documentación y los diagramas en `develop`, y prepararse para explicar el módulo y sus relaciones con el resto del sistema.

### 6️⃣ ✅ Síntesis final

- Extraer y depurar sustantivos de los casos de uso permite proponer elementos del modelo.
- Homologar términos reduce discrepancias entre módulos.
- El diccionario precisa significado, tipo, restricciones y reglas de cada dato.
- La calidad de los datos depende de su integridad, consistencia, exactitud, completitud y validez.
- El proyecto final requiere documentación integrada y comprensión del sistema completo.

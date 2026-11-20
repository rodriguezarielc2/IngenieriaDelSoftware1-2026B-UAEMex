# Clase 23: Patrones de análisis y reusabilidad

### 1️⃣ 📘 Identificación

- **Tema principal:** formalización del análisis de sistemas mediante patrones, técnicas y componentes reutilizables.
- **Subtemas y actividades:** identificación de estructuras y flujos; patrones en cuadrículas; límites del sistema; requisitos funcionales y no funcionales; análisis de negocio, estructurado, orientado a objetos y de datos; reusabilidad; revisión de la documentación del proyecto final.
- **Propósito de aprendizaje:** describir con precisión qué necesita un sistema, cómo se relacionan sus partes y qué técnicas permiten analizarlo de manera consistente.

### 2️⃣ 📝 Resumen explicativo

**Estructuras, reglas y límites.** El profesor comenzó relacionando la documentación con la necesidad de ordenar el análisis. Un patrón de análisis se presentó como una representación formal de estructuras identificadas en los sistemas. Además de reconocer las piezas, hay que explicar sus flujos, reglas de ejecución y condiciones de uso. La documentación debe permitir entender qué se necesita antes de decidir la solución técnica.

Para ilustrarlo se observaron cuadrículas de colores. En la rosa se describió una alternancia de casillas y una fila completamente coloreada. Se preguntó qué ocurriría al agregar una cuarta fila. La extrapolación parecía razonable según el patrón observado, pero el profesor aclaró que la extensión depende de los límites y reglas del sistema: si no se admite otra fila, hay que justificar esa restricción. En la cuadrícula azul se identificaron desplazamientos y repeticiones. Las diferentes cuadrículas sirvieron para comparar sistemas con comportamientos distintos; no se asignó formalmente programarlas.

**Requisitos y contexto.** Se relacionaron los resultados esperados con los requisitos funcionales y las condiciones de calidad con los no funcionales. El profesor vinculó eficacia con resolver correctamente y con rapidez, y eficiencia con optimizar los recursos utilizados. Los ejemplos sobre recursos finitos y centros de datos principal y de respaldo ilustraron que el entorno influye en las decisiones. No se establecieron ubicaciones de servidores ni infraestructura obligatoria para el proyecto escolar.

El profesor agrupó los patrones en análisis de requisitos, modelado de datos y análisis orientado a objetos; el material visual también menciona patrones de límites. Recordó que el grupo ya estaba utilizando estas ideas al formular requisitos y modelos estáticos y dinámicos. El modelado de datos se retomaría en clases posteriores. Los módulos deben funcionar de manera coherente: casos de uso duplicados, requisitos contradictorios o términos sin definir —como “recursos”— dificultan la integración. Cuando algo no se conoce, corresponde investigarlo y conceptualizarlo.

**Análisis de negocio y requisitos.** Se explicó que el analista necesita conocer el propósito de la organización, sus servicios, usuarios, reglas y procesos. La matriz CRUD permite identificar qué entidades se crean, consultan, actualizan o eliminan y relacionar esas operaciones con su ciclo de vida. El análisis de casos de uso permite precisar actores, permisos e interacciones, incluidos flujos principales y alternativos. El mapeo de procesos describe los pasos de una actividad; se ilustró con la producción y distribución de una bebida. También se describieron entrevistas y sesiones con usuarios, operadores y responsables para obtener información del negocio. La expresión transcrita como “talleres de licitación” es dudosa; la explicación que la sigue corresponde a obtención de información mediante preguntas y entrevistas.

**Análisis estructurado y de sistemas.** Se revisaron flujos de datos y procesos, el análisis de causa raíz y FODA. El método de los cinco porqués se ilustró con un diagnóstico que parte de una falla general y busca su origen mediante preguntas cada vez más específicas. FODA se presentó como apoyo para valorar fortalezas, oportunidades, debilidades y amenazas, y orientar prioridades según los objetivos de la organización. Los ejemplos fueron explicaciones de las técnicas, no diagnósticos realizados al SCE.

**Análisis orientado a objetos y arquitectura.** El profesor explicó la descomposición de problemas complejos en partes y subpartes. Se retomaron modelos UML estáticos y dinámicos: clases, secuencia, actividades y máquinas de estados. El análisis de dominio relaciona objetos y operaciones con conceptos y reglas del negocio, de modo que los nombres permitan comprender su responsabilidad. Los ejemplos de alumnos, profesores, aulas e inscripciones mostraron esa relación con el dominio escolar. Finalmente, el análisis de impacto y dependencias permite estudiar cómo un cambio afecta otras funciones, módulos y usuarios; se retomó como ejemplo la evaluación de versiones de prueba de una plataforma.

**Análisis de datos y estructuras.** Se enfatizaron integridad, consistencia y calidad de la información almacenada. Se comparó el uso de tipos de datos y recursos de almacenamiento mediante un servidor hipotético con capacidades limitadas. La normalización se relacionó con reducir redundancias y dependencias anómalas. El análisis de dependencias funcionales estudia relaciones entre atributos para organizar los datos. Como advertencia para el proyecto, se señaló que repetir datos del alumno o del profesor en Inicio de Sesión puede introducir redundancia cuando esos datos corresponden a su entidad principal. La decisión concreta debe revisarse con las relaciones del modelo.

**Reusabilidad.** Se definió como la capacidad de diseñar, construir y empaquetar componentes para utilizarlos en distintos contextos, con las adaptaciones necesarias. Se mencionaron funciones, clases, bibliotecas, dependencias, JDK, npm, Gradle y Maven. La reutilización también puede darse en componentes de interfaz, modelos y patrones. Se utilizó la analogía de una armadura adaptable a diferentes personas para explicar entradas y características configurables; esa analogía no sustituye un modelo de arquitectura. Una interfaz CRUD compartida entre módulos se propuso como ejemplo de reutilización de estructuras.

**Indicaciones del proyecto.** Al cierre, el profesor informó que había revisado PR y dejado comentarios. Solicitó completar módulos y README, revisar aportaciones de otros equipos y resolver discrepancias mediante discusión. Para las siguientes revisiones reiteró que los diagramas deben incluir código fuente UML e imágenes. Indicó que también depuraría material ya aceptado si incumplía lo solicitado. Pidió una presentación homogénea en Markdown, títulos claros, imágenes visibles y descripciones suficientes; mencionó posibles puntos extra por mejorar el formato. No fijó en esta sesión una nueva fecha de entrega.

### 3️⃣ 🧩 Conceptos teóricos y técnicos relevantes

| Concepto | Explicación trabajada en la sesión |
|---|---|
| Patrón de análisis | Representación formal de estructuras o comportamientos reconocidos al estudiar un sistema. |
| Límite del sistema | Restricción que delimita qué elementos, condiciones o extensiones admite el análisis. |
| CRUD | Crear, leer o consultar, actualizar y eliminar; operaciones que se relacionan con entidades y sus estados. |
| Caso de uso | Interacción orientada a un objetivo entre actores y sistema, con condiciones y alternativas. |
| Mapeo de procesos | Descripción ordenada del flujo de trabajo para realizar una actividad. |
| Causa raíz | Búsqueda del origen de un problema mediante diagnóstico y preguntas sucesivas. |
| FODA | Análisis de fortalezas, oportunidades, debilidades y amenazas para apoyar decisiones. |
| Análisis de dominio | Uso de conceptos y reglas del negocio para organizar responsabilidades y modelos. |
| Impacto y dependencias | Estudio de los efectos de un cambio sobre partes relacionadas del sistema. |
| Normalización | Organización de los datos orientada a reducir redundancias y anomalías. |
| Dependencia funcional | Relación entre atributos que ayuda a definir la estructura de los datos. |
| Reusabilidad | Preparación de componentes o estructuras para utilizarlos en distintos contextos. |

### 4️⃣ ⚠️ Problemas, errores o aclaraciones del profesor

- Un patrón observado no autoriza extender el sistema sin revisar sus límites. La cuarta fila del ejercicio fue una hipótesis para discutir esa condición.
- Los conceptos no definidos, las funciones duplicadas y los requisitos incompatibles deben resolverse mediante análisis y coordinación.
- La transcripción contiene términos dudosos: “talleres de licitación”, “modelado dinámico y estético” y “SAI” en un pasaje sobre centros de datos. Se conservaron como incertidumbres; el contexto permite identificar entrevistas, modelado estático y un sitio de respaldo, respectivamente.
- Las comparaciones de tipos de datos y ubicaciones de centros de datos se expusieron como ejemplos. No constituyen mediciones ni decisiones de infraestructura del proyecto.
- El profesor empleó rapidez al explicar eficacia. Este resumen registra esa formulación de la sesión; no establece una definición normativa externa.
- La frase de cierre sobre PR “aceptados” y “rechazados” no permite determinar el estado actual de cada PR. Debe consultarse GitHub antes de tratar una aportación como integrada.
- Tener un cambio aceptado no exime de corregirlo si carece de fuente UML, imagen, coherencia o el formato solicitado.

### 5️⃣ 🧠 Conclusión de la clase

La sesión formalizó técnicas que el grupo ya había utilizado: comprender el negocio, describir flujos, abstraer objetos y organizar datos. Se insistió en mantener coherencia entre módulos y aprovechar estructuras reutilizables. Para el proyecto se pidió completar la documentación, atender comentarios de PR, revisar el trabajo de otros equipos e integrar diagramas con fuente e imagen y una presentación uniforme. El modelado de datos continuaría en clases posteriores.

### 6️⃣ ✅ Síntesis final

Los patrones ayudan a formalizar estructuras, flujos y límites del sistema.\
Las técnicas de negocio, sistemas, objetos y datos se complementan.\
La reusabilidad permite adaptar componentes y modelos existentes.\
El proyecto debe resolver duplicidades y mantener coherencia entre módulos.\
Los diagramas requieren fuente UML, imagen y documentación homogénea.

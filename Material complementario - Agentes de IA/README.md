# Agentes de IA: método de cuatro pasos

Síntesis de las dos transcripciones proporcionadas de un mismo video. El contenido se presenta como la propuesta del expositor; no como una norma general ni como una instrucción oficial de la asignatura.

## 1️⃣ 📘 Identificación

- **Tema principal:** organización de un agente de IA mediante archivos, carpetas e instrucciones reutilizables.
- **Subtemas:** contexto, memoria, habilidades (*skills*), carpetas de proyecto, elaboración iterativa de presupuestos y generación de una experiencia 3D.
- **Propósito del tutorial:** mostrar un flujo de trabajo para automatizar tareas repetitivas y reutilizarlo con distintas herramientas de IA.

## 2️⃣ 📝 Resumen explicativo

### Paso 1. Preparar la carpeta del agente

El expositor propone crear una carpeta para el agente con cuatro áreas:

- **Contexto:** información estable de la organización, como tarifas, catálogo, condiciones de trabajo y tono de comunicación.
- **Skills:** procedimientos paso a paso para tareas concretas.
- **Memoria:** criterios y correcciones que conviene conservar para trabajos futuros.
- **Proyectos:** una subcarpeta por cliente o encargo, con sus documentos, medidas y planos.

La carpeta se acompaña con un archivo de instrucciones que el video llama `Agents.md`. Ahí se explica a la IA qué función cumple el agente y cómo usar el resto de la información. El expositor destaca dos pautas: preguntar cuando falten datos y conservar los criterios que sean útiles después.

### Paso 2. Resolver una tarea manualmente

El ejemplo es un estudio de reformas que prepara presupuestos. El expositor conecta la carpeta con un proyecto de ChatGPT y pide elaborar un presupuesto usando las instrucciones y los archivos del cliente. Cuando la herramienta plantea dudas, el usuario responde y aporta criterios para el encargo: cómo tratar la puerta de una cocina abierta, considerar la nivelación del suelo y estimar contenedores para residuos, dejando esta última estimación para validación manual.

La primera versión se entrega en HTML y Excel, pero mezcla estancias con trabajos de distintos oficios. El expositor corrige el resultado y especifica que el presupuesto debe organizarse por oficio, reunir suministro y colocación en una sola partida con un precio y seguir los criterios de medición que indica. La versión revisada se presenta con ocho capítulos por oficio y 23 partidas.

### Paso 3. Convertir las correcciones en habilidades reutilizables

El video muestra que, después de las correcciones, la herramienta agrega algunos criterios a la memoria. El expositor distingue esa memoria —que registra observaciones en orden cronológico— de una *skill*, que organiza las reglas como un procedimiento secuencial para repetir una tarea.

Luego pide crear una habilidad para elaborar presupuestos a partir de los criterios discutidos. La herramienta guarda la habilidad en la carpeta `Skills`. En la misma conversación se amplía el ejemplo: se solicita un recorrido 3D interactivo del inmueble, con estados antes y después de la reforma, elementos seleccionables y acceso al desglose del presupuesto. Tras simplificar la representación, el video muestra una segunda habilidad para crear recorridos, acompañada de referencias y recursos gráficos.

### Paso 4. Reutilizar el agente con otra herramienta

Para un segundo proyecto, el expositor carga los archivos del nuevo cliente en `Proyectos` y abre la carpeta del agente con Claude Cowork —nombre que aparece transcrito de distintas formas—. Con una instrucción, la herramienta produce un presupuesto en Excel, otro en HTML y un recorrido 3D interactivo. El video usa esta demostración para ilustrar la reutilización de la misma estructura y los mismos procedimientos en más de una herramienta.

El material también incluye un segmento patrocinado sobre Mammoth AI. Ahí se describen modelos y funciones disponibles en ese servicio; sus afirmaciones comerciales, de privacidad y de almacenamiento no se verifican en esta síntesis.

## 3️⃣ 🧩 Conceptos teóricos y técnicos relevantes

- **Contexto:** información de referencia que condiciona cómo se realiza el trabajo.
- **Memoria:** registro acumulativo de criterios aprendidos o proporcionados durante el uso.
- **Skill o habilidad:** procedimiento reutilizable que ordena criterios y pasos para resolver una tarea.
- **Carpeta de proyecto:** espacio con los datos particulares de un encargo; se mantiene separado del contexto general.
- **Instrucciones del agente:** reglas que indican a la herramienta cómo actuar y consultar los archivos. El video llama `Agents.md` al archivo principal.
- **Iteración:** probar la tarea, revisar el resultado, corregirlo y convertir las correcciones útiles en instrucciones reutilizables.

## 4️⃣ ⚠️ Problemas, errores o aclaraciones

- Las dos transcripciones corresponden al mismo contenido, pero presentan diferencias de puntuación y reconocimiento de voz. En ambas aparecen errores como “gente” donde el contexto indica “agente”; se consolidaron como variantes, sin tratar cada archivo como una sesión distinta.
- Algunos nombres de herramientas aparecen transcritos como “Cloud” o con otras variaciones. Se conserva la referencia a Claude Cowork con esa aclaración.
- La explicación de la nivelación del suelo no conserva con claridad todos los detalles de su alcance. No se infieren cantidades ni unidades que no queden explícitas.
- La estructura de carpetas y el nombre `Agents.md` corresponden al método presentado por el expositor; la transcripción no demuestra que sean requisitos universales ni que todas las herramientas los procesen igual.
- La incorporación de correcciones que se observa en el ejemplo depende de instrucciones y funciones de la herramienta usada; el video no demuestra que cualquier agente aprenda automáticamente sin configuración.
- El ejemplo de presupuestos y reformas es demostrativo. Sus criterios no deben asumirse como reglas técnicas o contractuales para un proyecto real.

## 5️⃣ 🧠 Conclusión

El método propuesto organiza un agente con contexto, memoria, habilidades e información de cada proyecto. Primero se ejecuta una tarea y se corrigen sus resultados; después, los criterios que conviene repetir se convierten en habilidades. El último paso consiste en reutilizar la estructura con otra herramienta y otro proyecto. El expositor cierra recomendando un video posterior sobre gestión del conocimiento, cuyo contenido no aparece en estas transcripciones.

## 6️⃣ ✅ Síntesis final

Organizar la información del agente en contexto, memoria, habilidades y proyectos.
Probar la tarea manualmente y corregir el resultado con criterios explícitos.
Convertir las correcciones útiles en procedimientos reutilizables.
Reutilizar la estructura con otro proyecto y otra herramienta, verificando sus resultados.

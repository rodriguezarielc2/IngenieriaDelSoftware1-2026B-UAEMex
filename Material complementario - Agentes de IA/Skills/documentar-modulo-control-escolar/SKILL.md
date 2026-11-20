---
name: documentar-modulo-control-escolar
description: Analiza y documenta un módulo del proyecto final de Ingeniería de Software I, verificando requisitos, modelos y dependencias con el sistema de control escolar.
---

# Documentar un módulo del sistema de control escolar

## ¿Cuándo usar esta habilidad?

Úsala cuando el usuario solicite analizar, crear o revisar la documentación de un módulo del proyecto final. El repositorio de apuntes y el repositorio de entrega pueden ser distintos; confirma la ubicación antes de editar archivos.

## Fuentes necesarias

Antes de escribir, localiza y consulta:

1. El repositorio del proyecto final y su template más reciente.
2. El README general, los documentos de los módulos relacionados y sus cambios recientes.
3. Las instrucciones y transcripciones de clase relacionadas con el requisito, priorizando las indicaciones más recientes del docente.
4. `../../Agents.md` y `../../Memory.md` para conocer reglas de trabajo y decisiones previas.

Si falta una fuente importante o su versión es dudosa, informa la limitación y pregunta antes de presentar una propuesta como definitiva.

## Procedimiento

1. **Delimita el encargo.** Identifica el módulo, su propósito, el usuario, la ubicación del archivo y el template vigente. Si el nombre o la responsabilidad del módulo no están confirmados, márcalos como pendientes.
2. **Parte del problema y la evidencia.** Describe el contexto, los actores, las necesidades observadas, el alcance y las exclusiones. No conviertas opiniones sobre el sistema actual en hechos sin evidencia de entrevistas, encuestas, observación o documentos.
3. **Actualiza el mapa de módulos.** Comprueba dependencias, datos y servicios compartidos. La lista de seis módulos de la clase 13 es una distribución inicial; las clases posteriores discutieron periodos, grupos/aulas, catálogo de exámenes y autenticación común. Verifica cuáles quedaron en el diseño vigente antes de asignar responsabilidades.
4. **Especifica entradas, procesos y salidas.** Para cada función, indica qué información entra, qué proceso ocurre, qué resultado sale y qué módulo produce o consume los datos. Señala dependencias que falten.
5. **Redacta requisitos verificables.** Separa requisitos funcionales de no funcionales. Expresa cada requisito desde la necesidad del usuario, evita duplicados y agrega criterio de aceptación solo cuando haya información suficiente para definirlo.
6. **Respeta los niveles del sistema.** Mantén los requisitos generales del sistema en nivel 0, los de cada módulo en nivel 1 y el detalle de funciones o procesos en nivel 2. No profundices más allá del nivel 2, según la indicación registrada en la clase 21, salvo que una instrucción vigente lo cambie.
7. **Elabora modelos pertinentes.** Usa actores y casos de uso para la vista externa; contexto y flujo de datos para entradas, salidas y límites; clases y componentes para estructura; y secuencia, actividades o estados para comportamiento. Incluye solo elementos respaldados por requisitos y por el comportamiento del módulo.
8. **Resuelve las reglas de diagramación con el template vigente.** Las notas de clase 19 y 21 describen conjuntos parcialmente distintos para cada caso de uso. Si el template actual no resuelve cuál aplica, documenta la discrepancia y pregunta antes de completar diagramas en lote.
9. **Revisa la integración.** Comprueba que actores, roles, permisos, datos, CRUD, transiciones de estado, nombres y responsabilidades no contradigan a otros módulos. Revisa también la tabla común de actores/roles/permisos cuando exista.
10. **Entrega e integra la documentación.** Sigue las pautas de presentación del proyecto, conserva los diagramas legibles en el tamaño requerido, enlaza el archivo desde el índice general y deja claras las decisiones pendientes. Actualiza `../../Memory.md` cuando haya decisiones o avances relevantes comprobados, conforme al mantenimiento autorizado en el manual. No hagas commit o push salvo petición explícita.

## Estructura sugerida del documento de módulo

Adáptala al template vigente; no la impongas si el proyecto ya tiene una estructura:

1. Propósito, objetivo, alcance y exclusiones.
2. Actores, roles y permisos pertinentes.
3. Requisitos funcionales y no funcionales.
4. Datos de entrada, procesos, salidas y dependencias.
5. Casos de uso y reglas de negocio respaldadas.
6. Modelos y diagramas requeridos por la plantilla actual.
7. Dudas, supuestos pendientes y fuentes consultadas.

## Comprobación de calidad

- Cada requisito tiene fuente o está claramente marcado como propuesta.
- No se confundieron ejemplos de clase con funciones del sistema escolar.
- Los límites del sistema, actores y responsabilidades de módulo son consistentes.
- Las dependencias de datos y servicios compartidos están explícitas.
- Los diagramas representan la misma versión de los requisitos y son legibles.
- El documento está enlazado desde el README general y los puntos abiertos no se presentan como resueltos.
- Se revisaron la puntuación y los signos de apertura y cierre en español de México, incluidos los encabezados formulados como preguntas. Se distinguieron las preguntas directas de las interrogativas indirectas.

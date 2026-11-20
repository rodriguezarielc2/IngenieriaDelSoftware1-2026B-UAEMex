# Preparación de la copia pública

## Fuente y alcance

- Archivo fuente: `Encuesta SCE _ Experiencia Estudiantil (respuestas).xlsx`.
- SHA-256: `eeba3df9e4ac7feac1205a0a6df1dad6d991915d02e621889bc9f092692ca202`.
- Corte documental: 19 de noviembre de 2026.
- Se conservaron 194 envíos y las diez preguntas abiertas de experiencia estudiantil, equivalentes a 1940 celdas de respuesta con contenido. Tener contenido no significa que la respuesta sea válida para cualquier análisis.

## Transformaciones

| Elemento | Tratamiento | Motivo |
|---|---|---|
| Nombre | Retirado | Identificador directo. |
| Marca temporal | Retirada | Evitar identificar un envío por fecha y hora. |
| Edad y semestre | Retirados | Reducir combinaciones que puedan identificar a una persona. |
| Carrera y plantel | Retirados | Reducir identificación por contexto académico. |
| Integrante que invitó a responder | Retirado | No se necesita para el análisis público de necesidades. |
| Columna vacía | Retirada | No aporta datos. |
| Diez preguntas de experiencia | Conservadas como P1–P10 | Mantener significado y trazabilidad de la evidencia. |
| Orden y números de fila originales | Sustituidos | Se asignaron IDs nuevos y se mezcló el orden. |
| Libro, anotaciones y metadatos originales | No se trasladaron | Se generó un libro nuevo a partir del contenido preparado. |

El original permanece fuera del repositorio. La correspondencia entre IDs y filas de origen es un material privado de preparación y tampoco se publica.

## Revisión del texto libre

Se aplicó una búsqueda de nombres disponibles en la columna de identificación, correos, enlaces y secuencias numéricas que pudieran ser identificadores. Después se leyeron las diez respuestas de cada uno de los 194 envíos para localizar referencias personales o contextuales que no detectara esa búsqueda.

Se modificaron 17 celdas de texto: se omitió un nombre de personal, se generalizaron referencias a carrera o espacio académico y antigüedad personal, se retiró un servicio personal y se generalizó un relato administrativo con detalles particulares. Las omisiones o generalizaciones se señalan con corchetes; algunas referencias de contexto se sustituyen por expresiones generales como “coordinación de carrera” o “espacio académico”. No se eliminó el envío completo por contener una referencia personal.

Se conservaron errores de escritura, negaciones, opiniones y respuestas poco interpretables. Las modificaciones no corrigen los juicios sobre el sistema ni convierten una opinión en un hecho técnico. Se conservaron denominaciones generales de servicios e instituciones cuando son necesarias para entender una necesidad.

## Alcance y revisión posterior

La revisión elimina los identificadores directos detectados y reduce el contexto personal. Un relato libre puede ser reconocible para quien conozca el incidente; la copia no permite garantizar anonimato absoluto. Si un participante identifica un fragmento que deba retirarse, se revisa esa celda y se publica una versión corregida, registrando el cambio sin revelar la identidad.

La copia pública se revisó para comprobar número de envíos, correspondencia de preguntas, ausencia de columnas retiradas, ausencia de comentarios/enlaces externos heredados y conservación de valores respecto al conjunto preparado. El formato se revisó mediante vistas de las tres pestañas. No se ejecutaron macros ni se abrió el archivo en Excel para certificar funciones de la aplicación; el libro contiene datos y un conteo de registros.

# PR-003 local: datos, reglas e integración de Profesores

**Tarea:** T06 para E3 y decisiones D03/D07. **Estado:** propuesta concreta para revisión de E3, E1 y consumidores; sin PR oficial enviado.\
**Base revisada:** `553104011ece92aeeeecfe54298173bfb88e102f`.\
**Destino:** agregar una sección al final de `modulos/m3_profesores.md`, conservando su contenido actual.

## Propósito

La clase 22 pidió precisar datos, metadatos y condiciones. El módulo ya enumera datos básicos y baja lógica, pero no define su estructura ni distingue exactamente qué datos modifica el profesor. Se propone una sección que hace visibles esos acuerdos pendientes y organiza lo que los equipos deben decidir antes de producir todos los diagramas.

## Revisión y dependencias

1. E3 valida datos y obligatoriedad con su fuente de requisitos. La encuesta estudiantil no justifica por sí sola recopilar teléfono o especialidad de profesores.
2. E1/E3 acuerdan cómo se vincula una cuenta con el perfil y si la identificación externa debe distinguirse del ID interno.
3. E3 y consumidores acuerdan estado del docente, referencias históricas y responsables de asignarlo a grupos o materias.
4. E3 aclara la edición del perfil: RF-07 frente a RNF-01. La nueva sección expone una propuesta; si se aprueba, también deben ajustarse los requisitos y modelos afectados.

El paquete contiene texto propio para esa sección; no replica el documento oficial. Es revisable como propuesta, pero no debe presentarse como un diccionario de datos cerrado mientras existan campos por acordar. No incluye los diagramas faltantes ni da por implementada una base de datos.

**URL del PR enviado:** pendiente. **Responsable de revisión y envío:** E3, pendiente de aceptación interna.

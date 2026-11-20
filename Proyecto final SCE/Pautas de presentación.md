# Pautas de presentación

Guía propuesta para los documentos y aportaciones del proyecto SCE. La [plantilla vigente del profesor](https://github.com/wichis/26b_is1_proyecto-final/blob/develop/modulos/m0-NOMBRE_MODULO.template.md) y sus indicaciones tienen prioridad. Los apuntes de clase conservan su formato propio.

## Formato común

| Elemento | Pauta |
|---|---|
| Títulos | Un título principal `#` por archivo; secciones `##` y subsecciones `###`, sin saltar niveles. Usar mayúscula inicial. Numerar solo cuando lo requiera la estructura del entregable. |
| Redacción | Español claro, párrafos breves y una idea por párrafo. Explicar las siglas al primer uso. |
| Énfasis | Negritas para conceptos o estados importantes; código entre comillas invertidas para rutas, identificadores y sintaxis. Evitar emojis, adornos y mayúsculas sostenidas en documentos del proyecto. |
| Listas y tablas | Listas para pasos o enumeraciones; tablas para comparar elementos del mismo tipo. Encabezados claros y una fila por elemento. |
| Espaciado | Dejar una línea en blanco después de títulos y antes de listas, tablas y bloques de código. |
| Archivos y enlaces | Nombres descriptivos y rutas relativas dentro del repositorio. Conservar las rutas oficiales; acordar cualquier renombre con los equipos afectados. |

## Organización del contenido

- **README:** propósito breve e índice. Las tareas van en el plan, los detalles técnicos en el módulo y las fuentes en el documento correspondiente. Evitar explicar lo mismo en varios lugares.
- **Módulos:** conservar los apartados y el orden de la plantilla oficial. Integrar datos, metadatos y reglas en secciones identificables conforme a las indicaciones vigentes.
- **Requisitos y casos de uso:** usar identificadores estables y mencionar el módulo para evitar ambigüedad. Mantener los nombres en texto, tablas y diagramas.
- **Diagramas:** título descriptivo, enlace al archivo fuente UML, imagen visible con texto alternativo y una explicación breve. Deben poder leerse en tamaño carta. La plantilla exige componentes y secuencia por caso de uso, además de los otros modelos que especifica.
- **Fuentes y pendientes:** distinguir hechos respaldados, testimonios y propuestas. Escribir las decisiones pendientes en un apartado propio. Citar la clase o evidencia necesaria sin repetir sus apuntes dentro del proyecto.

## Estado del trabajo

Usar **Por iniciar**, **En preparación**, **En revisión**, **PR enviado** e **Integrado**. Este último requiere comprobar que el cambio se incorporó a `develop`. Los responsables de tareas compartidas deben aceptar su asignación.

## Antes de compartir

- [ ] El contenido sigue la plantilla aplicable y estas pautas.
- [ ] Los enlaces e imágenes abren y los diagramas incluyen su fuente.
- [ ] Actores, términos e identificadores coinciden con los módulos relacionados.
- [ ] Las fuentes y decisiones pendientes son claras y se retiraron datos personales innecesarios.
- [ ] El PR describe el cambio real en menos de 50 palabras y el commit tiene menos de 24, conforme al [template oficial](https://github.com/wichis/26b_is1_proyecto-final/blob/develop/.github/PULL_REQUEST_TEMPLATE.md).

# Diagnóstico y pendientes

**Corte:** 19 de noviembre de 2026. **Versión examinada:** `develop`, `553104011ece92aeeeecfe54298173bfb88e102f`. Se revisa lo integrado; los PR abiertos se registran como aportaciones pendientes. La referencia es documental, no una ejecución de software ni una calificación de los equipos.

## Faltantes generales

| Hallazgo | Consecuencia | Trabajo asociado |
|---|---|---|
| README con títulos vacíos y marcas TODO en contexto, alcance, RF/RNF y modelos generales | No permite explicar propósito, límites ni requisitos del sistema completo | T02, T03, T05, T09 |
| Índice solo enlaza Inscripciones y Asignaturas, pese a nueve documentos de módulo | Parte del trabajo existente no es accesible desde la entrada principal | PR-001 |
| Varios diagramas generales de contexto están guardados, pero falta elegir e integrar una vista común | Se conservan versiones con conceptos o supuestos diferentes | T04, T09 |
| Matriz común de roles y permisos ausente; Inicio de Sesión sigue en PR | Permisos y dependencia de autenticación no están cerrados | T04, T05 |
| Falta un diccionario de datos y un modelo entidad-relación general integrados | No quedan fijadas claves, cardinalidades ni reglas compartidas | T06, T09 |
| Los documentos de módulos no cubren todavía componentes/secuencias por CU, estados y clases según plantilla | El análisis no alcanza la cobertura de modelado solicitada | T07, T08 |
| Nombres o IDs ambiguos: m02 para Periodo, “Módulo 2” para Inscripciones y m8 para Aulas y Calificaciones | Confusión al relacionar requisitos, archivos y modelos | T04, T11; acordar nomenclatura antes de renombrar |
| Falta contenido en interfaz (mockups/wireframes) del README | No hay una vista común de interacción documentada en esa sección | T10 |

## Estado por módulo

| Módulo / archivo oficial | Lo que existe | Principal faltante |
|---|---|---|
| [Alumnos](https://github.com/wichis/26b_is1_proyecto-final/blob/553104011ece92aeeeecfe54298173bfb88e102f/modulos/m1_alumnos.md) | Esquema de secciones y texto UML de casos de uso | Resumen, objetivo, alcance, RF/RNF y glosario vacíos; resolver PR #48/#51 y fuente/imagen. |
| [Inscripciones](https://github.com/wichis/26b_is1_proyecto-final/blob/553104011ece92aeeeecfe54298173bfb88e102f/modulos/modulo-inscripciones.md) | Propósito, actores, funciones, RNF e imagen de casos de uso | Fuente UML enlazada, IDs, datos, flujos/modelos y límites con Periodos y grupos. |
| [Periodos](https://github.com/wichis/26b_is1_proyecto-final/blob/553104011ece92aeeeecfe54298173bfb88e102f/modulos/m02_periodo.md) | Resumen, alcance, RF/RNF y actores | Sección de imagen anuncia integración futura aunque el PNG ya existe; enlazarlo, revisar reglas temporales y datos. |
| [Profesores](https://github.com/wichis/26b_is1_proyecto-final/blob/553104011ece92aeeeecfe54298173bfb88e102f/modulos/m3_profesores.md) | 8 RF, 7 RNF, actores, 6 CU, PlantUML embebido e imagen | Datos/reglas, modelos restantes, enlaces a fuentes y resolución de permisos de edición; explicar asteriscos. |
| [Asignaturas](https://github.com/wichis/26b_is1_proyecto-final/blob/553104011ece92aeeeecfe54298173bfb88e102f/modulos/m4_asignaturas.md) | Alcance, 13 RF, actores, RNF y casos de uso | Datos, reglas del plan/seriación y dependencias con oferta, grupos y avance; RNF verificables. |
| [Calendario](https://github.com/wichis/26b_is1_proyecto-final/blob/553104011ece92aeeeecfe54298173bfb88e102f/modulos/m5_calendarioExs.md) | RF, 8 CU descritos, casos de uso y contexto | Hacer corresponder CU con RF, acordar ventanas y publicación; datos y modelos de detalle. #55 propone ajustes. |
| [Aulas](https://github.com/wichis/26b_is1_proyecto-final/blob/553104011ece92aeeeecfe54298173bfb88e102f/modulos/m8_Aulas.md) | Funciones, 8 CU, casos de uso y contexto | Homologar actores con CU; definir recursos, reservas, datos y relación con grupos. #55 propone ajustes. |
| [Calificaciones](https://github.com/wichis/26b_is1_proyecto-final/blob/553104011ece92aeeeecfe54298173bfb88e102f/modulos/m8_calificaciones.md) | RF, actores, RNF, casos de uso y reglas de integración | Especificar entidades, estados y condiciones de actas/rectificaciones; citar reglas académicas aplicables. |
| [Catálogo de exámenes](https://github.com/wichis/26b_is1_proyecto-final/blob/553104011ece92aeeeecfe54298173bfb88e102f/modulos/m9_catalogo_examenes.md) | RF, actores, RNF, casos de uso y reglas de integración | Metadatos, vigencia y versiones de reglas; modelos y fuente normativa de criterios. |
| Inicio de Sesión | [PR #47](https://github.com/wichis/26b_is1_proyecto-final/pull/47) abierto | No está integrado en la base revisada; acordar perfil/cuenta y compatibilidad con los demás roles. |
| Grupos | Responsabilidad mencionada con E5 en `teams-info.md`; consumido por varios módulos | No hay documento propio en la base revisada; acordar si será módulo o entidad administrada por otro. |

Los bloques PlantUML de Profesores sí contienen código. El pendiente es su integración conforme al formato de fuentes y la cobertura de modelos restante; no debe confundirse con una ausencia total de código.

## Problemas concretos de consistencia que deben resolverse

- **Profesores:** RF-07 permite al profesor actualizar datos propios, pero RNF-01 dice que solo el administrador puede modificar profesores sin precisar campos. Debe distinguirse edición de datos de contacto frente a datos administrados por la institución. Sin esa distinción, los permisos se contradicen.
- **Aulas:** los casos de uso mencionan consultas de alumnos y profesores que no figuran de la misma manera en la lista de actores. El sistema automatizado debe situarse dentro o fuera del límite con una justificación; no basta con tratar una validación interna como usuario externo.
- **Calificaciones y Catálogo:** bitácora, rectificaciones o validación de claves aparecen agrupadas como RNF. Revisar qué describe una función o regla y qué expresa una calidad o restricción. Conservar la necesidad al reclasificarla.
- **Requisitos de calidad:** “pocos pasos”, “alta demanda” o “tiempo adecuado” necesitan condiciones para evaluarse. Los valores de 2, 3 o 5 segundos que aparecen en documentos requieren fuente o acuerdo y escenario de carga; la encuesta no fija esos umbrales.
- **Arquitectura:** caché, colas, APIs y proveedor de identidad aparecen en algunas vistas. Acordar cuáles son decisiones respaldadas y cuáles propuestas; la percepción de lentitud no demuestra que una cola, más servidores o cierta tecnología sea la solución necesaria.

## ¿Qué aporta la encuesta?

La [lectura exploratoria](<Encuestas/Análisis de resultados.md>) permite respaldar necesidades con testimonios concretos: uso móvil, elección de horarios/cupos, interrupciones, ubicación de información y seguimiento de trámites. También contiene experiencias positivas y solicitudes fuera del alcance actual. No permite diagnosticar causas técnicas, medir tiempos reales, probar fallas de seguridad ni justificar porcentajes de prevalencia sin un método de codificación y muestreo adicional.

## Cobertura de fuentes

Este diagnóstico se apoya en archivos del commit indicado y las clases 21–23. Las revisiones futuras deben comprobar cambios en `develop`, comentarios del docente y acuerdos del grupo. Los criterios de cierre están en el [plan](<Plan de trabajo.md>); este documento registra evidencia de pendientes, no asigna una calificación de cumplimiento.

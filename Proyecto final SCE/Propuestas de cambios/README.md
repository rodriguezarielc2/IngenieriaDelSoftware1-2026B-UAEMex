# Propuestas de cambios para el repositorio oficial

Aquí se preparan aportaciones propias para revisión del equipo. **Ningún paquete de esta carpeta se ha enviado como PR al profesor.** Las carpetas `PR-001`, `PR-002` y `PR-003` son identificadores locales; no corresponden a números de GitHub.

Al redactar una aportación, seguir las [pautas de presentación](<../Pautas de presentación.md>).

## Paquetes iniciales

| Paquete | Objetivo | Estado | Coordinación necesaria |
|---|---|---|---|
| [PR-001 — Índice de módulos](<PR-001 - Índice de módulos/README.md>) | Hacer accesibles los nueve módulos integrados desde el README | Contenido y descripción preparados; pendiente revisión del equipo | Coincide con el índice que toca el PR oficial #51. |
| [PR-002 — Problemas con evidencia](<PR-002 - Problemas con evidencia/README.md>) | Proponer una sección 2.1 sustentada en testimonios | Contenido y descripción preparados; pendiente acuerdo de alcance | Conciliar con el autor del PR oficial #52; no enviar dos versiones simultáneas. |
| [PR-003 — Datos de Profesores](<PR-003 - Datos de Profesores/README.md>) | Agregar una propuesta explícita de datos, reglas e integración | Borrador concreto para revisión del E3; decisiones visibles | E1 y consumidores deben validar identificadores y permisos. |

Los paquetes son pequeños para que cada aportación tenga un propósito revisable. La cobertura restante del proyecto sigue en el [plan](<../Plan de trabajo.md>): aprobar los tres paquetes no completa todos los modelos o requisitos pendientes.

## Aplicación y envío

1. Consultar la [referencia oficial](<../Referencia del repositorio oficial.md>) y actualizarla si cambió `develop`.
2. Leer el archivo actual del destino y los PR que ya lo afectan. Resolver duplicación antes de abrir otro PR.
3. Crear la rama de la aportación sobre la versión vigente del repositorio oficial o un fork actualizado. La carpeta local de este repositorio no es una rama del proyecto oficial.
4. Aplicar el contenido propio de `Contenido propuesto.md` únicamente en la ubicación indicada. No pegar todo el paquete en el README del profesor.
5. Revisar enlaces, permisos, coherencia, fuente UML e imagen cuando corresponda. Un cambio textual no se presenta como prueba de ejecución de software.
6. Usar el título y el texto de `Texto del PR.md`, después de ajustar cualquier diferencia del cambio real. La descripción debe seguir teniendo menos de 50 palabras.
7. Registrar URL y commit del PR enviado aquí. Atender las observaciones y marcar **Integrado** solo al comprobar el merge en `develop`.

## Ficha para próximas aportaciones

Cada paquete nuevo debe tener:

- Problema, fuente y tarea del plan que atiende.
- Commit base, archivos de destino y efecto sobre otros módulos.
- Contenido propio concreto: bloques a insertar/reemplazar o archivos nuevos, evitando duplicar documentos oficiales completos.
- Decisiones pendientes y responsable de revisarlas.
- Criterios de revisión cumplidos y limitaciones.
- Título y descripción breve de PR; después del envío, enlace real y estado de integración.

Para las aportaciones UML, agregar archivos fuente e imágenes propios y sus referencias. La plantilla exige componentes y secuencia por caso de uso y estados/clases pertinentes; subir solo PNG no cubre esa condición.

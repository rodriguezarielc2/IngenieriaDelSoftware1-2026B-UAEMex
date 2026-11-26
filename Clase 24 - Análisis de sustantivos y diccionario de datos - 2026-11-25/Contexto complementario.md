# Contexto complementario

El análisis de sustantivos parte de los casos de uso y ayuda a proponer actores, clases o entidades y atributos. Antes de trasladar un término a un diagrama, se revisa si está dentro del alcance, si duplica otro concepto y si todos los módulos lo nombran de la misma manera. El diccionario de datos continúa ese análisis al documentar las entidades y los atributos que realmente necesita el sistema.

Para cada campo, la estructura de referencia considera descripción, tipo de dato, dominio o rango, longitud o precisión, obligatoriedad, unicidad, valor predeterminado y reglas de negocio. La sesión también relacionó la calidad de los datos con integridad, consistencia, exactitud, completitud, oportunidad y validez.

## Ejemplo de estructura del diccionario

La entidad **Libro** se describe como el catálogo de ejemplares físicos disponibles en una biblioteca. La tabla de ejemplo presenta estos campos:

| Campo | Tipo y longitud | Restricciones o valor predeterminado | Significado o regla indicada |
|---|---|---|---|
| `id_libro` | `INT`, 11 | `PK`, `NOT NULL`, autoincremental | Identificador interno consecutivo del ejemplar. |
| `isbn` | `VARCHAR`, 13 | `NOT NULL`, sin valor predeterminado | Código estándar de 13 dígitos sin guiones. |
| `titulo` | `VARCHAR`, 150 | `NOT NULL`, sin valor predeterminado | Nombre completo de la obra literaria o técnica. |
| `anio_publicacion` | `INT`, 4 | `NOT NULL` | Año mayor que 1500 y menor o igual al año actual. |
| `disponible` | `BOOLEAN`, 1 | `NOT NULL`, valor predeterminado `TRUE` | `TRUE` indica que el libro está en estantería; `FALSE`, que está prestado. |

Este ejemplo sirve para mostrar el nivel de precisión esperado en la definición de campos. Es un caso de biblioteca y no un requisito del sistema de control escolar. El significado de cada estado debe concordar con los casos de uso y los demás modelos.

## Coordinación del proyecto final

Las instrucciones presentadas para el cierre del proyecto indicaron que `develop` sería la rama de evaluación y que el README principal debía concentrarse en la información general de nivel cero. La documentación de cada módulo y los diagramas debían mantenerse en las ubicaciones definidas para el proyecto, con enlaces funcionales y correspondencia entre el código fuente UML y su representación gráfica. Se pidió una presentación uniforme, legible y con color; el formato completamente gris por defecto no se consideraría aceptable.

También se comunicó como fecha límite de integración el jueves 3 de diciembre de 2026, con presentaciones a partir del viernes 4. Cada equipo tendría 50 minutos: 30 para explicar y justificar su módulo y 20 para preguntas sobre ese módulo y sus dependencias. Todos los integrantes debían participar y poder explicar cómo su módulo se relaciona con el sistema completo. Estas indicaciones reflejan lo dicho en clase y deben cotejarse con cualquier aviso posterior del docente.

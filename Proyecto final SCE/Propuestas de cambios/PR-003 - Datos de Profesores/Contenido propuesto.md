# Sección propia propuesta para Profesores

Agregar al final del módulo, ajustando la numeración si la versión vigente ya incorpora otras secciones. El bloque explicita su estado de propuesta para que el grupo no confunda una decisión pendiente con una regla definitiva.

---

## 8. Datos, metadatos, reglas e integración

**Estado de esta sección:** propuesta de E3 para revisión con los módulos relacionados. Los datos enumerados como nombre, apellidos, correo, teléfono y especialidad proceden del RF-01 actual. Su obligatoriedad y condiciones requieren validación; no se establece una longitud, formato institucional o identificador definitivo sin ese acuerdo.

### 8.1 Dato principal

El dato principal es el **Profesor**: registro de una persona docente que permite su gestión administrativa y la consulta de su perfil. El perfil y la cuenta de acceso deben relacionarse sin duplicar innecesariamente la información personal en Inicio de Sesión. La cuenta, sus credenciales y sus permisos corresponden a la responsabilidad transversal de acceso; la relación exacta y sus identificadores se acuerdan con E1.

### 8.2 Metadatos y condiciones por acordar

| Elemento | Representación propuesta | Necesidad y regla a precisar |
|---|---|---|
| ID interno del profesor | Identificador estable; tipo y generación por acordar | Relacionar registros sin depender del nombre. Acordar unicidad y referencias con los consumidores. |
| Nombre y apellidos | Texto Unicode | Identificar y mostrar el perfil. Acordar campos obligatorios y representación de nombres sin imponer un patrón que excluya nombres válidos. |
| Correo | Texto con validación del formato acordado | Contacto o identificación según RF-01/RF-02. Acordar si debe ser institucional, si es único y quién autoriza cambiarlo. |
| Teléfono | Texto si se conserva este dato | Contacto; justificar obligatoriedad y acordar formato. No tratarlo como cantidad para operaciones aritméticas. |
| Especialidad | Texto o referencia a catálogo, por decidir | Presente en RF-01; justificar su uso y fuente. Acordar si se comparte con asignaturas o grupos. |
| Estado del registro | Estado vigente o baja lógica, sujeto al modelo de estados | RF-05 exige conservar historial. Precisar consecuencias de baja sobre consultas y nuevas asignaciones sin borrar relaciones históricas. |
| Referencia de cuenta | Relación con cuenta, por acordar con E1 | Vincular acceso y perfil sin almacenar contraseñas en el registro docente. Acordar cardinalidad y tratamiento de roles simultáneos. |

### 8.3 Reglas y permisos

1. Una baja conserva el registro y su historial, conforme a RF-05. Debe acordarse qué operaciones nuevas se restringen y qué consultas siguen disponibles.
2. La identificación de duplicados debe basarse en una clave acordada; compartir nombre no demuestra duplicidad. La posibilidad de correo duplicado se resuelve con el alcance del registro y la política institucional.
3. Se propone que el profesor edite únicamente campos personales o de contacto autorizados y que los campos de gestión institucional queden bajo responsabilidad administrativa. La lista de campos y excepciones debe validarse y reflejarse en RF-07, RNF-01 y la matriz común de permisos.
4. La cuenta y sus permisos no se derivan automáticamente de que exista un registro docente. E1/E3 deben acordar el vínculo entre alta administrativa, acceso y baja.
5. Los módulos consumidores deben consultar identificadores y datos necesarios, sin administrar copias independientes del perfil como fuentes de verdad distintas.

### 8.4 Entradas, salidas y dependencias

| Interacción | Información | Acuerdo pendiente |
|---|---|---|
| Administración hacia Profesores | Datos de alta/edición y solicitud de baja | Campos obligatorios, validaciones y permisos por operación. |
| Profesor hacia su perfil | Consulta y cambios autorizados | Relación con cuenta y lista de campos editables. |
| Profesores hacia módulos consumidores | Identificador, nombre para presentación y estado pertinente | Consumidores, permisos, datos mínimos y responsable de las asignaciones. |
| Módulos con historial hacia Profesores | Referencias a docentes asociados a registros académicos | Conservación de relaciones ante baja y reglas de consulta histórica. |

La asignación de un profesor a materias, grupos u horarios queda fuera del alcance actual de Profesores. El equipo debe acordar con E2/E4/E5 quién administra esa relación y cómo E6 valida al profesor que captura calificaciones.

### 8.5 Cierre de esta propuesta

Antes de considerarla una definición final, E1/E3 y consumidores deben acordar identificadores, cardinalidades, campos obligatorios, formatos, duplicados, permisos y efectos de baja. Las decisiones deben propagarse a requisitos, casos de uso, clases, estados, componentes y secuencias y al modelo entidad-relación general, con fuente UML e imagen según plantilla.

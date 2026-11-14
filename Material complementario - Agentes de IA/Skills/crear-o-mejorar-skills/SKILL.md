---
name: crear-o-mejorar-skills
description: Convierte una tarea ya realizada y sus correcciones confirmadas en un procedimiento reutilizable para un agente de IA.
---

# Crear o mejorar una habilidad reutilizable

## Cuándo usarla

Úsala después de completar una tarea y recibir criterios o correcciones que puedan servir en trabajos posteriores. No crees una habilidad a partir de un ejemplo aislado sin identificar qué parte es generalizable.

## Procedimiento

1. **Delimita la tarea.** Describe qué resultado se busca, quién lo usa y qué entradas necesita. Separa el objetivo estable de los detalles particulares del proyecto de ejemplo.
2. **Revisa las fuentes.** Examina las instrucciones, archivos de contexto, datos del proyecto y correcciones recibidas. Conserva cualquier incertidumbre; no añadas requisitos que no estén respaldados.
3. **Clasifica cada corrección.** Determina si es una regla general confirmada, una preferencia, una excepción o un dato de un solo proyecto. Si no queda claro su alcance, pregunta antes de convertirla en regla.
4. **Actualiza la memoria.** Registra la corrección confirmada en `Memory.md`, con su alcance y fuente. No dupliques allí el procedimiento completo.
5. **Escribe la habilidad.** Guárdala en `Skills/<nombre-de-la-tarea>/SKILL.md` e incluye:
   - propósito y condición de uso;
   - entradas y contexto necesarios;
   - pasos ordenados para completar la tarea;
   - reglas de decisión y casos en los que se debe preguntar;
   - formato de salida esperado;
   - comprobaciones para detectar omisiones o errores;
   - límites y excepciones confirmados.
6. **Hazla concreta y reutilizable.** Usa instrucciones accionables, pero evita codificar nombres, datos o decisiones exclusivas del ejemplo. Si una regla solo aplica a un caso, márcala como ejemplo o déjala en los archivos de ese proyecto.
7. **Revisa y aplica.** Comprueba que cada regla tenga respaldo en una fuente o corrección confirmada. En la siguiente tarea comparable, usa la habilidad y registra cualquier ajuste necesario.

## Memoria y habilidad cumplen funciones distintas

La memoria conserva qué se decidió y cuándo; la habilidad explica cómo ejecutar una clase de tarea. Una lista de correcciones sin orden de ejecución no es una habilidad terminada.

## Límites

- No presentes una regla del video de referencia como una exigencia universal.
- No afirmes que una habilidad funciona en todas las herramientas. Verifica que la aplicación pueda leer el archivo y seguir el formato.
- No digas que la habilidad quedó validada hasta aplicarla a una tarea y revisar el resultado.
- No guardes información sensible ni datos identificables que no sean necesarios.

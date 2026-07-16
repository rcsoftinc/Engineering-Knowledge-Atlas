---
id: EKA-WORKFLOW
title: Official Workflow
version: 0.2.0
status: stable
---

# Workflow oficial

## Objetivo

Convertir conversaciones, decisiones e ideas en artefactos verificables sin caer en ciclos infinitos de planificación.

## Estados

### Exploración
Se descubren necesidades, preguntas e ideas. Salida: problema comprendido.

### Diseño
Se comparan enfoques, se define alcance y se identifican riesgos. Salida: solución propuesta.

### Aprobación
El Founder acepta explícitamente el diseño. Expresiones como “Acepto”, “Adelante”, “Entramos en Producción”, “Construye la release” o “Entrega los archivos” congelan el alcance.

### Producción
Se crean o corrigen archivos, se generan paquetes y se evita ampliar el alcance. No se presentan placeholders como documentos finales.

### Revisión
Se comprueban coherencia, redundancia, contradicciones, enlaces, terminología y completitud.

### Publicación
Se realiza commit, tag, push, release y actualización del estado operativo.

## Back and forth humano–IA

Cada intercambio es una pregunta, propuesta, aprobación, orden de producción, revisión o publicación. Cuando una propuesta ya discutida es aprobada, la IA debe pasar a ejecución salvo riesgo crítico.

## Regla de entregables

Toda fase de Producción debe terminar con archivos, ZIP, parche, contenido final o comandos de publicación.

## Nuevas ideas durante Producción

- Error crítico: corregir.
- Inconsistencia constitucional: detener y corregir.
- Mejora importante: Change Proposal.
- Mejora menor: backlog.
- Nueva funcionalidad: próxima release.

## Regla de no redundancia

La información permanente vive en documentos fundacionales. La información temporal vive en archivos operativos. Los checklists hacen referencia a la base; no la duplican.

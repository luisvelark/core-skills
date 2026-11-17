---
name: "correos-reunion-cliente"
description: Redacta correos profesionales y ejecutivos a partir de reuniones con clientes, organizando acuerdos, decisiones, pendientes con responsables, fechas, recomendaciones y próximos pasos, y entrega un correo listo para copiar y enviar. Úsala siempre que el usuario pegue notas, minutas, transcripciones o apuntes de una reunión con un cliente (kickoff, seguimiento, discovery, revisión técnica, validación/UAT, salida a producción, soporte o cierre) y pida un correo, resumen, minuta, recap o "acuerdos y próximos pasos", aunque no mencione la palabra "correo". También aplica cuando el usuario comparta una plantilla de correo de referencia para imitar su estilo. No la uses para correos que no provengan de una reunión (cold outreach, respuestas sueltas) ni para actas internas sin destinatario cliente.
---

# Redacción de correos de reuniones con clientes

Convierte las notas de una reunión en una síntesis ejecutiva orientada al seguimiento: qué se acordó, quién hace qué y para cuándo. El lector es un cliente que quiere claridad y confianza, no una transcripción.

## Entradas

Toma el contenido de lo que el usuario haya pegado o descrito. Reconoce estos elementos aunque no vengan etiquetados:

- **Tipo de sesión**: kickoff, seguimiento, discovery, revisión técnica, validación/UAT, salida a producción, soporte, cierre u otra. Si no se indica, dedúcelo de las notas.
- **Notas de la reunión**: acuerdos, decisiones, observaciones, compromisos, responsables, fechas.
- **Plantilla de referencia** (opcional): úsala como guía de tono, formato y presentación.
- **Datos adicionales** (opcionales): cliente, destinatarios, fecha, zona horaria, contexto, próxima reunión.

No pidas datos adicionales si ya puedes redactar un correo útil. Pregunta solo si una contradicción impide comunicar un acuerdo importante y no puede resolverse con redacción neutral. En ese caso, prefiere entregar el correo marcando el dato como pendiente de confirmación.

## Cómo procesar la información

Antes de redactar, clasifica lo que recibiste. Esto evita el error más costoso en este tipo de correos: presentar ante el cliente como compromiso algo que solo fue una idea.

1. **Contexto**: identifica el objetivo de la sesión y su impacto en el proyecto. Distingue entre información contextual, acuerdos confirmados, decisiones, pendientes y recomendaciones.
2. **Compromisos**: extrae solo los respaldados por las notas. Para cada uno, identifica actividad, responsable, fecha (límite o estimada), estado (completado, en curso, pendiente, sujeto a validación), dependencias y siguiente paso. Una observación, sugerencia o posibilidad no se convierte en compromiso.
3. **Prioridad**, en este orden: decisiones y acuerdos importantes → compromisos pendientes → fechas e hitos → riesgos, bloqueos o dependencias → recomendaciones de valor.

Omite detalle técnico que no sea necesario para entender los acuerdos y evita repetir información entre secciones.

## Adaptación al tipo de sesión

Ajusta el énfasis según el propósito real de la reunión. Estas guías son orientativas; manda el contexto.

| Sesión                     | Enfoque del correo                                                    |
| -------------------------- | --------------------------------------------------------------------- |
| Kickoff                    | Alineación, objetivos, alcance y próximos pasos                       |
| Seguimiento                | Avances, acuerdos, pendientes y compromisos                           |
| Discovery                  | Necesidades, procesos, requerimientos y definiciones                  |
| Validación / UAT           | Pruebas, observaciones, correcciones y criterios pendientes           |
| Salida a producción        | Fechas, condiciones de liberación, responsables y actividades previas |
| Soporte / revisión técnica | Incidencias, hallazgos, acciones correctivas y próximos pasos         |
| Cierre                     | Resultados, entregables, conformidades y actividades posteriores      |

## Tono

Profesional, ejecutivo y cordial; claro, directo y orientado a resultados; colaborativo y enfocado en la continuidad. Técnico solo cuando el contexto lo pida, sin jerga innecesaria. Cuando haya incidencias, retrasos o actividades en validación, usa un tono tranquilizador y persuasivo: expón el hecho con neutralidad y enfatiza la acción en curso, sin atribuir responsabilidades que no estén documentadas.

## Estructura del correo

Incluye únicamente las secciones que tengan información relevante; no fuerces las demás. Si el usuario entregó una plantilla, adopta su tono, formato y presentación; si no, usa la estructura por defecto de `references/plantilla-por-defecto.md`.

1. **Asunto**: breve y descriptivo; identifica cliente, proyecto y propósito. Ejemplo: `Acuerdos y próximos pasos | Proyecto Bahía Motors | Sesión de seguimiento`.
2. **Saludo y apertura**: cordial; agradece la participación, menciona el propósito de la sesión e introduce el resumen. Evita aperturas genéricas que no correspondan al tipo de reunión.
3. **Acuerdos de la sesión**: decisiones y acuerdos confirmados. Presenta el encabezado únicamente en negrita y una viñeta por acuerdo, con este formato exacto:
   `✅ **[Tema o concepto]:** [Acuerdo o decisión con datos concretos]. [Fecha, si aplica].`
   Los compromisos operativos pendientes van en su sección correspondiente.
4. **Entregables**: resultados o artefactos concretos entregados, por entregar o previstos como resultado de la sesión (por ejemplo, documentos, configuraciones, reportes, correcciones o versiones). Presenta el encabezado únicamente en negrita. Incluye una viñeta por entregable y, cuando se conozcan, su responsable, estado y fecha o condición de entrega. No conviertas una idea o recomendación en entregable.
5. **Pendientes**: presenta el encabezado únicamente en negrita y una viñeta por compromiso, con este formato exacto:
   `🔄 **[Responsable]:** [Actividad concreta]. [Fecha o condición, si aplica].`
   Agrupa por responsable cuando facilite el seguimiento.
6. **Recomendaciones**: solo si hay recomendaciones útiles, riesgos, consideraciones técnicas o acciones preventivas. Deben ser accionables y concretas.
7. **Próximos pasos**: presenta el encabezado únicamente en negrita y resume las siguientes actividades, reuniones o hitos. No dupliques lo ya explicado en Pendientes o Entregables.
8. **Cierre**: frase cordial que refuerce la colaboración y la disponibilidad para consultas, seguida de «Saludos,».

Usa únicamente encabezados en negrita para diferenciar las secciones, por ejemplo: `**Entregables:**`. No uses HTML ni tamaños de letra especiales.

## Reglas de integridad

Estas reglas existen porque el correo queda como registro escrito frente al cliente y un dato inventado compromete al equipo.

- No inventes nombres, fechas, horarios, responsables, decisiones, resultados ni compromisos.
- los responsables solo son Inconcert y el nombre de la empresa del cliente.
- No presentes una fecha estimada como confirmada, ni uses expresiones que comprometan al equipo con fechas o resultados no confirmados («estimamos», «a validar» según corresponda).
- Respeta valores, porcentajes, horarios y zonas horarias tal como aparecen en las notas.
- Conserva nombres de herramientas, módulos, funcionalidades y proyectos relevantes.
- Si las notas se contradicen, no elijas una versión: redacta de forma neutral y marca el dato como pendiente de confirmación.
- Si un dato falta y no es indispensable, omítelo.
- No copies acuerdos, nombres, fechas ni recomendaciones de la plantilla o de los ejemplos como si fueran de la reunión actual.

## Calidad de redacción

- Corrige ortografía, gramática y puntuación; convierte apuntes fragmentados en oraciones completas sin alterar el significado.
- Evita párrafos extensos y redundancias. Es una síntesis ejecutiva, no una transcripción.
- Usa negritas para responsables, fechas, hitos y conceptos clave. Mantén el formato limpio.
- Cada pendiente expresa una acción concreta, con responsable cuando se conoce.
- Cada entregable identifica un resultado concreto y lo diferencia de un acuerdo, pendiente, recomendación o próximo paso.

## Verificación antes de entregar

Comprueba internamente que: el correo corresponde al tipo de sesión; los acuerdos reflejan lo conversado; los entregables son resultados concretos y están diferenciados de los pendientes; los pendientes tienen acción y responsable cuando se conocen; fechas y horarios coinciden con el origen; no hay compromisos inventados o presentados como confirmados; los encabezados de Acuerdos de la sesión, Entregables, Pendientes y Próximos pasos están en negrita y sin HTML; no hay repetición innecesaria; y el correo está listo para copiar, editar y enviar.

## Formato de salida

Entrega **exclusivamente el correo final**, sin análisis, explicaciones de cómo lo redactaste, listas de información extraída ni comentarios fuera del correo. Escríbelo en el idioma de las notas (español por defecto). Para ver ejemplos de distintos tipos de sesión, consulta `references/ejemplos.md`.

## 1. Problema

Manta Seguros no cuenta con una plataforma de gestión y visibilidad de siniestros. Al no existir aún operación, la alternativa por defecto para recibir, analizar y decidir sobre los siniestros reportados por RGC/TPA sería un esquema manual basado en Excel, correo electrónico y revisión caso por caso por parte de un analista.

Ese esquema manual no garantiza escalabilidad cuando crezca el volumen de siniestros, incrementa el riesgo de fuga de información, limita la capacidad de análisis de datos, aumenta el tiempo invertido por siniestro, y deriva en pérdida de control sobre la información del proceso.

## 2. Por qué es un problema

Sin una plataforma que estructure y sustente el análisis, la aseguradora quedaría expuesta a tres consecuencias concretas:

- Pagar (o glosar) sin conocimiento de causa: la decisión de pago se tomaría sin una base de análisis clara y verificable, no porque el valor pagado sea necesariamente incorrecto, sino porque no habría cómo demostrar que fue la decisión correcta.
- Exposición regulatoria y legal por falta de trazabilidad de las decisiones de indemnización.
- Imposibilidad de auditar cómo se tomó cada decisión, lo que compromete tanto el control interno como la revisión de un auditor externo.

## 3. Para qué resolverlo

Hay dos objetivos detrás de resolver este problema. El primero es poder pagar con conocimiento de causa, es decir, que cada decisión de indemnización esté sustentada y sea trazable. El segundo es de posicionamiento: como aseguradora nueva, la intención es diferenciarse desde el diseño mismo de la operación, ofreciendo un proceso de indemnización ágil y transparente. *(Interpretación: estos dos objetivos están conectados (la solidez del sustento de cada decisión y la agilidad del proceso no se plantean como metas independientes, sino como dos caras de la misma propuesta de valor operativa).)*

## 4. Para quién

El problema es de la operación de la aseguradora en conjunto, y en particular de quienes deben tomar o sustentar la decisión de pago: el analista de indemnizaciones y el director de indemnizaciones. También es relevante para quien necesita entender el comportamiento de cada prestador por departamento, con el fin de conocer la operación a detalle.

## 5. Por qué es un problema para esa persona

Para el analista y el director, la ausencia de esta plataforma se traduce en tres fricciones concretas:

- No tienen cómo sustentar la decisión de pago o glosa que toman.
- Reunir la evidencia y hacer el análisis les toma demasiado tiempo, incluyendo relacionar el siniestro con reclamos y verificar si está dentro de las coberturas.
- No tienen información clara sobre la facturación de cada prestador, lo que limita su capacidad de identificar patrones o comportamientos problemáticos.

## 6. Solución satisfactoria

Como propuesta a validar (no como la única solución posible), el usuario define que una solución sería satisfactoria si permite:

1. Revisar la información que RGC reportó sobre un siniestro.
2. Tomar una decisión de pago o glosa sobre un siniestro.
3. Verificar si un siniestro cumple los requisitos de pago respecto a amparos y coberturas.
4. Realizar muestreo in situ (auditoría de casos) dentro de la misma plataforma.
5. Revisar el comportamiento de los prestadores a nivel nacional.

Esta lista de criterios de éxito es un buen punto de partida, pero conviene tratarla como hipótesis a afinar con el equipo antes de convertirla en requisitos de una spec (por ejemplo, precisando qué significa exactamente "muestreo in situ" dentro de la plataforma).

Sobre el primer punto (revisar la información que RGC reportó), el usuario precisó qué evidencia mínima haría que una decisión se considere sustentada: revisión de los soportes, facturas y RIPS; revisión de los documentos médicos y coincidencia de CUPS; y concordancia de lo facturado con el manual tarifario de la aseguradora.

## Síntesis del problema

Manta Seguros, una aseguradora sin operación previa, necesita poder recibir, analizar y decidir sobre siniestros desde el primer día, y hoy no cuenta con ninguna plataforma para hacerlo (la alternativa sería un proceso manual que no escala y que no deja sustento verificable de cada decisión). Esto deja al analista y al director de indemnizaciones sin forma de justificar sus decisiones, les exige un esfuerzo desproporcionado para reunir evidencia, y les impide ver el comportamiento de los prestadores. El problema, entonces, no es solo operativo: sin resolverlo, la aseguradora arrancaría con riesgo regulatorio, sin capacidad de auditoría y sin la base de transparencia y agilidad que quiere usar como diferenciador frente al mercado.

## Información pendiente

- No hay datos cuantitativos sobre el volumen de siniestros esperado al inicio de operación ni sobre cómo escalaría ese volumen en el tiempo, lo que ayudaría a dimensionar qué tan urgente es el riesgo de "no escalar".
- No se mencionó evidencia externa (por ejemplo, casos de otras aseguradoras, hallazgos de auditoría previos en el mercado, o normativa específica del regulador) que respalde el riesgo regulatorio y legal señalado en la pregunta 2.
- No quedó definido qué tiempo se considera hoy "demasiado tiempo" para el análisis de un siniestro (ya se precisó, en cambio, qué evidencia mínima sustenta una decisión: soportes, facturas, RIPS, documentos médicos, coincidencia de CUPS y concordancia con el manual tarifario).
- El criterio de éxito "capacidad de muestreo in situ dentro de la plataforma" no quedó del todo explícito (valdría la pena precisar si se refiere a auditoría de casos por muestreo estadístico, a inspección de campo, o a otra cosa).

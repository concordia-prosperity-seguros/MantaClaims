# Modelo de datos

El modelo de dominio detallado no fue definido todavía. Se identifican, como mínimo, estas entidades conceptuales:

- Siniestro.
- Póliza.
- Amparo.
- Prestador.
- TPA.
- Documento.
- Factura.
- Servicio o procedimiento.
- Validación.
- Fase de análisis.
- Resultado de IA.
- Revisión humana.
- Inconsistencia.
- Glosa.
- Decisión.
- Pago.
- Movimiento actuarial.
- Usuario.
- Auditoría.
- SLA.

## Relaciones conceptuales
Un siniestro pertenece a una póliza y puede involucrar uno o varios amparos, prestadores, documentos, facturas y servicios.

El análisis tiene fases y resultados. Una revisión humana puede continuar un análisis iniciado por IA.

Las inconsistencias generan glosas cuando existe un valor no reconocible.

La decisión final determina el valor aprobado y puede generar un pago.

## Pendiente
Definir claves, cardinalidades, estados, versionamiento, historiales y modelo físico.

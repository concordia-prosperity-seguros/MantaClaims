# Integraciones y flujo de información

## Sistema de administración de pólizas
Debe entregar la información necesaria para validar póliza, amparos y topes.

## RGC, TPA
Entrada principal de:
- Siniestros.
- Documentación.
- Información de prestadores.

## ERP
Salida del módulo hacia el proceso de pago. Debe permitir generar la nota crédito necesaria para pagar una indemnización.

## Sistema actuarial
Recibe los movimientos asociados a la operación.

## Flujo
TPA → módulo de siniestros → análisis IA → revisión humana, cuando corresponda → decisión director → ERP y sistema actuarial.

## Pendiente
Definir con el equipo:
- Contratos de integración.
- Formatos.
- Identificadores.
- Manejo de errores.
- Reintentos.
- Idempotencia.
- Tiempos de respuesta.
- Monitoreo.

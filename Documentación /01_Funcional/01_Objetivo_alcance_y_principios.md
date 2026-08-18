# Objetivo, alcance y principios funcionales

## Objetivo
Construir un módulo que permita recibir, analizar, auditar y resolver siniestros con una combinación de inteligencia artificial y revisión humana.

El módulo debe permitir determinar qué valores de un siniestro son reconocibles, cuáles deben glosarse y cuál es el valor final que corresponde pagar según la documentación, la validación médica, las referencias tarifarias y las coberturas por amparo disponible.

## Alcance
Incluye:
- Recepción de siniestros y soportes desde RGC.
- Validación documental.
- Validación médica.
- Validación de valores.
- Validación de amparos y topes.
- Análisis mediante IA.
- Revisión humana.
- Registro de inconsistencias.
- Registro de glosas.
- Decisión final del director.
- Integración con pólizas, ERP y sistema actuarial.
- Auditoría y trazabilidad.
- Indicadores de operación y SLA.

## Principios
1. La IA debe seguir las mismas cuatro fases que seguiría un analista humano.
2. Si la IA puede completar el análisis con información suficiente, el caso debe continuar sin revisión humana.
3. Si la IA no puede cerrar el análisis, debe indicar la fase exacta donde requiere intervención.
4. El analista debe continuar desde esa fase y no repetir las fases ya resueltas.
5. Toda decisión debe estar soportada por evidencia.
6. Toda inconsistencia debe tener una explicación.
7. Toda glosa debe estar asociada a evidencia.
8. El director toma la decisión final de pago.
9. La documentación original recibida del TPA no se debe perder.
10. Las decisiones históricas no se deben sobrescribir.
11. El valor pagado debe respetar el amparo y su tope disponible.
12. El sistema debe permitir reconstruir el razonamiento operativo que llevó a una decisión.

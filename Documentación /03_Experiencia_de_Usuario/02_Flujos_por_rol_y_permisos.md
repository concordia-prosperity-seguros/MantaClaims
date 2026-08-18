# Flujos por rol y permisos

## Analista
Flujo:
1. Entra a bandeja.
2. Selecciona caso.
3. Consulta expediente.
4. Revisa resultado IA.
5. Retoma desde la fase indicada.
6. Completa análisis.
7. Registra inconsistencias y glosas.
8. Genera recomendación.
9. Entrega el caso al director.

No puede:
- Aprobar pago.
- Acceder a auditoría.

## Director
Flujo:
1. Consulta caso.
2. Revisa expediente.
3. Revisa análisis.
4. Revisa glosas.
5. Consulta auditoría.
6. Decide pago total, parcial o no pago.
7. Confirma la decisión.

## Regla UX
El sistema debe diferenciar claramente entre:
- Valor facturado.
- Valor reconocido.
- Valor glosado.
- Valor disponible del amparo.
- Valor final a pagar.

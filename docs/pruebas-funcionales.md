# Matriz de pruebas funcionales

Registrar por ejecución: **fecha, navegador, URL, resultado observado y evidencia**. Distinguir **aprobada**, **no aprobada**, **no ejecutada** y **solo representación visual**.

| ID | Probar | Resultado esperado | Resultado observado |
|---|---|---|---|
| P01 | Abrir la demo y recorrer los perfiles previstos | Inicio y panel correspondiente a cada recorrido de demostración | |
| P02 | Registrar o recorrer el alta de un producto y consultarlo | Referencia visible con los campos requeridos | |
| P03 | Agregar lote con fecha y cantidades | La referencia muestra el lote, vencimiento y saldo correspondiente | |
| P04 | Registrar o recorrer una venta de 2 unidades de un lote con saldo inicial de 10 | Confirmación, total en COP y saldo final de 8. Indicar si se calculó o solo se representó | |
| P05 | Solicitar una cantidad superior al saldo | Mensaje de rechazo y saldo sin cambio | |
| P06 | Revisar un lote próximo a vencer | Alerta con lote, fecha y criterio visible | |
| P07 | Consultar un reporte por un periodo | Periodo visible y montos en COP | |
| P08 | Recargar la página tras una operación, si la demo registra cambios | Documentar si los datos se reinician, se conservan en ese navegador o se guardan en un sistema externo | |



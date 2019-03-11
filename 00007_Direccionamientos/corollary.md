¡Excelente! :clap:

Hay dos instrucciones del ejercicio que son inválidas. ¿Por qué?

`MOV 0x1003, R1`

`MOV 0x1003, 0x1C04`

Seguramente te diste cuenta: **no tiene sentido** copiar un valor a una constante. En ambas instrucciones, `0x1003` es el operando destino. ¡Un valor constante no puede ser destino! Sí los registros, porque allí almacenamos valores variables. :satisfied:
La arquitectura Q tiene un repertorio de instrucciones básicas para que ejecute la CPU, y en ellas se pueden utilizar cualquiera de los registros R0 a R7 que mencionamos en el ejercicio anterior.

Las instrucciones son las siguientes:

| Instrucción | Operación | Ejemplo de uso |
|---|---|---|
| ADD | Suma | `ADD R0, R4` |
| SUB | Resta | `SUB R2, R1` |
| MUL | Multiplicación | `MUL R5, R7` |
| DIV | División | `DIV R6, R3` |

Como ves, las cuatro instrucciones tienen dos operandos. El resultado de la operación se almacena en el primero de ellos, denominado **operando destino**, mientras que el segundo se denomina **operando origen**.

Por ejemplo, `ADD R0, R4` suma R0 y R4 y guarda el resultado de la suma en R0. :satisfied:

> Marcá las opciones correctas.

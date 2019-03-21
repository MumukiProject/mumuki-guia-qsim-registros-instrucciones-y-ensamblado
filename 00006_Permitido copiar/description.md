Hasta ahora, las únicas cuatro instrucciones que conocemos corresponden a las operaciones aritméticas básicas: sumar :heavy_plus_sign:, restar :heavy_minus_sign:, multiplicar :heavy_multiplication_x: y dividir :heavy_division_sign:.

Aprendamos una más: es el momento de la instrucción `MOV`. `MOV` también trabaja con dos operandos, y su función es **copiar** un valor a un registro. Ese valor puede estar almacenado en otro registro, o bien ser un valor constante.

Al igual que con las otras instrucciones, el _operando destino_ es el primero, y el _operando origen_ el segundo. Por ejemplo, para copiar el valor de `R0` a `R1`, hacemos `MOV R0, R1`.

> ¡A copiar, pero no a copiarse! Copiá el valor del registro `R4` al registro `R3`; luego copiá la constante `0x03A1` al registro `R2`.
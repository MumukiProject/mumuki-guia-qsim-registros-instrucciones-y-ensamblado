Cuando un operando tiene direccionamiento inmediato, los 6 bits se ensamblan como `000000` y se dedican **16 bits** más a traducir a binario el número hexadecimal.

Por ejemplo, el código máquina de la instrucción `SUB R5, 0xD13B` es...

* `0011`, 4 bits, que es el código de la instrucción SUB;
* `100101`, 6 bits; `100` por ser direccionamiento de registro y `101` que es 5 en binario (por ser el registro R5);
* `000000`, 6 bits, porque el direccionamiento del operando origen es inmediato;
* Y 16 bits distribuidos en cuatro partes:
  * `1101`, 4 bits, que es `D` hexadecimal en binario;
  * `0001`, 4 bits, que es `1` hexadecimal en binario;
  * `0011`, 4 bits, que es `3` hexadecimal en binario;
  * `1011`, 4 bits, que es `B` hexadecimal en binario.

El ensamblado final lo tenemos juntando cada parte: `00111001010000001101000100111011`. :grin:

> ¡El esfuerzo final! :muscle: Escribí el código máquina de la instrucción `SUB R2, 0xF012`.
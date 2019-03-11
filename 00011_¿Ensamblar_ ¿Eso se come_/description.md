Todas las instrucciones que aprendimos hasta ahora son **código fuente**: los seres humanos las podemos leer, escribir e interpretar, como vos durante esta lección :grin:. Pero una computadora no sabe interpretar palabras como MOV o SUB, y tampoco sabe leer números en hexadecimal. :confused:

Por esa razón se requiere de un proceso que _traduzca_ el código fuente en **código máquina** :computer:, compuesto por unos y ceros, que la CPU sí comprende. Este proceso se llama **ensamblado** y sigue ciertas reglas que dependen de la arquitectura de cada procesador.

En nuestra arquitectura Q, por ejemplo, la instrucción `DIV R1, R2` se ensambla al código máquina `0111100001100010`. La lógica del ensamblado es la siguiente:

* Los primeros **4 bits**, `0111`, corresponden a la instrucción, en nuestro caso DIV. Por ejemplo, ADD es 0010 y DIV es 0111.
* Los siguientes **6 bits**, `100001` corresponden al modo de direccionamiento del operando destino. Por ser direccionamiento de registro empieza con `100`, y `001` es el número 1 (¡del registro R1!) en binario.
* Los últimos **6 bits**, `100010`, corresponden al modo de direccionamiento del operando origen. También es  direccionamiento de registro, por lo que otra vez empieza con `100`, pero termina con `010` (que es el número 2 en binario, por el registro R2).

Leelo atentamente antes de pasar al siguiente ejercicio. ¡Va a ser tu turno de ensamblar! :scream:
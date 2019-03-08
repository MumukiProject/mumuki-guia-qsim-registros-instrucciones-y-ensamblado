Todo viene bien con sumar, restar, multiplicar y dividir registros, pero ¿qué valores tienen? ¿Cómo saber qué valores estamos operando? :thought_balloon:

En QSim podemos trabajar con valores **constantes** - constante significa que, a diferencia de un registro, no puede variar: es un número que siempre vale lo mismo, como 5, 7 ó 19.

¿Dónde está la dificultad? ¡El procesador no entiende de números decimales! :scream: Pero sí entiende de números en el **sistema hexadecimal**, como estuvimos aprendiendo. Por eso, cuando querramos hacer referencia a un número constante, hay que anteponer el prefijo `0x`, y luego escribir el número hexadecimal en cuatro dígitos.

Para transformar los números a hexadecimal, recordá que podíamos asistirnos con otro lenguaje. [link] **¡Tené ese ejercicio a mano!** Convertir los números en esa consola te va a resultar útil para el resto de la lección. :grin:

> Probemos algo simple: escribí en la consola el número constante 505, convertido a hexadecimal y con el prefijo correspondiente.

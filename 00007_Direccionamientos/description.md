Es cierto que copiar a un registro el valor que está en otro registro o algún valor constante se ve parecido a simple vista, pero... :eyes:

> `MOV R3, R2` :arrow_left: copiando desde un registro

> `MOV R3, 0x0134` :arrow_left: copiando un valor constante

...¡a la CPU no le da igual! Si bien copiar un valor constante es más simple, copiar desde un registro implica un trabajo adicional: hay que averiguar cuál es el valor que está en ese registro... ¡así lo puede copiar! :grimacing:

Según los operandos de la instrucción se estará utilizando un **modo de direccionamiento** u otro. Por ejemplo, para `MOV R3, R2` se utiliza el **direccionamiento de registro** para ambos operandos, porque ambos son registros.

En cambio, `MOV R3, 0x0134` utiliza dos tipos de direccionamiento distintos:

* direccionamiento de registro para el operando destino, R3, porque es un registro;
* y **direccionamiento inmediato** para el operando origen, porque el valor que requiere (0x0134) ya aparece directamente en la instrucción.

¡No son los únicos dos tipos de direccionamiento, pero sí los dos más simples! :blush:

> Marcá las respuestas correctas.
# Sintaxis CSS


### Que es CSS?


CSS es un lenguaje declarativo, lo que hace que su sintaxis sea bastante fácil de usar y de comprender. Además, dispone de un potente sistema de recuperación de errores que permite cometer fallos sin que esto afecte a todo el código — las declaraciones que no son comprendidas normalmente son ignoradas. La parte negativa es que puede ser más difícil averiguar de dónde proceden los errores. Si seguimos leyendo entenderemos porqué.
Un poco de vocabulario

### Ejemplos de codigo CSS

>h1 {
   colour: blue;
  
>	background-color: yellow;
  
>	border: 1px solid black;

>	}



*El codigo de arriba, da color a todos los h1 del html ademas de modificarle el fondo y darle un borde *

>p {
  
>	color: red;

>	}


*El codigo de arriba, modifica el color de todos los parrafos en el html*



### Formas de escribir en CSS

Algunas propiedades como: font, background, padding, border, y margin se llaman propiedades abreviadas — permiten establecer varios valores a la vez en una sola línea, ahorrando tiempo y haciendo el código más limpio.

Por ejemplo esta linea

> padding: 10px 15px 15px 5px;

Hace lo mismo que todas estas

> padding-top: 10px;

> padding-right: 15px;

> padding-bottom: 15px;

> padding-left: 5px;

### ¿Cuando usar "id" o cuando usar “class”?

> Las "id" se utilizan para objetos unicos, se identifican con **"#"** a la hora de ponerle las propiedades que queremos en CSS
> Las "class" se utilizan para conjuntos de objetos, se identifican con **"nombre de la clase"** a la hora de ponerle las propiedades que queremos en CSS


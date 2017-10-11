CSS es un lenguaje declarativo, lo que hace que su sintaxis sea bastante fácil de usar y de comprender. Además, dispone de un potente sistema de recuperación de errores que permite cometer fallos sin que esto afecte a todo el código — las declaraciones que no son comprendidas normalmente son ignoradas. La parte negativa es que puede ser más difícil averiguar de dónde proceden los errores. Si seguimos leyendo entenderemos porqué.
Antes de profundizar más en el tema, veamos un ejemplo concreto (vimos algo parecido en nuestro artículo anterior):

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My CSS experiment</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <h1>Hello World!</h1>
    <p>This is my first CSS example</p>

    <ul>
      <li>This is</li>
      <li>a list</li>
    </ul>
  </body>
</html>

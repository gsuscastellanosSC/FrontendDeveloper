# 🚨[Curso de Frontend Developer](https://platzi.com/clases/frontend-developer/)🚨
## ✅Class#1⚡️
```Presentación y bienvenida al curso de HTML y CSS```
## ✅Class#2⚡️
```HTML y CSS: definición y usos```
* Historia
    ```Interconnected + Network =Internet```
    * Tim Berners-Lee Fue el inventar de la Word Wide Web Y fundador de la W3C.
    * Tecnologías que dieron paso al internet
        * HTTP => Hyper Text Transfer Protocol.
        * URL  => Uniform Resource Locator.
        * HTML => Hyper Text Markup Language.
        * CSS  => Cascade Style Sheets.
## ✅Class#3⚡️
```¿Qué son y para qué nos sirven HTML y CSS?```
* HTML => Es un lenguaje de marcado usado para decirle a tu navegador cómo estructurar las páginas web que visitas. No es un lenguaje de programación.
* CSS  => Es un lenguaje que nos permite crear páginas web con un diseño agradable para los usuarios. Tampoco es un lenguaje de programación.
## ✅Class#4⚡️
```DOM, CSSOM, Render Tree y el proceso de renderizado de la Web```
* DOM (Document Object Model):
    ```Es una transformación del código HTML escrito por nosotros a objetos entendibles para el navegador.```
* CSSOM (CSS Object Model):
   ```Así como el DOM para el HTML, EL CSSOM es una representación de objetos de nuestros estilos en CSS.```
   https://developer.mozilla.org/es/docs/Web/API/CSS_Object_Model
* Render Tree:
   ```Es la unión entre el DOM y el CSSOM para renderizar todo el código de nuestra página web.```
* Pasos de la transformación que hace el navegador:
   * Bytes.     => 01110011101....
   * Characters => Utf8,...
   * Tokens.    => Etiquetas Html.
   * Nodes.     => Objetos que interpreta el navegador y donde esta el contenido de los elementos.
   * DOM.       => Se dejan todos los elementos en el "arbol" que representa todo el HTML.
* Pasos que sigue el navegador para construir las páginas web:
   * Procesa el HTML para construir el DOM.
   * Procesa el CSS para construir el CSSOM.
   * El DOM se une con el CSSOM para crear el Render Tree.
   * Se aplican los estilos CSS en el Render Tree.
   * Se ““pintan”” los nodos en la pantalla para que los usuarios vean el contenido de la página web.
## ✅Class#5⚡️
```5 tips para aprender CSS```
1. Identificar los diferentes selectores que se pueden usar:
    ```
    Universal => * {
                    margin: 0;
                }
    Tipo     => h1 {
                    color: red;
                }
    Clase    => .saludo {
                    font-size: 2em;
                }
    Id       => #id {
                    border-radius: 20px;
                }
    ```
2. Conecer la anatomía para declarar codigó css.
    ```
    Selector
        p   { propiedad
                color  :  red;
                        Valor
        }  
    |____________Declaración____________|
    ```
3. Compresión del modelo de caja.
    ```
    Margin
         Border
             Padding
                 Content
                     https://devcode.la/tutoriales/modelo-caja-css/
    ```
4. Domina como se posicionan los elementos absoluto, relativo, Flexbox y CSS Grid.
5. [Practicar Flexbox.](https://flexboxfroggy.com/#es)
## ✅Class#6⚡️
```Anatomía de un Elemento HTML: Atributos, Anidamiento y Elementos vacíos```
*   Algunos Elementos Html
    ```
    h1 Titulo principal
    h2       .
    h3       .  
    h4       .  
    h5       . 
    h6     Subititulo.
    ul => No importa el orden.
    ```
*   Nuestros elementos HTML se componen de:
    * Etiqueta de apertura: el nombre de nuestra etiqueta encerrado entre símbolos de mayor o menor. Por ejemplo: ```<h1>```.
    * Contenido: dentro de nuestras etiquetas podemos añadir texto u otros elementos HTML, lo que conocemos como anidamiento.
    * Etiqueta de cierre: son casi iguales que las etiquetas de apertura, pero también necesitan un slash (/) antes del nombre de la* queta. Por ejemplo: ```</h1>```.
*  Las etiquetas de apertura también pueden tener atributos.
 
    ```Los atributos nos permiten definir características especiales para nuestros elementos: <etiqueta atributo=""valor del atributo"">.*  ejemplo: <h1 class=""saludo"">.```
*  También existen elementos vacíos.

    ```Estos elementos no tienen contenido ni etiqueta de cierre, solo etiqueta de apertura y atributos. Por ejemplo: <img src=""puppy* "" alt="Descripción en caso de que la imagen no se pueda ver"mi mascota"">.```
## ✅Class#7⚡️
```Anatomía de un Documento HTML: DOCTYPE, html, head y body```

Identar es importante para identificar los elementos en el archivo ```.html <meta charset="UTF-8"> Incluye los símbolos según el lenguaje.```
## ✅Class#8⚡️
```Funciones de las etiquetas HTML más importantes```
    
    <!DOCTYPE html>  => Aquí definimos que el documento está bajo el estándar HTML5
       <html lang="es"> => Representa la raíz de nuestro documento HTML. Todos los démas elementos deben ser decendientes de este elemento.
       <head></html> => En el heada siempre vamos a encontrar los metadatos(que se escriben con la etiqueta vacía <mesta>) del documento    quevamos   a escribir, incluyendo también enlaces(que por los general son de nuestro archivo de estilos, fuentes..).
       <meta> => Define los metadatos que no pueden ser definidos usando otro elemento HTML, como por ejemplo el tipo de codificación UTF-8.
       <title></title> => Aquí definimos el título de nuestro documento, sólo puede contener texto y se muestra en la pestaña de la página.
       <body></body> => Es la única etiqueta body que debe aparacer en nuestro documento y representa todo el contenido principal. Aquí esdonde     escribimos las etiquetas <div>, <h1>, <p>, <footer>...
           <body>
               <h1>
               </h1>
               <h2>
               </h2>
               <div>
                   <p></p>
               </div>
               .
               .
               .
               <footer></footer>
           </body>
        <ol></ol> => Describe una lista ordenada.
        <ul></ul> => Describe una lista desordenada.
## ✅Class#9⚡️
```La importancia del código semántico```
* Es importante que como desarrolladores tengamos claro el significado de escribir código. Debes ser consciente de que la manera en la que codeas tenga sentido.
* La semántica HTML no es más que darle sentido y estructura a lo que estas escribiendo. Muy importante para el navegador. No todos los elementos deberían ser un div.
## ✅Class#10⚡️
```Tipos de errores en HTML, debugging y servicio de validación de etiquetas```
* Errores sintácticos:
    ```
    Son errores de escritura en el código y evitan que el programa funcione. Pueden ser errores de tipado.
    ```
* Errores lógicos:
    ```
    En estos la sintaxis es correcta, pero el código no hace lo que debería. El programa funciona, pero de forma incorrecta.
    ```
## ✅Class#11⚡️
```Reto 1: Organiza el siguiente bloque de código de forma semántica```
* Solución de reto
    ```
    Clase#11.html
    ```
## ✅Class#12⚡️
```Anatomía de una declaración CSS: Selectores, Propiedades y Valores```
* Nuestros estilos con CSS se componen de:
    * Selector
       Son la referencia a los elementos HTML que queremos estilizar. Los nombres de estas etiquetas van seguidas de una llave de ra    otra de cierre ({}). 
       ```
       Por ejemplo
         h1 {}
       ```
    * Propiedades
       Las propiedades deben estar dentro de las llaves del selector que definimos anteriormente. Podemos escribir diferentes piedades  mismo selector. 
       ```
       Por ejemplo 
          h1 { color: }
        ```
    * Valores
       * Son el estilo que queremos que tomen nuestros elementos HTML con respecto a una propiedad. Van seguidas de un punto y coma (;
        ```
            Por ejemplo:
                h1 { color: red; }
        ```
## ✅Class#13⚡️
```Tipos de selectores, pseudo-clases y pseudo-elementos```
* (asterisco) Es el selector universal. Las propiedades se aplicaran a todos los elementos de nuestro HTML. No es recomendado en aplicaciones muy grandes.
    ```
    Por ejemplo:
        * {
        margin: 0;
        }
    ```
* Tipo Son selectores que se aplican a cierto elemento HTML en específico. Las propiedades se aplicaran a la etiqueta que queremos.
    ```        
    Por ejemplo:
                p, body, html, div, etc.
                *h1{
                   height:20px;
                }
    ```
* Class: ```Si nuestras etiqueta de HTML tienen un atributo de class podemos usar ese valor o identificador para que los cambios en el CSS afecten únicamente a ese elemento.```
    ```
    Por ejemplo
        .NameClass {
            color:green;
        }
    ```
* ID: ```Es similar al anterior, si la etiqueta HTML tiene un ID podemos afectar solo ese elemento.```
    ```
    Por ejemplo
        #NameId {
             color:green;
         }
    ```
* Las Pseudo-clases y Pseudo-elementos: ```Nos permiten ser aún más específicos con qué elemento o partes de nuestros elementos deben recibir los estilos. Para usarlas debemos definir el selector base (por ejemplo, p ) seguido de dos puntos y la pseudo-clase que queremos estilizar (por ejemplo: p:first-child). En el caso de los pseudo-elementos debemos usar el dos puntos 2 veces (p::first-letter).```
    ```
    Por ejemplo
       p:first-child{
           color: white;
       }
       p:last-child {
           color: purple;
       }
       p:nth-child(2n) {
           color: red;
       }
    ```         
## ✅Class#14⚡️
```Modelo de caja```

    Todos los elementos de HTML tienen un modelo de caja y esta compuesto por cuatro elementos:
        ________________________________
        |margin                         |
        |   ____________________________|
        |   |Border                     |
        |   |    _______________________|
        |   |   |padding                |  
        |   |   |                       |
        |   |   |   ____________________|
        |   |   |   |Content            |
        |___|___|___|___________________|
                    margin-top
                    _________
                    |   12    |
                    |    |    |
        margin-left |9   .__ 3| margin-right
                    |         |
                    |____6____|
                    margin-bottom
## ✅Class#15⚡️
* Valores relativos y absolutos
* Los valores absolutos: ```Centímetros, milímetros, pixeles y pulgadas. Se llaman de esta forma porque no tienen en cuenta a nadie más, no depende de la ida de otra unidad.```
* Los valores relativos: ```Porcentajes, vmx, em, entre otros. Se llaman de esta forma porque depende de otra unidad de medida o elemento.```
## ✅Class#16⚡️
```Displays en CSS```

    Todos los elementos en CSS son cuadrados o rectángulos y aparte de eso, estos elementos tienen un comportamiento que se define a través de la propiedad display. Los display más comunes y usados son: block, inline, inline-block, none, table, flex y grid. Veamos de qué se tratan:
<img src="https://static.platzi.com/media/user_upload/Display%20en%20CSS-634bc14a-bdf5-4337-a67d-49fc74f92a60.jpg" alt="Display en CSS.png">

## ✅Class#17⚡️
```Funciones de las propiedades CSS más usadas```
* width: Define el ancho de un elemento. Por ejemplo: width: 20px;.
* height: Define el alto de un elemento. Por ejemplo: height: 20px;.
* background: Puede definir el color de fondo o la url de fondo de un elemento. Por ejemplo: background: url(';puppy.png';);.
* background-color: Define el color de fondo de un elemento. Por ejemplo: background-color: red;.
* color: Define el color de nuestros textos. Estos colores los podemos escribir de 3 formas en CSS:
    * Con los nombres de los colores. Por ejemplo: black, red, green.
    * Sistema hexadecimal: Donde blanco se define como #FFFFFF y negro como #000000. Una página que me gusta mucho para sacar colores en hexadecimal es colorhunt.co.
    * RGB: Donde la R significa Red, G significa Green y B significa Blue; por lo que escribimos rgb(red, green, blue) y cada uno de ellos es un valor de 0 a 255 que describe la intensidad de ese color. Por ejemplo, para denotar el color verde, escribimos: rgb(0, 255, 0). También a estos valores se les puede agregar una opacidad (transparencia) que va de 0 a 1, por ejemplo: rgba(0, 255, 0, 0.5) lo que quiere decir que el color verde lo queremos con una transparencia del 50%.
* border: Define el tamaño, estilo y color del borde de un elemento. Por ejemplo: border: 2px solid yellow;.
* border-radius: Define qué tan redondeado quiero mi elemento. Por ejemplo: border-radius: 20px;.
* margin: Define la margen de un elemento. Por ejemplo: margin: 2px (lo que quiere decir que mi elemento tendrá márgenes en todos sus lados de 2px).
* Si quiero que mi elemento tenga margen superior de 2px, margen inferior de 4px, margen derecha de 3px y margen izquierda de 5px, lo escribiría de la siguiente forma: margin: 2px 3px 4px 5px. El primer valor es la margen superior y siempre va en sentido de las manecillas del reloj.
* Si solo quiero que mi elemento tenga una margen a la derecha de 10px, escribiría margin-right: 10px;. Y para los demás valores sería margin-top: 10px; para la margen superior, margin-bottom: 10px; para la margen inferior y margin-left: 10px; para la margen izquierda.
* padding: Define la distancia del borde de un elemento hasta su contenido. Por ejemplo: padding: 2px (lo que quiere decir que mi elemento tendrá un “margen interno” en todos sus lados de 2px).
* Si quiero que mi elemento tenga padding superior de 2px, padding inferior de 4px, padding a la derecha de 3px y un padding a la izquierda de 5px, lo escribiría de la siguiente forma: padding: 2px 3px 4px 5px. El primer valor es la padding superior y siempre va en sentido de las manecillas del reloj al igual que con las márgenes.
* Si solo quiero que mi elemento tenga un padding a la derecha de 10px, escribiría: padding-right: 10px;. Y para los demás valores sería padding-top: 10px; para la margen superior, padding-bottom: 10px; para la margen inferior y padding-left: 10px; para la margen izquierda.
* font-size: Define el tamaño de la fuente. Por ejemplo: font-size: 20px;.
* font-family: Define la familia tipográfica de la fuente. Por ejemplo: font-family: 'Roboto', sans-serif;.
* opacity: Determina la transparencia del elemento. Tiene valores entre 0 y 1, que pueden verse como un porcentaje. Por ejemplo, si quiero que mi elemento se vea con una transparencia del 50%, escribiría: opacity: 0.5;.
* outline: Un término algo desconocido es el esquema de los elementos HTML. Un esquema es una línea (por defecto, de color azúl) que se dibuja alrededor de los elementos que hace que se “destaquen”.
* Lo anterior sucede mucho en elementos como los ```<input>``` y los ```<button>```. Si no queremos ver esa línea, lo que hacemos es outline: none;. Aunque también podemos decirle que tenga determinado estilo, color, tamaño, entre otras. Por ejemplo:
```
outline-style: solid;
outline-color: red;
outline-width: 5px;
```	
* box-sizing: Cuando trabajamos con paddings, por ejemplo, veremos que el tamaño de nuestro elemento crece. Es decir, si tengo:
```
    div {
    background: pink;
    width: 20px;
    height: 20px;
    }
```
* Y luego le agrego un padding de 20px, veré en el navegador que mi div ya no tiene un ancho y un alto de 20px, sino de 40px cada uno. Lo que quiere decir que el padding hizo que creciera mi elemento. Sin embargo, si yo no quiero que el padding afecte los 20px originales, le agrego la propiedad box-sizing para que el tamaño total del elemento incluya el padding también y no se vea afectado por él.
* transition: Las transiciones CSS le permiten cambiar los valores de las propiedades sin problemas durante una duración determinada. Debemos tener presente que una transición NO es una animación. Una transición va de un punto A, a un punto B sin interrupciones o saltos en medio.
* Te comparto la siguiente documentación para que puedas visualizar las propiedades y valores que puedes utilizar:
    * [https://www.w3schools.com/css/css3_transitions.asp](https://www.w3schools.com/css/css3_transitions.asp)
    * [https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions)
    * [https://css-tricks.com/almanac/properties/t/transition/](https://css-tricks.com/almanac/properties/t/transition/)
    * [https://www.w3schools.com/css/css3_animations.asp](https://www.w3schools.com/css/css3_animations.asp)
    * [https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations)
    * [https://css-tricks.com/almanac/properties/a/animation/](https://css-tricks.com/almanac/properties/a/animation/)
* animation: Esta propiedad permite que animemos nuestros elementos.
## ✅Class#18⚡️
```Posicionamiento en CSS ```
* El posicionamiento en CSS es una de las cosas más importantes, pues establece cómo van a estar ubicados nuestros elementos en la pantalla.
* En CSS los elementos se posicionan utilizando las propiedades top (superior), bottom (inferior), left (izquierda) y right (derecha), pero sólo funcionarán si la propiedad position está establecida. Esto quiere decir que si quiero que mi elemento div esté completamente a la derecha, debo escribir en mi CSS lo siguiente:
    ```
    div { position: absolute: right: 0px; }
    ```
* La propiedad position tiene 7 valores diferentes: relative, absolute, fixed, sticky, static, initial e inherit. Veremos de qué se tratan:
<img src="https://static.platzi.com/media/user_upload/Posicionamiento%20en%20CSS-6477ec29-d5d2-44d0-b3f5-c2876e0ee739.jpg" alt="Posicionamiento en CSS.png">
## 🚧Links🚨
* [Coolors](https://coolors.co/001514-fbfffe-6b0504-a3320b-e6af2e)
* [Paletton](http://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF)
* [Video](https://picular.co/Video)
* [Como combinan los colores](https://colorhunt.co/)
* [Pseudo-classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)
* [Pseudo-elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements)
* [Emoji-for-copy-and-paste](https://coolsymbol.com/emojis/emoji-for-copy-and-paste.html)
* [Validator](https://validator.w3.org)
* [More colors](https://coolors.co/5e1dfc-ab88ff-8f57fd-21c08b-e6af2e)
* [Muestra todos los elementos que podemos usar en css.](https://cssreference.io/)
* [Muestra todos los elementos que podemos usar en html.](https://htmlreference.io/)
* [HTMLGeneration.](http://line-mode.cern.ch/www/hypertext/WWW/Tools/HTMLGeneration/Overview.html)
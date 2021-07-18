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
    ***Tipos de errores en HTML, debugging y servicio de validación de etiquetas***
        ***Errores sintácticos***
            Son errores de escritura en el código y evitan que el programa funcione. Pueden ser errores de tipado.
        ***Errores lógicos*** 
            En estos la sintaxis es correcta, pero el código no hace lo que debería. El programa funciona, pero de forma incorrecta.
    ***Links**
        https://validator.w3.orgClase#9
## ✅Class#11⚡️
    ***Reto 1: Organiza el siguiente bloque de código de forma semántica***
        ***Solución de reto***
            Clase#11.html
## ✅Class#12⚡️
    ***Anatomía de una declaración CSS: Selectores, Propiedades y Valores***
        ***Nuestros estilos con CSS se componen de:***
            ***Selector***
                  Son la referencia a los elementos HTML que queremos estilizar. Los nombres de estas etiquetas van seguidas de una llave de apertura y otra de cierre ({}). 
                  ***Por ejemplo***
                    h1 {}
            ***Propiedades***
                  Las propiedades deben estar dentro de las llaves del selector que definimos anteriormente. Podemos escribir diferentes propiedades en un mismo selector. 
                  ***Por ejemplo***
                     h1 { color: }
            ***Valores***
                  Son el estilo que queremos que tomen nuestros elementos HTML con respecto a una propiedad. Van seguidas de un punto y coma (;). 
                  ***Por ejemplo***
                      h1 { color: red; }
## ✅Class#13**
    ***Tipos de selectores, pseudo-clases y pseudo-elementos***
        ***(asterisco)***
            Es el selector universal. Las propiedades se aplicaran a todos los elementos de nuestro HTML. No es recomendado en aplicaciones muy grandes.        
            ***Por ejemplo***
                * {
                   margin: 0;
                }
        ***Tipo***
            Son selectores que se aplican a cierto elemento HTML en específico. Las propiedades se aplicaran a la etiqueta que queremos.
            ***Por ejemplo***
                p, body, html, div, etc.
                *h1{
                   height:20px;
                }
        ## ✅Class***
            Si nuestras etiqueta de HTML tienen un atributo de class podemos usar ese valor o identificador para que los cambios en el CSS afecten únicamente a ese elemento.
            ***Por ejemplo**
                .NameClass {
                    color:green;
                }
        ***ID***
            Es similar al anterior, si la etiqueta HTML tiene un ID podemos afectar solo ese elemento.
            ***Por ejemplo**
                #NameId {
                     color:green;
                 }
        ***Las Pseudo-clases y Pseudo-elementos***
             Nos permiten ser aún más específicos con qué elemento o partes de nuestros elementos deben recibir los estilos.
             Para usarlas debemos definir el selector base (por ejemplo, p ) seguido de dos puntos y la pseudo-clase que queremos estilizar (por ejemplo: p:first-child). En el caso de los pseudo-elementos debemos usar el dos puntos 2 veces (p::first-letter).
             ***Por ejemplo***
                p:first-child{
                    color: white;
                }
                p:last-child {
                    color: purple;
                }
                p:nth-child(2n) {
                    color: red;
                }         
        ***Links**
            * https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes
            * https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-elements
            * https://coolsymbol.com/emojis/emoji-for-copy-and-paste.htmlClase#9
## ✅Class#14⚡️
* Modelo de caja:
    ``` Todos los elementos de HTML tienen un modelo de caja y esta compuesto por cuatro elementos```
    
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
* links
    * https://coolors.co/001514-fbfffe-6b0504-a3320b-e6af2e
    * http://paletton.com/#uid=1000u0kllllaFw0g0qFqFg0w0aF
    * https://picular.co/Video
    * https://colorhunt.co/ (Como combinan los colores).
## ✅Class#15⚡️
* Valores relativos y absolutos
* Los valores absolutos: ```Centímetros, milímetros, pixeles y pulgadas. Se llaman de esta forma porque no tienen en cuenta a nadie más, no depende de la ida de otra unidad.```
* Los valores relativos: ```Porcentajes, vmx, em, entre otros. Se llaman de esta forma porque depende de otra unidad de medida o elemento.```
## 🚧Links🚨
* [More colors](https://coolors.co/5e1dfc-ab88ff-8f57fd-21c08b-e6af2e)
* [Muestra todos los elementos que podemos usar en css.](https://cssreference.io/)
* [Muestra todos los elementos que podemos usar en html.](https://htmlreference.io/)
* [HTMLGeneration.](http://line-mode.cern.ch/www/hypertext/WWW/Tools/HTMLGeneration/Overview.html)
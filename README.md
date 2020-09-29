# CursoDeFrontendDeveloper
    https://platzi.com/clases/1640-frontend-developer/21874-presentacion-y-bienvenida-al-curso-de-html-y-css/
***Class#1**
    ***Presentación y bienvenida al curso de HTML y CSS***
***Clase#2**
    ***HTML y CSS: definición y usos***
        ***Historia***
            Interconnected + Network
                        =
                    Internet
            Tim Berners-Lee Fue el inventar de la Word Wide Web Y fundador de la W3C.
        ***Tecnologías que dieron paso al internet**
            1. HTTP => Hyper Text Transfer Protocol.
            2. URL  => Uniform Resource Locator.
            3. HTML => Hyper Text Markup Language.
            4. CSS  => Cascade Style Sheets.
            http://line-mode.cern.ch/www/hypertext/WWW/Tools/HTMLGeneration/Overview.html
***Clase#3***
    ***¿Qué son y para qué nos sirven HTML y CSS?***
        HTML => Es un lenguaje de marcado usado para decirle a tu navegador cómo estructurar las páginas web que visitas. No es un lenguaje de programación.
        CSS  => Es un lenguaje que nos permite crear páginas web con un diseño agradable para los usuarios. Tampoco es un lenguaje de programación.
            https://htmlreference.io/ => Muestra todos los elementos que podemos usar en html.
            https://cssreference.io/  => Muestra todos los elementos que podemos usar en css.
***Clase#4***
    ***DOM, CSSOM, Render Tree y el proceso de renderizado de la Web***
        ***DOM => Document Object Model.***
            Es una transformación del código HTML escrito por nosotros a objetos entendibles para el navegador.
        ***CSSOM => CSS Object Model*** 
            Así como el DOM para el HTML, EL CSSOM es una representación de objetos de nuestros estilos en CSS.
            https://developer.mozilla.org/es/docs/Web/API/CSS_Object_Model
        ***Render Tree*** 
            Es la unión entre el DOM y el CSSOM para renderizar todo el código de nuestra página web.
        ***Pasos de la transformación que hace el navegador***
            1. Bytes.     => 01110011101....
            2. Characters => Utf8,...
            3. Tokens.    => Etiquetas Html.
            4. Nodes.     => Objetos que interpreta el navegador y donde esta el contenido de los elementos.
            5. DOM.       => Se dejan todos los elementos en el "arbol" que representa todo el HTML.
        ***Pasos que sigue el navegador para construir las páginas web:***
            1. Procesa el HTML para construir el DOM.
            2. Procesa el CSS para construir el CSSOM.
            3. El DOM se une con el CSSOM para crear el Render Tree.
            4. Se aplican los estilos CSS en el Render Tree.
            5. Se ““pintan”” los nodos en la pantalla para que los usuarios vean el contenido de la página web.
***Clase#5***
    ***5 tips para aprender CSS***
        ***1. Identificar los diferentes selectores que se pueden usar.***
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
        ***2. Conecer la anatomía para declarar codigó css.***
                Selector
                    p   { propiedad
                            color  :  red;
                                    Valor
                    }  
                |____________Declaración____________|
        ***3. Compresión del modelo de caja.***
            Margin
                Border
                    Padding
                        Content
                            https://devcode.la/tutoriales/modelo-caja-css/
        ***4. Domina como se posicionan los elementos absoluto, relativo, Flexbox y CSS Grid.***
            https://flexboxfroggy.com/#es => Practicar Flexbox.
        ***5. Practica***
***Clase#6***
    ***Anatomía de un Elemento HTML: Atributos, Anidamiento y Elementos vacíos***
        ***Algunos Elementos Html***
            h1 Titulo principal
            h2       .
            h3       .  
            h4       .  
            h5       . 
            h6     Subititulo.
            ul => No importa el orden.
        ***Nuestros elementos HTML se componen de:***
            Etiqueta de apertura: el nombre de nuestra etiqueta encerrado entre símbolos de mayor o menor. Por ejemplo: <h1>.
            Contenido: dentro de nuestras etiquetas podemos añadir texto u otros elementos HTML, lo que conocemos como anidamiento.
            Etiqueta de cierre: son casi iguales que las etiquetas de apertura, pero también necesitan un slash (/) antes del nombre de la etiqueta. Por ejemplo: </h1>.
        ***Las etiquetas de apertura también pueden tener atributos.***
            Los atributos nos permiten definir características especiales para nuestros elementos: <etiqueta atributo=""valor del atributo"">. Por ejemplo: <h1 class=""saludo"">.
        ***También existen elementos vacíos.***
            Estos elementos no tienen contenido ni etiqueta de cierre, solo etiqueta de apertura y atributos. Por ejemplo: <img src=""puppy.png"" alt="Descripción en caso de que la imagen no se pueda ver"mi mascota"">.

# Navegación con anclas
### Crea una página con un menú (Inicio, Contacto, Acerca de) y añade las 3 categorías con un texto lerm ipsum*10 de relleno. Haz que cuando hagamos click en el enlace de cada uno de los elementos de la página nos lleve al corespondiente lugar.

Respuesta
~~~html
<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="http://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.4.0/css/font-awesome.min.css">
    </head>
    <body>
        <nav id="menu">
            <a href="#inicio">Inicio</a>
            <a href="#contacto">Contacto</a>
            <a href="#acerca-de">Acerca de</a>
        </nav>

        <h2 id="inicio">Inicio<a href="#menu"><i class="fa fa-upload"></i></a></h2>
        <p>Lorem ipsum ...</p>
        
        <h2 id="contacto">Contacto<a href="#menu"><i class="fa fa-upload"></i></a></h2>
        <p>Lorem ipsum ...</p>
        
        <h2 id="acerca-de">Acerca de<a href="#menu"><i class="fa fa-upload"></i></a></h2>
        <p>Lorem ipsum ...</p>
    </body>
</html>
~~~
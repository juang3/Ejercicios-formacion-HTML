# Ejercicios de encabezado y párrafos
### ¿Por qué no es recomendable meter un elemento en bloque dentro de un elemento en línea? Argumenta la respuesta.

~~~
<a href="/"><p>Bad HTML</p></a>     ❌
<p><a>href="/"</a>Bad HTML<p>       ✔️
~~~ 

Previos:
* inline: etiqueta que adapta tu tamaño para entrar en las zonas no ocupadas.
* bloque: etiqueta que ocupa todo el ancho de la ventana.
    
Respuesta

    1. Incluir una etiqueta de bloque <p> dentro de una etiqueta inline <a>, provoca la situacion donde la etiqueta <a> queda dividida en dos partes:
        1. La parte que hay antes el bloque <p>
        2. La parte que hay después del bloque <p>
    Pues el bloque ocupa todo el ancho de la ventana.

    2. Incluir una etiqueta inline <a> dentro de una etiqueta de bloque <p>, provoca que la etiqueta inline se adapte al espacio no usado por la etiqueta de bloque.
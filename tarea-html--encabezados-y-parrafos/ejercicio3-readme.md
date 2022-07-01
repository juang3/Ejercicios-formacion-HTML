# Ejercicios de encabezado y párrados
### Duplicando uno delos ejercicios anteriores y minificalo con una aplicación para el VSC o ien desde alguna págna web online ¿Qué está pasando? Analiza si el tamaño del fichero se reduce.

~~~
Comando bash:
$ ll -h ejercicio3*html | cut -d " " -f 5,10

Resultado:
1.8K ejercicio3-index-reducido.html
2.0K ejercicio3-index.html
~~~

### Observación:
    Tamaño inicial          2.0K
    Tamaño comprimido       1.8K

    Direferencia            0.2K
    Reducción del archivo   10%
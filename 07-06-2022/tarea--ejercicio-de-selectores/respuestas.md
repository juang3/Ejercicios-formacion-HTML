
## Level 1: 
~~~html
   <p>select me</p>
~~~
    Respuesta: p
## Level 2: 
~~~html
   <p id="me">select me</p>
   <p>but not me!</p>
~~~
    Respuesta:  #me
## Level 3: 
~~~html
    <p class="lol">select me</p>
    <em class="lol">and me</em>
    <p>but not me</p>
~~~
    Respuesta:  .lol 
##  Level 4: 
~~~html
    <p class="lol wut">select me</p>
    <p class="lol">but neither me</p>
    <p class="wut">nor me</p>
~~~
    Respuesta:  .lol.wut
##  Level 5: 
~~~html
    <p class="meh">select me</p>
    <p>but neither me</p>
    <em class="meh">nor me</em>
~~~
    Respesta:   p.meh
##  Level 6: 
~~~html
    <p>select me</p>
    <em id="bop">and me</em>
    <em>but not me</em>
~~~
    Respuesta:  p, #bop
##  Level 7:
    If you'd like to see more levels, please tweet @toolness. Or fork the code and add your own levels!
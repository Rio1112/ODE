# ODEs

##Introduccion
Para este trabajo resolveremos ecuaciones diferenciales usando rk2, rk4 y euler. 
Estas 3 formas de resolver EDOs seran aplicadas a diversas ecuaciones donde hablaremos de en que caso resulta mejor utilizar un metodo en concreto y sus diferencias.


##Metodo de Euler
Este metodo se basa en una expansion de Taylor de una funcion x(t). De manera que hacemos x(t+h), donde h representa un salto infinetesimal en el tiempo. SU expansion de Taylor es la siguiente. 

$Taylor[ x(t+h) ]= x(t) + h\frac{dx}{dt} + \overbrace{ \frac{h^2}{2} \frac{d^2x}{dt^2} } ^{\epsilon} + O(h^3 ) $


## Rounge-Kuta 

El metodo de Rounge-Kutta es un metodo numerico el cual se usa para aproximar la solucin de una ecuacion diferencial. Este es uno de los metodos mas utiles para la resolucion de ecuaciones diferenciales debido a su estabilidad. Hay varios tipos de Rounge-Kutta cuya diferencia radica en su grado. Este es un metodo que parte del metodo de Euler, no obstante, este tiene un mayor rendimiento a nivel computacional. A continuacion veremos dos formas de este. 



## RK2



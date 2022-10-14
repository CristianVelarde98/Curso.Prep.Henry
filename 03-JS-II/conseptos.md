Bucle for
 El bucle for es un statement que nos va a ayudar a la hora de escribir y optimizar nuestro codigo. Siempre tenemos que tratar de resolver los problemas con astucia y tener en cuenta si hay una solucion mas facil o practica que estamos ignorando, el bucle for nos va a ayudar en esto ya que lo vamos a usar para tares repetitivas que de hacerlas a mano seria muy complicado e ineficiente. 
  La sintaxis del bucle for es la siguiente:
   for (variable del contador; condicion del contador; incremento de la variable) {
     //codigo
   }
 Primero que nada vamos a tener que defini una variable que la vamos a usar solo para el bucle, osea que va a ser usada dentro del scope del bucle. Luego tenemos que definir nuestra condicion, es importante prestar atencion a que la condicion se cumple en un determinado momento por que podemos tarminar creando un bucle infinito que puede trabar el codigo y el equipo, el bucle se va a ejecutar mientras se cumpla la condicion establecida y se va a dejar de ejecutar cuando la condicion ya no se cumpla. un ejemplo podria ser: condicion (a <= 10) esto quiere decir que el bucle for se va a ejecutar mientras la variable previamente definida a sea menor o igual a 10, cuando esta condicion se deje de cumplir ya no se va a ejecutar el bucle. Por ultimo y tambien muy importante el incrementador del contado, por lo general va a se el operador ++, esto quiere decir que cada vez que se ejecute el bucle se le va a sumar 1 a la variable y de esta forma va a ir incrementando el valor hasta que ya no se cumpla la condicon que planteamos y se detenga el bucle. 
  EJEMPLO:
  for (var a = 0; a <= 10; a++) {
    console.log(a);
  }
 De esta forma le estamos diciendo al interprete lo siguiente: primero le defino una variable a que va a usar para contar y le asigno un valor de incio 0, luego le digo que quiero que antes de ejecutar el bucle se fije si el valor de a sea menor o igual a 10 para ejecutar el bucle, de otra forma no quiero que ejecute el bucle y antes de ejecutar el bucle quiero que le sume un 1 a la variable a. luego de que hizo esto el interprete ejecuta el codigo que hay adentro del bucle en este caso le pedi que en cada momento imprima el valor de la variable a de forma que medida vaya incrementando a se va a ir imprimiendo el resultado de ese incremento en la pantalla hasta que se deje de ejecutar el bucle, osea que va a imprimir en la pantalla el numero del 0 al 10. hacerlo de esta forma es importante porque nos ahorramos de escribir muchas lineas de codigo repetidas y medida que el numero vaya aumentando se nos iba a hacer mas dificil o imposible de escribir una por una.

A continuacion vamos a ver 3 operadores logicos:

-Operador logico "Y": AND "&&"
El operador logico and, en español dicho como y, es un operador de control de flujo que se fija si las 2 expreciones que estan a su izquierda y derecha son verdaderos, si ambas expresiones son verdaderas el operador va a devolver como resultado true, osea verdadero. Con que una de las dos condiciones sea falsa el operador va a devolver falso.

-Operador logico "O": OR "||"
 Este operador va a evaluar las dos expreciones que esten a su izquiera y a su derecha, si una de las 2 condiciones resulta ser verdadera entronces devolvera true. solo si las 2 condiciones son falsas devolvera falso.

-Operador logico "NO/CONTRARIO/NO ES": NOT "!"
 este operador se puede agregar a cualquier expresion o a otro operador para indicar lo contrario de la premisa original. por ejemplo si usamos la expresion (a !>= b) la con esa expresion va a ser verdadera mientras que a NO sea mayor o igual a b. 
  El operador NOT va a devolver el valor booleano OPUESTO de lo que se le pase. 
  
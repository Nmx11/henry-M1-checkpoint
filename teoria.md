## Explica los siguentes conceptos con tus propias palabras. (no más de tres líneas por respuesta).

* Estructura de Datos:
Es una forma particular de organizar datos para que puedan ser utilizados y manejados de manera eficiente. Una estructura de datos eficiente es clave para diseñar algoritmos eficientes. Se usa, por ejemplo, en grandes bases de datos y servicios de indización de internet.

* Lista Enlazada:
Es una secuencia de nodos (que son puntos de unión que contienen información y una referencia o link a otro nodo) unidos entre ellos y que contienen información. Una lista enlazada solo puede recorrerse en forma lineal y hacia adelante. Hay otros tipos de listas enlazadas como las dobles o múltiples.

* Árbol:
Son estructuras de datos que consisten en una serie de nodos conetados entre ellos. Tiene la particularidad de asemejarse estructuralmente a un arbol y se puede recorrer desde el nodo raíz hasta los nodos hojas. Sus componentes son: la raíz, padre, hijo, hermanos, hojas, nivel y camino.

* Closures:
Al terminar de ejecutar y retornar una función, su contexto es destruido, pero las variables usadas dentro de ese contexto son almacenadas en memoria y se puede acceder a ellas desde otro scope porque queda una referencia al lexical enviroment de la función retornada aunque ya no exista. 
 
* Contexto de Ejecución:
Contiene información sobre que código se está ejecutando en cada momento y el lexical enviroment que se está manejando en cada instancia.

* Variable THIS:
Es una variable que apunta a distintos objetos dependiendo de donde se la esta llamando. Si this no está dentro de un objeto, entonces hace referencia al objeto padre y en caso de no haberlo se hace referencia al objeto global, que el lenguaje javascript entiende como ¨window¨.

* Hoisting:
Javascript mueve automaticamente las declaraciones hechas en el código al principio del scope donde se han escrito. Por ejemplo, se puede llamar a una función y definirla más abajo en el código, javascript automáticamente va a subir la definición antes del llamado y la función funcionará.

* Pasar por valor y por referencia:
Cuando se pasa un valor por referencia, se está pasando una referencia al objeto original y si esta es modificada el original tambien sufre la misma modificación. Cuando se pasa algo por valor se pasa como si fuera una copia del original, que existe por si misma, entonces el original no es modificado.

* Algoritmo:
Un algoritmo es como una receta que contiene un conjunto de instrucciones, que están ordenadas y permiten realizar una actividad o resolver problemas, siguiendo los pasos sucesivos y las reglas que esta receta dicta.

* Big O notation:
Se utiliza para analizar la complejidad de los algoritmos. Un algoritmo se puede comparar con las funciones tipicas del big O (O(1), O(n), O(log N), O(n2), O(N!)) y apartir de esta comparación, dependiendo a cual de estas funciones se parece más, el algoritmo será más o menos eficiente.

* Inmediatly Invoked Function Expression (IIFF):
Es cuando se invoca a una función inmediatamente despues de escribir la expresión. Por ejemplo: var saludo = function() { return ¨hola¨;}(). Al poner () luego de definir la función se llama a esta de inmediato.



# GUIA 6
## Sesion 1

1. Responda las siguientes preguntas y de un ejemplo en cada caso:
   
• ¿Qué diferencias encuentra entre un arreglo y una lista Enlazada?

*SOLUCION |* Los arreglos almacenan elementos de forma contigua en la memoria, permitiendo acceso aleatorio eficiente, pero insertar o eliminar elementos puede ser costoso. Por otro lado, las listas enlazadas no tienen elementos contiguos, lo que facilita la inserción y eliminación de elementos, aunque el acceso aleatorio es menos eficiente. Los arreglos tienden a usar menos memoria y son mejores para acceso aleatorio, mientras que las listas enlazadas son ideales para operaciones frecuentes de inserción y eliminación.

• ¿Cuáles son las diferencias entre las clases ArrayList, LinkedList y Vector
utilizadas en Java? Realice un cuadro comparativo

*SOLUCION |* https://docs.google.com/document/d/1Jd6sz0XTGTCEdaqxe5aD4114TR2kyUG3A-GdaCJk-I8/edit?usp=sharing

Identifique 5 aplicaciones de las listas circulares en el ámbito de su carrera

*SOLUCION |*   Aplicaciones de las listas circulares en Java en el ámbito de la Ingeniería de Software:

Implementación de colas circulares en sistemas distribuidos: Las colas circulares pueden ser utilizadas para implementar sistemas de mensajería en aplicaciones distribuidas donde los mensajes deben ser procesados en un orden específico y la capacidad de la cola debe ser limitada para evitar la saturación del sistema.

Representación de trayectorias cíclicas en grafos: En aplicaciones que involucran grafos donde las trayectorias pueden ser cíclicas, como en algoritmos de búsqueda de ciclos o en sistemas de enrutamiento de redes, las listas circulares pueden ser utilizadas para representar estas trayectorias de manera eficiente.

Gestión de eventos en aplicaciones GUI: En el desarrollo de aplicaciones con interfaces gráficas de usuario (GUI), las listas circulares pueden ser útiles para implementar sistemas de gestión de eventos donde los eventos deben ser procesados de manera cíclica, como en animaciones o en la rotación de elementos de la interfaz.

Implementación de buffers circulares en sistemas embebidos: En sistemas embebidos donde el espacio de memoria es limitado, las listas circulares pueden ser utilizadas para implementar buffers circulares para la recepción y transmisión de datos, permitiendo un uso eficiente de la memoria disponible.

Aplicaciones en sistemas de gestión de memoria: En sistemas operativos y entornos de ejecución de programas, las listas circulares pueden ser utilizadas en la implementación de algoritmos de gestión de memoria, como en la asignación de bloques de memoria o en la administración de la memoria virtual.

3. Explique claramente en qué consiste una pila y como es su funcionamiento.

*SOLUCION |* Una pila en Java es una estructura de datos que sigue el principio de LIFO (Last In, First Out), lo que significa que el último elemento en ser insertado es el primero en ser eliminado. En Java, las pilas son implementadas mediante la clase Stack, que es una subclase de Vector.

El funcionamiento de una pila en Java se puede resumir en los siguientes puntos:

Push (Empujar): Se utiliza el método push() para insertar un elemento en la parte superior de la pila. Este elemento se coloca en la posición superior de la pila.
Pop (Sacar): Se utiliza el método pop() para eliminar y devolver el elemento que está en la parte superior de la pila. Este elemento es eliminado de la pila.
Peek (Mirar): Se utiliza el método peek() para obtener el elemento que está en la parte superior de la pila sin eliminarlo. Este método devuelve el elemento, pero no lo elimina de la pila.
Empty (Vacía): Se utiliza el método empty() para verificar si la pila está vacía o no. Devuelve true si la pila está vacía y false si contiene elementos.

4. Describa 3 aplicaciones de las pilas en su vida como ingeniero.

*SOLUCION |*

1. Evaluación de expresiones aritméticas: Las pilas son ampliamente utilizadas en la evaluación de expresiones aritméticas en la conversión de notación infija a postfija y en el cálculo del resultado. Por ejemplo, en la implementación de calculadoras o en el análisis de fórmulas matemáticas en programas de ingeniería.

2. Gestión de llamadas en sistemas operativos: En sistemas operativos, las pilas son utilizadas para gestionar las llamadas a funciones y el paso de parámetros entre ellas, lo que permite mantener un seguimiento de las llamadas activas y las variables locales de cada función.
   
3. Implementación de algoritmos de búsqueda en profundidad (DFS): En algoritmos de búsqueda en grafos como el DFS (Depth-First Search), las pilas son utilizadas para mantener un seguimiento de los nodos visitados y los nodos vecinos que aún no han sido explorados, lo que permite recorrer el grafo de manera recursiva.

### Presaberes Requeridos:

1. Son secuencias de elementos almacenados en una lista encadenada
   
a. Pila

2. Comparadas con los vectores, estas permiten una mayor rapidez de inserción
y borrado, pero una menor velocidad de acceso aleatorio Pilas Listas Colas.

c. Lista

3. Es una estructura FIFO, first in, firstout.

b. Colas



### Trabajo Autonomo:

Describir cómo se declara una pila en los siguientes lenguajes de programación:
Pascal, Crystal, D, Delphi, Elisa, Forth, Julia, Lingo, Mercury, Prolog, Ruby, UnixPipes, R.

*SOLUCION |*

Pascal: 

type
  Stack = array[1..MAX_SIZE] of Integer;
  
Crystal:

stack = Array(Int32)

D:

Stack!(int) stack;

Delphi:

var
  stack: array of Integer;
  
Elisa:

stack : [Int] # Declaración de una pila de enteros

Forth:

CREATE stack 10 CELLS ALLOT

Julia:

stack = Int[]

Lingo:

global stack = []

Mercury:

:- type stack(T) == list(T).

Prolog:

:- dynamic(stack/1).

Ruby:

stack = []

UnixPipes:

declare -a my_stack

R:

stack <- NULL




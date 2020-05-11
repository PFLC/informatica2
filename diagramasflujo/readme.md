# TÉCNICAS DE RESOLUCIÓN DE PROBLEMAS

En el mundo de hoy, una computadora se usa para resolver varios tipos de problemas, porque lleva mucho menos tiempo en comparación con un ser humano. El seguimiento se resuelve un problema:

1. Analiza el problema dado.
2. Divida el proceso utilizado para resolver el problema en una serie de Tareas.
3. Formule el algoritmo para resolver el problema.
4. Exprese el algoritmo como una notación precisa, que se conoce como un programa de computadora.
5. Alimente el programa de computadora en la computadora. La CPU interpreta el programa dado, procesa los datos en consecuencia, y genera el resultado.
6. Envíe el resultado generado a la unidad de salida, que lo muestra.

**Los algoritmos y los diagramas de flujo son dos técnicas importantes** que ayudan a los usuarios a resolver problemas o realizar tareas usando una computadora.

Un algoritmo es un método paso a paso completo, detallado y preciso para resolver un problema de forma independiente del software o hardware de la computadora. Los algoritmos son muy esenciales, ya que instruyen a la computadora qué pasos específicos debe realizar para llevar a cabo una tarea en particular o para resolver un problema. Comprender cómo funciona un algoritmo.

_El enfoque de arriba hacia abajo de un algoritmo para resolver un problema dado también se conoce como divide y vencerás. En este enfoque, el problema dado se divide en dos o más subproblemas, cada uno de los cuales se parece al original, la solución de cada subproblema se saca de forma independiente. Finalmente, la solución de todos los subproblemas se combinan para obtener la solución del problema principal._


## CONCATENACION

Una cadena es una secuencia de caracteres que se trata como un único elemento de datos. Hemos utilizado cadenas en varios ejemplos en el pasado. Cualquier grupo de caracteres (excepto el signo de comillas dobles) definido entre comillas dobles es una constante de cadena. Al usar el **símbolo & ** permite unir cadeanas de texto con variables, recordemos agregar espacio para que se separen los resultados. "Nombre es " & nombreAutor


# MATRICES

Una matriz es una colección secuenciada de elementos de tamaño fijo del mismo tipo de datos. Es simplemente una agrupación de datos de tipo similar. En su forma más simple, se puede usar una matriz para representar una lista de números o una lista de nombres. Algunos ejemplos en los que se puede usar el concepto de matriz:
- Lista de temperaturas registradas cada hora en un día, un mes o un año.
- Lista de empleados en una organización.
- Lista de productos y su costo vendido por una tienda.
- Resultados de exámenes de una clase de estudiantes.
- Lista de clientes y sus números de teléfono.
- Tabla de datos diarios de tipos de cambio dolar.


La capacidad de usar un solo nombre para representar una colección de artículos y para referirse a un artículo especificando el número de artículo nos permite desarrollar programas concisos y eficientes. Por ejemplo, podemos usar una construcción de bucle, con el subíndice como la variable de control para leer toda la matriz, realizar cálculos yimprime los resultados.
Podemos usar matrices para representar no solo listas simples de valores sino también tablas de datos en dos, tres o más dimensiones. 
Lostipos de matrices
- Matrices unidimensionales, **para efecto de este curso veremos solo esta sección**
- Matrices bidimensionales
- Matrices multidimensionales


# Trabajando con Flowgorithm con matrices Unidimensionales 

![](https://pbs.twimg.com/profile_images/905575120705486848/ZburZtMW_400x400.jpg)

Matrices unidimensionales, una lista de elementos se le puede dar un nombre de variable usando solo un subíndice y tal una variable se denomina variable de subíndice único o matriz unidimensional.

Por ejemplo, si queremos representar un conjunto de cinco números, digamos (35, 40, 20, 57, 19), por una matriz número variable, entonces podemos declarar el número variable de la siguiente maneraint número [5];y la computadora reserva cinco ubicaciones de almacenamiento como se muestra a continuación: 

 Programación para la resolución de problemas número 
 ```
numero = [10]   // es la forma de declarar un "array" o arreglo unidimensional sencillo.
 
 Los valores de los elementos de la matriz se pueden asignar de la siguiente ejemplo:
 numero[0] = 35;
 numero[1] = 40;
 numero[2] = 20;
 numero[3] = 57;
 numero[4] = 19; 
 
  ```
 **notece que 0 es la primera posición**, para el efecto del ciclo o bucle, son reglas de programación.

# INICIALIZACIÓN DE ARREGLOS DIMENSIONALES
_Después de declarar una matriz, sus elementos deben inicializarse. De lo contrario, contendrán "basura". Una matriz puedese inicializar, podemos usar un "ciclo for" para asignación de CERO por ejemplo o un " " (espacio) si es cadena de texto

Ejercicios de Matrices:

El programa que usa una matriz unidimensional 100 para leer los valores ALEATORIOS y calcular la suma de sus cuadrados.

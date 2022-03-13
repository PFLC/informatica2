2.1 DIAGRAMAS DE FLUJO CON FLOWGORITHM

Los diagramas de flujo son recursos visuales que se usan para representar un algoritmo que utilizan símbolos y flechas en lugar de palabras. Tales símbolos tienen un significado definido y se unen mediante flechas, las cuales indican el orden del flujo.
(imagen de las figuras)
Reglas para diseñar diagramas de flujo:
- Los diagramas de flujo siempre se escriben de arriba abajo y de izquierda a derecha
- Dentro de cada símbolo se escribe un texto que indica la operación por realizar, el cual debe ser legible, preciso y con la menor cantidad de palabras.
- Los símbolos se unen con flechas (líneas de flujo), las cuales únicamente pueden ser horizontales y verticales.
- No deben haber símbolos sin conectar
- Tienen que tener una figura inicial y una final (main & end)

Utilizaremos un programa llamado Flowgorithm para crear los diagramas de flujo, las ventajas de este programa es que es fácil de usar, puedes compilar tu diagrama como si fuera un programa e incluso existe la opción de ver tu diagrama en algún lenguaje de programación, entre los que se encuentra java, c++, pascal, entre otros.

Flechas: Muestra la dirección y sentido de flujo del proceso. conecta a los símbolos
- Inicio y fin: Señala el comienzo y fin del diagrama, deben de haber 2 figuras de estas en cada diagrama, una indica el inicio y otro el fin.
- Declarar: Esta figura nos ayuda a declara las variables que usaremos, todas las variables se deben de declarar, sino no funcionara el diagrama, por lo regular las variables se declaran al principio del programa
- Asignar: Esta figura nos permite asignarle valores a las variables, ya sean valores asignados por el usuario o ya establecidos (como 3.1416)
- Input y output: Cumplen con la función de entrada y salida de datos, output lo usaremos pàra mostrar mensajes al usuario, mientras que input nos servirá para almacenar los datos ingresados.
- If: Esta figura funciona con una condición, si se cumple se ejecutará parte del código, sino se ejecutara otra diferente.
- Ciclos o bucles: También llamados bucles, estos ejecutan parte del codigo segun una condicion. cuando la condición deje de cumplirse el ciclo termina. existen 3 tipos de ciclos (while, for, do) que se ejecutan de distintas formas.


EJEMPLO

Volveremos a usar de ejemplo el siguiente problema:
Se debe calcular el área y el perímetro de un terreno rectangular.
El algoritmo quedó de la sig. forma:

1. Inicio
2. Solicitar base y altura
3. Leer base y altura
4. Calcular area=base*altura
5. Calcular perimetro=(base+altura)*2
6. Imprimir "El área del terreno es:" área
7. Imprimir "El perímetro es: " perimetro
8. Fin
   
   !´+
 
## PASOS 
1. Declaramos 4 variables, una para base, altura, area, perimetro, un consejo que te doy es que declares los variables con nombres cortos incluso puedes nombrarlas  con solo una letra si asi lo queres.
2. Agregamos output e input de la siguiente forma , esto para que al preguntar la base se almacene en su variable y con la altura también.
3. Calculamos el área, para esto le asignamos una expresión a la variable x para que pueda calcularla, recuerda que debemos escribir toda expresión de forma lineal (como una ecuación).
4. Hacemos lo mismo con la variable w (perímetro)
5. Ahora que ya tenemos los resultados, debemos mostrarlos al usuario, para esto usaremos el output, escribimos "El área es: " en comillas porque es una serie de caracteres, seguido de &x, necesitamos el amperson pàra indicar que el mensaje mostrará una variable. podemos mostrar también el perímetro en el mismo mensaje, solo debemos respetar la nomenclatura ("El perímetro es: "&w).
6. Listo, terminamos el diagrama, lo bueno de Flowgorithm es que puedes ejecutarlo para verificar que funcione correctamente, así que lo probaremos para verificarlo.


Bibliografía:
_http://softwareestructurado.blogspot_ 2018

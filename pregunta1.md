## Pregunta 1
El campeonato mundial de carreras de cuyes está organizado con una serie de
bases unidas por canales. Cada canal representa una carrera independiente con su
propio premio. Además éstos canales son muy exigentes para los roedores y el
campeonato se desarrolla en un solo día de modo que los concursantes como usted,
prefieren elegir en qué canales hacer participar a los animalitos. Todos los
cuyes deben iniciar en el primer punto y de allí, las inteligentes criaturas
tomarán el camino que sus entrenadores les indiquen, del mismo modo en cada
punto que visiten hasta el último punto, donde son retirados para recibir su
merecido alimento y descanso. Los cuyes no pueden regresar al mismo punto 2
veces y usted, siendo un experto en grafos, ha decidido hacer un algoritmo para
averiguar cual sería la secuencia de canales más rentable, recuerde que cada
canal tiene un premio distinto, y usted desea maximizar sus premios

### Input
Cada archivo de entrada tendrá un solo caso de prueba en el que cada línea
representa dos puntos, numerados desde cero y el correspondiente premio por del
canal que los une. Por ejemplo `0 1 5` representa el canal del punto 0 al punto
1 tiene un premio de 5 unidades.

### Output
La salida deberá ser la secuencia de puntos que el cuy debe visitar, uno por
línea y el premio total acumulado.

### Ejemplo de input

    0 1 5
    0 2 6
    1 2 3
    1 3 2
    2 3 4

### Ejemplo de output

    0
    2
    3
    1
    Total: 12

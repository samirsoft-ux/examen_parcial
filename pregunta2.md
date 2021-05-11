# Premio 2

Los estudiantes de complejidad algorítmica de la UPC son muy sociables y todos
son amigos. Sin embargo cuando se trata de realizar trabajos, son sumamente
exigentes y por ello solo desean trabajar con ciertos estudiantes. De hecho
cada estudiante tiene una lista de estudiantes con quienes desean hacer grupo.
Los profesores se han dado cuenta de éstas conexiones y han decidido pedirle a
usted, experto en complejidad algorítmica, que elabore una rutina para definir
información para formar grupos. Se desea conocer, cuantos alumnos se quedarían
sin grupo, y definir el tamaño del grupo más grande. Considerando que es posible
formar grupos siempre y cuando cada estudiante esté de acuerdo en hacer grupo
con alguien que no ha considerado directamente, siempre y cuando alguien más en
el grupo, si lo haya considerado. Es decir, si A desea hacer grupo con B, pero
no con C, pero B si desea hacer grupo con C y a su vez C si desea hacer grupo
con A, entonces los 3 pueden formar grupo. Obviamente, las relaciones son
unilaterales

## Input
Por cada archivo de entrada tiene un solo caso de entrada en el que en cada
línea tiene, como primer elemento, el código de un alumno, seguido de los
códigos de los alumnos con los que estaría de acuerdo formar grupo.

## Output
En la primera línea se indicará la cantidad de alumnos que se quedarían sin
grupo. En la segunda línea el tamaño de grupo más grande.

## Ejemplo de Input

    1 2
    2 3
    3 4
    4 2
    5 4
    6 5 7
    7 6

## Ejemplo de Output

    2
    3

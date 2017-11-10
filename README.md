# Práctica 3 de Estructura de Computadores

**Enunciado.-** Crear el T.D.A Pila_max (Pila con máximo). Esta Pila contiene un conjunto de enteros pero
además se almacena el valor máximo que existe en la Pila. Supongamos que tenemos una pila
a la que se le han insertado los datos 2, 7, 6 y 9.
En la primera inserción se pone el dato 2. Como la pila estaba vacía 2 este valor será el
máximo.
En el paso 2 se inserta el dato 7. Ahora para establecer cual es el máximo que hay que poner
junto con 7, se compara 2 con el máximo previo, que es 2. En este caso como 7 es mayor este
valor es el que se pone como máximo con el dato 7.
En el paso 3 se inserta 6 y se vuelve a repetir el proceso de comparación. Por lo tanto se
compara 6 con el máximo previo que es 7, como 7 es mayor se pone 7 como máximo del dato
6.
Finalmente en el paso 4 se inserta el valor 9, y se compara 9 con 7, como 9 es mayor este se
coloca como máximo.

El alumno debe llevar a cabo las siguientes tareas:
1. Dar una especificación del T.D.A. Pila_max
2. Definir el conjunto de operaciones con sus especificaciones
3. Usar dos estructuras de datos para implementar el T.D.A. Pila_max
• Como un Vector Dinámico. Esta implementación será el módulo Pila_max_VD
(Pila_max_VD.h y Pila_max_VD.cpp).
• Como un Cola. Esta implementación se desarrollará en el módulo Pila_max_Cola
(Pila_max_Cola.h y Pila_max_Cola.cpp).
4. Probar los módulos con programas test.
IMPORTANTE: Para llevar a cabo la implementación de los diferentes módulos no se
podrá usar la STL.


# -AYD1-Practica1_G2
Implementacion de despeje de ecuaciones lineales y cuadraticas de una sola variable

La feature resuelve errores sintacticos automaticamente antes de entrar al motor matematico, los errores sintacticos que resuelven se detallan a continuacion:
* Agrega signo de multiplicar * a expresiones implicitas, ej. `4X -> 4*X`
* Resuelve la funcion f(x) = 0, ej. `-20*X + 5 = 4*X -> -20*X + 5 - 4*X = 0`

>- Aldo Rigoberto Hernandez Avila
>- Luis Enrique Patal Ajzac
>- Cinthya Andrea Palomo Galvez 201700670
>- Diego Vasquez 201602421
>- Jose Fernando Guerra Muñoz 201731087

- Suma
- Resta
- Multiplicacion
- Division
- Potencia
- Raiz N

Para la otra pestaña, Operaciones Avanzadas, esta se encuentra dividida en 2 secciones, ya que la primera seccion es para las ecuaciones lineales o cuadraticas y solo tienen una variable ademas de que el usuario ingresara la ecuacion completa para luego despejar la variable. Mientras que en la otra seccion se le pide al usuario que ingrese el numero de variables que seran utilizadas en la ecuación estas variables seran almacenadas en un array de tipo variable, mientras se le va pidiendo al usuario que introduzca el nombre y el valor. Luego seguido de esto el usuario ingresara la ecuacion haciendo uso de las variables que creo para esta, para desplegar el resultado que esta obtendra al usar dichar variables.

### Clase HistorialOp
Se creó una clase para guardar en una lista el historial de cada operación y su debido resultado.
### Clase Historial
Este servirá para crear el historial con el .jar de Itext para crear un pdf con el nombre Operaciones.pdf que contendrá en una tabla las operaciones recientes. 

<b>Feature Variables_201408562</b>

Esta característica permite asignar valores enteros o reales a literales para que estas puedan ser usadas dentro de una expresión. Ejemplo: a = 5, b = 10, c = 30.

# Referencia

>- https://github.com/xcheko51x/iTextPDF-JAVA
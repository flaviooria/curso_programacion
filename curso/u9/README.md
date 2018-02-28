# Asignación de variables

Una vez que hemos definido una variable, podemos asignarle un valor con el operador de asignación (`<-` ó `:=`). El dato que se guarda en una variable puede estar expresado por un literal, guardado en otra variable o calculado tras operar una expresión. Por ejemplo:

	var1 <- 7;
	var2 <- var1;
	var3 <- var1 + var2;

Como diagrama de flujo:

![asignacion](img/asignacion.png)

Tenemos que tener en cuenta lo siguiente:

* No se puede asigna un valor a una variable que no haya sido definida con anterioridad.
* No se puede utilizar una variable sin inicializar.
* Con cada asignación se pierde el valor anteriormente guardado en la variable.

Las siguientes asignaciones producen error:

* Una variable real (con parte decimal) si se asigna una variable entera.
* Una variable cadena de caracteres si se asigna a una variable numérica.
* Una variable numérica si se asigna a una variable cadena de caracteres.
* Una asignación de una variable lógica a cualquier otra variable de otro tipo, y al contrario.

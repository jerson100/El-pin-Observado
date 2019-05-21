# El-pin-Observado
Muy bien, detective, uno de nuestros colegas observó con éxito a nuestra persona objetivo, Robby, el ladrón. Lo seguimos a un almacén secreto, donde asumimos que encontramos todas las cosas robadas. La puerta de este almacén está asegurada por una cerradura electrónica de combinación. Desafortunadamente, nuestro espía no está seguro del PIN que vio cuando Robby lo ingresó.

El teclado tiene el siguiente diseño:

┌───┬───┬───┐

│ 1 │ 2 │ 3 │

├───┼───┼───┤

│ 4 │ 5 │ 6 │

├───┼───┼───┤

│ 7 │ 8 │ 9 │

└───┼───┼───┘

    │ 0 │
    
    └───┘
    
Apuntó el PIN 1357, pero también dijo que es posible que cada uno de los dígitos que vio pueda ser otro dígito adyacente (horizontal o verticalmente, pero no en diagonal). Por ejemplo, en lugar de la 1también podría ser el 2o 4. Y en lugar de la 5que también podría ser el 2, 4, 6o 8.

También mencionó, él conoce este tipo de cerraduras. Puede ingresar una cantidad ilimitada de PIN incorrectos, que finalmente nunca bloquean el sistema ni hacen sonar la alarma. Es por eso que podemos probar todas las variaciones posibles (*).

* posible en el sentido de: el PIN observado en sí mismo y todas las variaciones considerando los dígitos adyacentes

¿Puedes ayudarnos a encontrar todas esas variaciones? Sería bueno tener una función que devuelva una matriz (o una lista en Java y C #) de todas las variaciones para un PIN observado con una longitud de 1 a 8 dígitos. Podríamos nombrar la función getPINs( get_pinsen python, GetPINsen C #). Pero tenga en cuenta que todos los PIN, el observado y también los resultados, deben ser cadenas, debido a los '0' iniciales. Ya hemos preparado algunos casos de prueba para usted.

Detective, contamos con usted!

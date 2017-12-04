
# Planificar una base de datos

El primer paso para crear una base de datos es hacerse algunas preguntas y escribirlas, dejando espacio entre ellas para, posteriormente, escribir las respuestas. Al menos algunas de las respuestas deberían ser obvias tras haber pensado durante un tiempo.

Debe pasar por este proceso varias veces antes de que todo quede claro en su cabeza y en el papel. Utilizar un documento de texto para estas preguntas y respuestas facilita los cambios en las preguntas, añadir nuevas preguntas o cambiar las respuestas.

Aquí tiene algunas de las preguntas y respuestas desarrolladas antes de crear una base de datos para gastos del coche. Ya tenía una de lo que quería antes de empezar, pero a medida que comencé a hacer preguntas y responderlas, descubrí que necesitaba tablas y campos adicionales.

¿Para qué serán los campos? Mis gastos están divididos en tres áreas: adquisición de combustible, mantenimiento y vacaciones. Los gastos para los permisos de circulación y de conducir cada cuatro años no encajan en ninguna de esas áreas. Tendremos una tabla para ellos: gastos de permisos.

¿Qué campos encajan en el área de adquisición de combustible? Fecha de adquisición, lectura del cuentakilómetros, importe, cantidad de combustible y método de pago (el consumo puede calcularse con una consulta).

¿Qué campos encajan en el área de mantenimiento? Fecha del servicio, lectura del cuentakilómetros, tipo de servicio, coste del servicio y próxima fecha del servicio de este tipo (por ejemplo, para cambio de aceite indica cuándo debería ser el próximo cambio). Además, sería fantástico si pudiéramos escribir algunas notas, por eso añadimos a la lista un campo para notas.

¿Qué campos encajan en el área de vacaciones? Fecha, lectura del cuentakilómetros, combustible (incluye todos los campos de la tabla combustible), comidas (incluye comida y tapas), alojamiento, peajes y otros. Puesto que estos gastos se pagan con una o dos tarjetas de crédito o en efectivo, quiero un campo para registrar qué forma de pago se usó en cada uno de ellos.

¿Qué campos encajan en la categoría comidas? Desayuno, comida, cena y tapas parecen encajar. ¿Debo listar las tapas individualmente o anotar el coste total de tapas de todo el día? Elijo dividir tapas en dos campos: número de tapas y coste total. También necesito una forma de pago para cada uno: desayuno, comida, cena y tapas.

¿Qué campos son comunes a más de un área? La fecha aparece en todas las áreas y también lo hacen la lectura de cuentakilómetros y la forma de pago.

¿Cómo usaré la información de estos tres campos? Mientras esté de vacaciones querré tener cada día una lista completa de todos los gastos. Los campos de fecha sugieren una relación entre la tabla vacaciones y las fechas de cada una de estas tablas: combustible y alimentación. Esto quiere decir que los campos de fecha de estas tablas deben estar vinculados cuando creemos la base de datos.

El tipo de pago incluye dos tarjetas de crédito y efectivo. Entonces, crearemos una tabla con un campo para el tipo de pago y la usaremos en cajas de lista en los formularios.
<td width="15%" bgcolor="#83caff">**Sugerencia**</td><td width="85%" valign="top">Además de los campos que hemos listado para crear en las tablas de la base de datos, hay un campo más que podemos necesitar en cada tabla: el campo para la clave primaria. En algunas tablas ya se ha mencionado el campo para la clave primaria, pero en otras tablas, como en tipo de pago, necesitaremos crear un campo adicional para la clave primaria.</td>

Además de los campos que hemos listado para crear en las tablas de la base de datos, hay un campo más que podemos necesitar en cada tabla: el campo para la clave primaria. En algunas tablas ya se ha mencionado el campo para la clave primaria, pero en otras tablas, como en tipo de pago, necesitaremos crear un campo adicional para la clave primaria.


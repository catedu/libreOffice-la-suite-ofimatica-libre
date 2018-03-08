
# Introducir datos en un formulario

Los *registros* se usan para organizar los datos que introducimos en un formulario. También organizan los datos que introducimos en un subformulario.

Cada tipo de campo permite un método diferente de introducir datos. En muchos, si no en todos los casos, se puede usar más de un método. 

El primer paso para introducir datos en un formulario es abrirlo en la ventana principal de la base de datos.

1. Pulse el icono Formularios en la lista *Base de datos*.

1. Busque el nombre del formulario en la lista *Formularios* (Vacaciones)

1. Haga doble clic en el nombre del formulario.

La manera más rápida de introducir una fecha en el campo Fecha es pulsar la flecha que abre el calendario desplegable. A continuación, haga clic en el día deseado. Después pulse la tecla *Tabulador* para ir al campo Cuentakilómetros.
    ![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/fig42.png)

Los campos Cuentakilómetros, Peaje y Motel son campos numéricos. Introduzca los datos directamente en ellos o use las flechas *arriba *y *abajo*. Cuando haya introducido los valores, use la tecla *Tabulador* para ir al campo siguiente.

- Al pulsar *flecha arriba*, se incrementa el valor, y al hacerlo sobre *flecha abajo,* se disminuye el valor en una unidad.
</li>
<li>
Estas dos flechas solamente cambian los números que hay a la izquierda de la coma decimal.
</li>
<li>
Los números que hay a la derecha del decimal deben cambiarse, borrándolos primero y luego escribiendo el valor deseado.
</li>

El campo Pago de Motel es una lista desplegable. Si, como en mi caso, todos los elementos de la lista comienzan por letras diferentes, al escribir la primera letra se selecciona el valor deseado.

<li value="1">
Si dos o más elementos de la lista comienzan por la misma letra, escribiendo la letra repetidamente se moverá cíclicamente a través de los elementos que comienzan por esa letra.
</li>
<li>
Cuando la selección sea la correcta, utilice la tecla "Tabulador" para ir al campo Misc.
</li>

El resto de los campos del formulario principal son campos numéricos o listas desplegables, hasta que llegamos al campo Misc. Notas. Éste es un campo de texto. Escriba cualquier cosa que desee en este campo, como si fuera un simple editor de texto.

**Nota:** Puesto que la tecla *Tabulador* se usa para moverse entre campos, no se puede usar en un campo de texto. Todos los espacios deben hacerse con la *Barra espaciadora*. Por último, la tecla *Enter* sólo actúa como salto de línea para mover el cursor a la siguiente línea. A diferencia del movimiento entre campos que no son de texto, la tecla *Enter*, no funcionará igual desde un campo de texto. Use la tecla *Tabulador* en su lugar.Si no tuviéramos un subformulario para los datos de combustible, al pulsar la tecla *Tabulador* en el último campo, se guardarían todos los campos, se limpiarían y se pondría el formulario listo para introducir los datos en el segundo registro.</td>

Puesto que tenemos un subformulario, la tecla *Tabulador* coloca el cursor en el primer campo Fecha del subformulario, con la fecha rellenada automáticamente para que coincida con el campo Fecha del formulario principal.

Los campos CosteCombustible, CantidadCombustible y Cuentakilómetros son campos numéricos. El campo FormaPago es una lista desplegable. Introduzca los datos como hizo en el formulario principal y utilice la tecla *Tabulador* para ir al campo siguiente.

Cuando utilice la tecla *Tabulador* para dejar el campo FormaPago, el cursor irá al campo Fecha de la siguiente línea e introducirá automáticamente la fecha. Ahora puede introducir el segundo conjunto de datos de combustible para este día.

Para moverse a otro registro cuando un formulario tiene un subformulario, pulse en cualquier campo del formulario principal. En este caso, pulse en el campo Fecha del formulario principal. Ahora utilice las flechas de dirección de la parte inferior. Hay cuatro y de izquierda a derecha son: *Primer registro*, *Registro anterior*, *Registro siguiente *y *Último registro*. A la derecha de estas flechas está el icono *Nuevo registro*.

Para crear un registro nuevo mientras que está en otro registro del formulario principal, pulse el icono *Siguiente registro* o bien en el icono *Nuevo registro*.

<td width="15%" bgcolor="#83caff"> <b>Sugerencia: </b> </td><td width="85%" valign="top">El número que hay en el cuadro Registro es el número del registro cuyos datos se muestran en el formulario.Si sabe el número del registro que quiere, escríbalo en el cuadro registro y presione la tecla *Enter* para ir a ese registro.</td>


La siguiente imagen muestra un registro con datos insertados en sus campos.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/fig43.png)




# Usar el asistente para crear una consulta

Las consultas creadas por el asistente proporcionan listas de información basadas en lo que uno quiere conocer. Es posible obtener una o varias respuestas dependiendo de las circunstancias.

En la ventana principal de bases de datos, pulse el icono Consultas de la sección Bases de datos, y a continuación, en la sección tareas, haga clic en *Utilizar el asistente para crear consulta*. Se abre el Asistente para consultas. La información que queremos es qué álbumes son de un determinado grupo o individuo (el autor del álbum). Podemos incluir cuándo se compró cada álbum.
<td width="15%" bgcolor="#94bd5e">**Nota**</td><td width="85%" valign="top">Cuando se trabaja con una consulta, se puede usar más de una tabla. Puesto que tablas diferentes pueden contener los mismos nombres de campo, el formato para denominar los campos en una consulta es *Nombre de la tabla.nombre del campo*, con un punto (.) entre el nombre de la tabla y el nombre del campo. Por ejemplo, el campo Desayuno en la tabla Vacaciones utilizado en una consulta tendrá el nombre *Vacaciones.Desayuno*.</td>

Cuando se trabaja con una consulta, se puede usar más de una tabla. Puesto que tablas diferentes pueden contener los mismos nombres de campo, el formato para denominar los campos en una consulta es *Nombre de la tabla.nombre del campo*, con un punto (.) entre el nombre de la tabla y el nombre del campo. Por ejemplo, el campo Desayuno en la tabla Vacaciones utilizado en una consulta tendrá el nombre *Vacaciones.Desayuno*.

**Paso 1: seleccione los campos.**

<li>
Seleccione la tabla ColecciónCD en la lista del cuadro combinado de tablas.
</li>
<li>
Seleccione los campos de la tabla ColecciónCD en la lista *Campos disponibles*.
</li>

Seleccione los campos de la tabla ColecciónCD en la lista *Campos disponibles*.

<li value="1">
Pulse en *Interprete* y utilice el botón **&gt;** para moverlo a la lista *Campos de la consulta*
</li>
<li>
Mueva los campos *TítuloÁlbum* y *FechaDeCompra* de la misma manera.
</li>
<li>
Pulse **Siguiente**.
</li>

Mueva los campos *TítuloÁlbum* y *FechaDeCompra* de la misma manera.
<td width="15%" bgcolor="#83caff">**Sugerencia**</td><td width="85%" valign="top">Para mover el orden de los campos, seleccione el campo que quiera mover y pulse las fechas hacia arriba o hacia abajo.</td>

Para mover el orden de los campos, seleccione el campo que quiera mover y pulse las fechas hacia arriba o hacia abajo.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/Asistente_de_consultas_334.png)
**Paso 2: seleccionar el orden.**

Se pueden usar hasta cuatro campos para ordenar la información de una consulta. Aplicar en este punto una lógica muy simple es de gran ayuda. ¿Cuál es el campo más importante?

En nuestra consulta, el más importante es el intérprete. El título del álbum es menos importante y la fecha de compra no tiene ninguna importancia. Por supuesto, si estamos interesados en la música que compramos en un día determinado, la fecha será lo más importante.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/fig45.png)
<li value="1">
Haga clic en el primer cuadro combinado *Ordenar por*.
</li>

<li>
Pulse en *ColecciónCD.Intérprete* para seleccionarlo.
</li>
<li>
Para ordenar los intérpretes en orden alfabético (a-z), seleccione *Ascendente* en el lado derecho.
</li>

Para ordenar los intérpretes en orden alfabético (a-z), seleccione *Ascendente* en el lado derecho.

<li>
Haga clic en el segundo cuadro combinado *Ordenar por*.
</li>

<li>
Pulse en *ColecciónCD.TítuloÁlbum* y seleccione *Ascendente.*
</li>

<li>
Repita el proceso para *ColecciónCD.FechaDeCompra*.
</li>
<li>
Haga clic en **Siguiente**.
</li>

Haga clic en **Siguiente**.

**Paso 3: seleccione las condiciones de búsqueda.**

Las condiciones de búsqueda permiten comparar el nombre introducido con los nombres de los intérpretes de nuestra base de datos y decidir si se incluye o no a un intérprete particular en nuestra consulta.

<li value="1">
*es igual a:* lo mismo que
</li>
<li>
*no es igual a: *distinto
</li>
<li>
*es menor que:* está delante
</li>
<li>
*es mayor que:* está detrás
</li>
<li>
*es menor o igual que:* está delante o es lo mimo
</li>
<li>
*es mayor o igual que: *está detrás o es lo mimo
</li>
<li>
*como: *similar en algo
</li>

*no es igual a: *distinto

*es mayor que:* está detrás

*es mayor o igual que: *está detrás o es lo mimo
<td width="15%" bgcolor="#94bd5e">**Nota**</td><td width="85%" valign="top">Estas condiciones se aplican a números, letras (utilizando el orden alfabético) y fechas.</td>

Estas condiciones se aplican a números, letras (utilizando el orden alfabético) y fechas.

<li>
Puesto que estamos buscando solo una cosa, dejaremos las opciones predeterminadas de *Coincidencia con todos los siguientes*.
</li>
<li>
Estamos buscando un intérprete en particular, por lo que seleccionamos *ColecciónCD.Intérprete* en la lista de campos y *es igual a* en la condición.
</li>
<li>
Escriba el nombre del intérprete en el cuadro *Valor*. Haga clic en **Siguiente**.
</li>

Estamos buscando un intérprete en particular, por lo que seleccionamos *ColecciónCD.Intérprete* en la lista de campos y *es igual a* en la condición.

**Paso 4: seleccione el tipo de consulta.**

Queremos información simple, por lo que la selección por defecto *Consulta detallada* es lo que necesitamos. Pulse **Siguiente** en la parte inferior de la ventana.
<td width="15%" bgcolor="#94bd5e">**Nota**</td><td width="85%" valign="top">Puesto que tenemos una consulta simple, no necesitamos *Agrupación* y *Condiciones de agrupación*. Se omiten los pasos 5 y 6 del asistente en nuestra consulta.</td>

Puesto que tenemos una consulta simple, no necesitamos *Agrupación* y *Condiciones de agrupación*. Se omiten los pasos 5 y 6 del asistente en nuestra consulta.

**Paso 7: asigne un alias si lo desea.**

Queremos las opciones predeterminadas. Pulse **Siguiente**.

**Paso 8: resumen.**

Ponga un nombre a la consulta (sugerencia: *Consulta Intérpretes*). A la derecha tiene dos opciones. Seleccione *Mostrar consulta*. Pulse **Finalizar**.


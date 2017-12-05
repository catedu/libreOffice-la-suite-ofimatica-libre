
# Usar el asistente para crear una tabla

Los asistentes se han diseñado para hacer tareas básicas. A veces no son suficiente para lo que queremos; en cuyo caso podemos utilizar el asistente como punto de partida, y después trabajar sobre el contenido generado.

El asistente para tablas en Base sugiere tablas de dos categorías: negocios y personal. Cada categoría contiene ejemplos de tablas entre las que escoger. Cada tabla tiene una lista de campos disponibles. Podemos borrar algunos de estos campos y añadir otros.

Un campo de una tabla contiene una parte de la información. Por ejemplo, una tabla con una lista de precios podría tener un campo para el nombre del elemento, otro para la descripción y otro para el precio.

Como ninguno de los campos que necesitamos para nuestra base de datos Automóvil aparece en las tablas de ejemplo del asistente, crearemos una tabla simple, y ésta no tiene nada que ver con nuestra base de datos, usando el asistente. Esta sección es un ejercicio para explicar cómo funciona el asistente.

El asistente permite que los campos de una tabla provengan de más de una tabla de las sugeridas. Crearemos una tabla con campos de tres tablas diferentes de las mostradas por el asistente.
<td width="16%" bgcolor="#ffd320">**Precaución**</td><td width="84%" valign="top">Cada tabla necesita un campo *Primary key* (*Clave primaria*, cuyo uso se explicará más adelante). Usaremos ese campo para numerar nuestras entradas y queremos que ese número se incremente automáticamente a medida que añadimos datos.Según la zona geográfica, se usa “clave” o “llave” primaria. Se intentará usar “clave”, salvo que se esté describiendo una opción de la interfaz.</td>



Según la zona geográfica, se usa “clave” o “llave” primaria. Se intentará usar “clave”, salvo que se esté describiendo una opción de la interfaz.

Pulse *Usar el asistente para crear tabla*. Se abre el asistente para tablas.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/SeleccionarCampos.png)
Usaremos la tabla de ejemplo *ColecciónCD* en la categoría Personal para seleccionar los campos que necesitamos.

<li value="1">
*Categoría*: seleccione *Personal*. La lista desplegable *Tablas de muestra* cambia a una lista de tablas de ejemplo personal.
</li>
<li>
*Tablas de ejemplo*: seleccione *ColecciónCD*. El cuadro *Campos disponibles* cambia a una lista de campos de esta tabla.
</li>
<li>
*Campos seleccionados:* mueva los siguientes campos desde la ventana Campos disponibles a la ventana Campos seleccionados usando el botón &gt; y en este orden: *IDColección, TítuloÁlbum, Intérprete, FechaDeCompra, Formato, Notas y NúmDePistas.*
</li>
<li>
*Seleccionar campos de otra tabla de ejemplo*. Pulse Negocios como categoría. Seleccione *Empleados* en la lista de tablas de ejemplo. Utilice el botón **&gt;** para mover el campo *Foto* desde la ventana *Campos disponibles* a la ventana *Campos seleccionados*. Se colocará en la parte inferior de la lista, debajo del campo *NúmDePistas*.
</li>
<li>
Si se equivoca al seleccionar campos, pulse el nombre del campo en la lista *Campos seleccionados* y con el botón **&lt;** muévalos desde *Campos seleccionados* de nuevo a la lista *Campos disponibles*.
</li>
<li>
Si se equivoca en el orden de los campos seleccionados pulse el nombre del campo cuyo orden es erróneo y use las flechas de dirección **Arriba** y **Abajo** situadas a la derecha de *Campos seleccionados* para mover el campo a su posición correcta.
</li>
<li>
Pulse **Siguiente**.
</li>

*Tablas de ejemplo*: seleccione *ColecciónCD*. El cuadro *Campos disponibles* cambia a una lista de campos de esta tabla.

*Seleccionar campos de otra tabla de ejemplo*. Pulse Negocios como categoría. Seleccione *Empleados* en la lista de tablas de ejemplo. Utilice el botón **&gt;** para mover el campo *Foto* desde la ventana *Campos disponibles* a la ventana *Campos seleccionados*. Se colocará en la parte inferior de la lista, debajo del campo *NúmDePistas*.

Si se equivoca en el orden de los campos seleccionados pulse el nombre del campo cuyo orden es erróneo y use las flechas de dirección **Arriba** y **Abajo** situadas a la derecha de *Campos seleccionados* para mover el campo a su posición correcta.



**Paso 2: establecer los tipos de campo y formatos.**

En este paso establecerá las propiedades de los campos. Cuando pulse en un campo, la información a la derecha cambia. Entonces, se pueden hacer cambios para ajustarlos a sus necesidades. Pulse en cada campo, de uno en uno, y haga los cambios que se indican abajo.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/TiposdeCampoyFormato.png)<td width="14%" bgcolor="#94bd5e">**Nota**</td><td width="86%" valign="top">Si alguno de estos campos requiere un valor, ajuste *Entrada requerida* a **Sí**. Entonces no se permitirá una entrada con ese campo en blanco. En general solamente se usa *Entrada requerida *a **Sí** si siempre se tiene que poner algo en ese campo. Por defecto *Entrada requerida * está ajustado a **No**.</td>

Si alguno de estos campos requiere un valor, ajuste *Entrada requerida* a **Sí**. Entonces no se permitirá una entrada con ese campo en blanco. En general solamente se usa *Entrada requerida *a **Sí** si siempre se tiene que poner algo en ese campo. Por defecto *Entrada requerida * está ajustado a **No**.

<li>
*IDColección*: cambie *Valor automático *de **No** a **Sí**.
</li>
<li>
*TítuloÁlbum*:
</li>

*TítuloÁlbum*:

<li style="list-style-type: none;">
<ul>
<li>
*Entrada requerida*: deje *Entrada requerida* en *No* a menos que toda su música esté en álbumes.
</li>
<li>
*Longitud*: no cambie la longitud a menos que tenga un título de álbum mayor de 100 caracteres, incluyendo los espacios.
</li>

*Longitud*: no cambie la longitud a menos que tenga un título de álbum mayor de 100 caracteres, incluyendo los espacios.
<td width="15%" bgcolor="#94bd5e">**Nota**</td><td width="85%" valign="top">En Base se debe especificar la longitud máxima para cada campo en el momento de la creación. No es fácil cambiarla después, por eso, en caso de duda, especifique una longitud mayor. Base usa VARCHAR como formato para campos de texto. Este formato utiliza solamente el número real de caracteres en un campo hasta el límite marcado. Es decir, un campo que contiene 20 caracteres usará solamente espacio para 20 caracteres aunque el límite este puesto en 100.</td>

En Base se debe especificar la longitud máxima para cada campo en el momento de la creación. No es fácil cambiarla después, por eso, en caso de duda, especifique una longitud mayor. Base usa VARCHAR como formato para campos de texto. Este formato utiliza solamente el número real de caracteres en un campo hasta el límite marcado. Es decir, un campo que contiene 20 caracteres usará solamente espacio para 20 caracteres aunque el límite este puesto en 100.

<li value="1">
*Intérprete*: use las opciones predeterminadas. Dado que la música siempre tiene intérpretes, establezca *Entrada requerida* en *Sí*.
</li>
<li>
*FechaDeCompra*: t*ipo de campo:* opciones predeterminadas para fechas. *Entrada requerida* debería ser *No* (puede que no sepa la fecha).
</li>
<li>
*Formato*: sólo cambie la opción de *Entrada requerida*: de *No* a *Sí*.
</li>
<li>
*Notas*: no se requieren cambios.
</li>
<li>
*NúmDePistas: c*ambie *Tipo de campo* a *Tiny Integer [TINYINT]*. El número de pistas permitido será de 999. *Small Integer [SMALLINT]* podría admitir 99999 pistas si necesita más de 999.
</li>
<li>
*Foto*: use las opciones predeterminadas.
</li>

*FechaDeCompra*: t*ipo de campo:* opciones predeterminadas para fechas. *Entrada requerida* debería ser *No* (puede que no sepa la fecha).

*Notas*: no se requieren cambios.

*Foto*: use las opciones predeterminadas.

Cuando haya terminado pulse **Siguiente**.
<td width="15%" bgcolor="#94bd5e">**Nota**</td><td width="85%" valign="top">Cada campo tiene un *Tipo de campo*, y éste debe especificarse. Los tipos incluyen texto, integer, fecha y decimal. Si el campo va a contener información general (por ejemplo, un nombre o una descripción), use texto. Si el campo va a contener siempre un número (por ejemplo, un precio), el tipo debería ser decimal u otro tipo de campo numérico. El asistente elige el tipo de campo correcto, por lo que para hacerse una idea de cómo funciona esto, vea lo que el asistente ha seleccionado para cada campo.</td>

Cada campo tiene un *Tipo de campo*, y éste debe especificarse. Los tipos incluyen texto, integer, fecha y decimal. Si el campo va a contener información general (por ejemplo, un nombre o una descripción), use texto. Si el campo va a contener siempre un número (por ejemplo, un precio), el tipo debería ser decimal u otro tipo de campo numérico. El asistente elige el tipo de campo correcto, por lo que para hacerse una idea de cómo funciona esto, vea lo que el asistente ha seleccionado para cada campo.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/Asistente_de_tablas_323.png)
<li>
Marque *Crear una clave principal*.
</li>
<li>
Seleccione *Usar un campo existente como clave principal*.
</li>
<li>
En la lista desplegable *Nombre del **campo* seleccione *IDColección*.
</li>
<li>
Marque *Autovalor* si no está marcado.* *
</li>
<li>
Pulse **Siguiente**.
</li>

Seleccione *Usar un campo existente como clave principal*.

Marque *Autovalor* si no está marcado.* *
<td width="15%" bgcolor="#94bd5e">**Nota**</td><td width="85%" valign="top">Una clave primaria identifica un ítem (o registro) de forma única en la tabla. Por ejemplo, puede tener dos personas llamadas “Antonio López” o tres personas que viven en la misma dirección y la base de datos necesita distinguir entre ellas.El método más sencillo es asignar un número único a cada uno: asignamos a la primera persona el número 1, a la segunda 2, etc. Cada entrada tiene un número y cada número es diferente, y por eso es fácil decir “registro con ID 172”. Esta es la opción elegida aquí: *IDColección* es simplemente un número asignado automáticamente por Base a cada registro de esta tabla.</td>

Una clave primaria identifica un ítem (o registro) de forma única en la tabla. Por ejemplo, puede tener dos personas llamadas “Antonio López” o tres personas que viven en la misma dirección y la base de datos necesita distinguir entre ellas.

**Paso 4: crear la tabla.**

<li value="1">
Si lo desea, cambie el nombre a la tabla en este punto. Si lo hace, asigne un nombre significativo para usted. En este ejemplo no haremos cambios.
</li>
<li>
Deje marcada la opción *Insertar datos inmediatamente*.
</li>
<li>
Pulse **Finalizar** para completar el asistente para tablas. Cierre la ventana creada por el asistente. Ahora está de nuevo en la ventana principal de la base de datos con la lista de tablas, consultas, formularios e informes. Observe que ahora hay una tabla con el nombre “ColecciónCD” en la ventana Tablas.
</li>

Deje marcada la opción *Insertar datos inmediatamente*.



# Usar el asistente para crear una tabla

Los asistentes se han diseñado para hacer tareas básicas. A veces no son suficiente para lo que queremos; en cuyo caso podemos utilizar el asistente como punto de partida, y después trabajar sobre el contenido generado.

El asistente para tablas en Base sugiere tablas de dos categorías: negocios y personal. Cada categoría contiene ejemplos de tablas entre las que escoger. Cada tabla tiene una lista de campos disponibles. Podemos borrar algunos de estos campos y añadir otros.

Un campo de una tabla contiene una parte de la información. Por ejemplo, una tabla con una lista de precios podría tener un campo para el nombre del elemento, otro para la descripción y otro para el precio.

Como ninguno de los campos que necesitamos para nuestra base de datos Automóvil aparece en las tablas de ejemplo del asistente, crearemos una tabla simple, y ésta no tiene nada que ver con nuestra base de datos, usando el asistente. Esta sección es un ejercicio para explicar cómo funciona el asistente.

El asistente permite que los campos de una tabla provengan de más de una tabla de las sugeridas. Crearemos una tabla con campos de tres tablas diferentes de las mostradas por el asistente.

**Precaución**: Cada tabla necesita un campo *Primary key* (*Clave primaria*, cuyo uso se explicará más adelante). Usaremos ese campo para numerar nuestras entradas y queremos que ese número se incremente automáticamente a medida que añadimos datos.Según la zona geográfica, se usa “clave” o “llave” primaria. Se intentará usar “clave”, salvo que se esté describiendo una opción de la interfaz.

Pulse *Usar el asistente para crear tabla*. Se abre el asistente para tablas.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/SeleccionarCampos.png)

Paso 1: seleccionar campos.

Usaremos la tabla de ejemplo *ColecciónCD* en la categoría Personal para seleccionar los campos que necesitamos.

1. *Categoría*: seleccione *Personal*. La lista desplegable *Tablas de muestra* cambia a una lista de tablas de ejemplo personal.

2. *Tablas de ejemplo*: seleccione *ColecciónCD*. El cuadro *Campos disponibles* cambia a una lista de campos de esta tabla.

3. *Campos seleccionados:* mueva los siguientes campos desde la ventana Campos disponibles a la ventana Campos seleccionados usando el botón &gt; y en este orden: *IDColección, TítuloÁlbum, Intérprete, FechaDeCompra, Formato, Notas y NúmDePistas.*

4. *Seleccionar campos de otra tabla de ejemplo*. Pulse Negocios como categoría. Seleccione *Empleados* en la lista de tablas de ejemplo. Utilice el botón **&gt;** para mover el campo *Foto* desde la ventana *Campos disponibles* a la ventana *Campos seleccionados*. Se colocará en la parte inferior de la lista, debajo del campo *NúmDePistas*.

5. Si se equivoca al seleccionar campos, pulse el nombre del campo en la lista *Campos seleccionados* y con el botón **&lt;** muévalos desde *Campos seleccionados* de nuevo a la lista *Campos disponibles*.

6. Si se equivoca en el orden de los campos seleccionados pulse el nombre del campo cuyo orden es erróneo y use las flechas de dirección **Arriba** y **Abajo** situadas a la derecha de *Campos seleccionados* para mover el campo a su posición correcta.

7. Pulse **Siguiente**.

**Paso 2: establecer los tipos de campo y formatos.**

En este paso establecerá las propiedades de los campos. Cuando pulse en un campo, la información a la derecha cambia. Entonces, se pueden hacer cambios para ajustarlos a sus necesidades. Pulse en cada campo, de uno en uno, y haga los cambios que se indican abajo.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/TiposdeCampoyFormato.png)

**Nota**: Si alguno de estos campos requiere un valor, ajuste *Entrada requerida* a **Sí**. Entonces no se permitirá una entrada con ese campo en blanco. En general solamente se usa *Entrada requerida* a **Sí** si siempre se tiene que poner algo en ese campo. Por defecto *Entrada requerida* está ajustado a **No**.


- *IDColección*: cambie *Valor automático* de **No** a **Sí**.

- *TítuloÁlbum*:

    - *Entrada requerida*: deje *Entrada requerida* en *No* a menos que toda su música esté en álbumes.

    - *Longitud*: no cambie la longitud a menos que tenga un título de álbum mayor de 100 caracteres, incluyendo los espacios.

**Nota:** En Base se debe especificar la longitud máxima para cada campo en el momento de la creación. No es fácil cambiarla después, por eso, en caso de duda, especifique una longitud mayor. Base usa VARCHAR como formato para campos de texto. Este formato utiliza solamente el número real de caracteres en un campo hasta el límite marcado. Es decir, un campo que contiene 20 caracteres usará solamente espacio para 20 caracteres aunque el límite este puesto en 100.

- *Intérprete*: use las opciones predeterminadas. Dado que la música siempre tiene intérpretes, establezca *Entrada requerida* en *Sí*.
- *FechaDeCompra*: t*ipo de campo:* opciones predeterminadas para fechas. *Entrada requerida* debería ser *No* (puede que no sepa la fecha).
- *Formato*: sólo cambie la opción de *Entrada requerida*: de *No* a *Sí*.
- *Notas*: no se requieren cambios.
- *NúmDePistas: c*ambie *Tipo de campo* a *Tiny Integer [TINYINT]*. El número de pistas permitido será de 999. *Small Integer [SMALLINT]* podría admitir 99999 pistas si necesita más de 999.
- *Foto*: use las opciones predeterminadas.

Cuando haya terminado pulse **Siguiente**.

**Nota:** Cada campo tiene un *Tipo de campo*, y éste debe especificarse. Los tipos incluyen texto, integer, fecha y decimal. Si el campo va a contener información general (por ejemplo, un nombre o una descripción), use texto. Si el campo va a contener siempre un número (por ejemplo, un precio), el tipo debería ser decimal u otro tipo de campo numérico. El asistente elige el tipo de campo correcto, por lo que para hacerse una idea de cómo funciona esto, vea lo que el asistente ha seleccionado para cada campo.

**Paso 3: seleccionar la clave primaria.**

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/Asistente_de_tablas_323.png)

1. Marque Crear una clave principal.

2. Seleccione Usar un campo existente como clave principal.

3. En la lista desplegable Nombre del campo seleccione IDColección.

4. Marque Autovalor si no está marcado.

5. Pulse **Siguiente**.

**Nota**. Una clave primaria identifica un ítem (o registro) de forma única en la tabla. Por ejemplo, puede tener dos personas llamadas “Antonio López” o tres personas que viven en la misma dirección y la base de datos necesita distinguir entre ellas. 

El método más sencillo es asignar un número único a cada uno: asignamos a la primera persona el número 1, a la segunda 2, etc. Cada entrada tiene un número y cada número es diferente, y por eso es fácil decir “registro con ID 172”. Esta es la opción elegida aquí: *IDColección* es simplemente un número asignado automáticamente por Base a cada registro de esta tabla.

**Paso 4: crear la tabla.**

1. Si lo desea, cambie el nombre a la tabla en este punto. Si lo hace, asigne un nombre significativo para usted. En este ejemplo no haremos cambios.
2. Deje marcada la opción *Insertar datos inmediatamente*.
3. Pulse **Finalizar** para completar el asistente para tablas. Cierre la ventana creada por el asistente. Ahora está de nuevo en la ventana principal de la base de datos con la lista de tablas, consultas, formularios e informes. Observe que ahora hay una tabla con el nombre “ColecciónCD” en la ventana Tablas.


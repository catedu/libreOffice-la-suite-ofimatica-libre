
# Acelerar la entrada de datos

Introducir datos en una hoja de cálculo puede ser una labor muy intensa, pero Calc proporciona varias herramientas para eliminar complicaciones a la hora de introducir datos.

La habilidad más básica es arrastrar y soltar el contenido de una celda en otra con el ratón. Para esto, Calc incluye varias herramientas para automatizar la entrada de datos, especialmente de material repetitivo. Estas incluyen la Herramienta para rellenar, listas de selección y la posibilidad de compartir datos en varias hojas del mismo documento.

## Usar la herramienta para rellenar en celdas

Para simplificar, definiremos la herramienta para rellenar como una forma de duplicar contenido existente. Comience por seleccionar la celda a copiar, luego arrastre el ratón en cualquier dirección (o mantenga pulsada la tecla mayúsculas y pulse en la última celda que desee rellenar), y elija **Editar → Rellenar** y la dirección en la que quiere copiar: arriba, abajo, izquierda o derecha.

Las opciones que no están habilitadas se encuentran en gris, pero aún puede seleccionar la dirección opuesta a la que pretendía, lo que puede hacer que las celdas sean sobrescritas accidentalmente.



**Una forma rápida de rellenar celdas** es **arrastrar el cuadro negro pequeño de la esquina inferior derecha** de la celda que quiere copiar en la dirección en la que se desea rellenar. Si la celda contiene un número, éste rellenará una serie. Si es texto, el mismo texto se repetirá en la dirección elegida.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/arrastrar.jpg)


## Rellenar una serie

Una forma más compleja de usar la herramienta de relleno es rellenar una serie. Las listas predeterminadas contienen los nombres completos y abreviados para los días de la semana y los meses del año, pero también se pueden crear listas propias.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/SerieRellena.jpg)

Para añadir una serie rellena a una hoja de cálculo, seleccione las celdas a rellenar, elija **Editar → Rellenar → Series**. En el diálogo Rellenar series, seleccione **Relleno automático** como el *tipo de serie*, e introduzca como *valor inicial* un elemento para cualquier serie definida. Las celdas seleccionadas se rellenan con los otros elementos de la lista de manera secuencial, repitiendo desde el inicio de la lista cuando se llega al final de la lista.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/RellenadodeCeldas.png)

También puede usar **Editar → Rellenar → Series** para crear una serie numérica usando un valor inicial y un incremento. Por ejemplo, si introduce como valor inicial 1 y como final 7, con un incremento de 2, se crea la secuencia 1, 3, 5, 7.

En cualquier caso, la herramienta de relleno crea sólo una conexión temporal entre las celdas. Una vez que se rellenan, las celdas quedan sin conexión entre sí.

## Definir series de relleno

Para definir una serie de relleno, vaya a **Herramientas → Opciones → LibreOffice Calc → Listas de ordenamiento**. Este diálogo muestra las series predefinidas en el campo *Listas* de la izquierda, y el contenido de la lista seleccionada en el campo *Entradas*.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/Ordenamiento.png)

Pulse **Nuevo**. El campo *Entradas se* limpia. Escriba la serie de la nueva lista en el cuadro *Entradas* (una entrada por línea), y pulse **Añadir**.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/Entradas.png)

## Usar listas de selección

Las listas de selección están habilitadas sólo para texto, y están limitadas al texto introducido previamente en la misma columna.



Para usar una lista de selección, clique con el botón derecho del ratón en una celda y vuelva a clicar en **Lista de selección**. Aparecerá una lista desplegable con los datos de cada celda en la misma columna que posean al menos un carácter o cuyo formato esté definido como texto. Elija la entrada que necesite.


![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/Seleccion_302.png) ![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/Seleccion_303.png)


## Compartir contenido entre hojas

Puede desear introducir la misma información en la misma celda de múltiples hojas, por ejemplo tener listas comunes para un grupo de personas u organizaciones. En vez de repetir la lista en cada hoja, puede introducir los datos en todas las hojas que desee a la vez. Para hacer esto, seleccione todas las hojas en las que quiere que aparezca la información, luego introduzca la información en la hoja activa.

**¡¡Atención!!** Esta técnica sobrescribe cualquier información que esté en las celdas de las demás hojas sin avisar. Por esta razón, asegúrese al terminar de quitar de la selección todas las pestañas de hojas (pulse *Ctrl* y luego la pestaña) excepto de la que desee editar.

## Validar el contenido de las celdas

Al crear hojas de cálculo para que las usen otras personas, puede desear asegurarse de que los datos introducidos sean válidos o apropiados para la celda. También puede usar la validación en su propio trabajo como guía para introducir datos que son complejos o que no son habituales.

Las series de relleno y las listas de selección pueden manejar algunos tipos de datos, pero están limitados a información predefinida. Para un caso más general, puede seleccionar una celda y usar **Datos → Validez** para definir el tipo de contenido que se puede introducir en esa celda. Por ejemplo, una celda puede requerir una fecha o un número entero, sin letras ni decimales, o no estar en blanco.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/Validez_305.png)


Dependiendo de la validez establecida, la herramienta también puede definir el rango de contenido que se puede introducir, y proporcionar mensajes que explique las reglas de contenido especificadas para la celda y qué tienen que hacer los usuarios cuando introduzcan un dato incorrecto. También pueden hacer que la celda rechace el contenido incorrecto, aceptarlo con un aviso, o ejecutar una macro cuando se introduzca un error.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/Seleccion_304.png)

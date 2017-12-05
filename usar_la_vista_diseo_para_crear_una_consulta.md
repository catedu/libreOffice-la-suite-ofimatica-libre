
# Usar la vista diseño para crear una consulta

Crear una consulta usando la Vista diseño no es tan difícil como puede parecer en un primer momento. Se hace en varios pasos, pero cada paso es bastante simple.

¿Cuál es el consumo de combustible de nuestro vehículo? Esta pregunta requiere crear dos consultas, usando la primera consulta como parte de la segunda consulta.

### Paso 1: abra la primera consulta en Vista diseño.

Haga clic en **Crear consulta en vista Diseño.**

### Paso 2: añada las tablas.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/fig46.png)
<li value="1">
Pulse en *Combustible* para resaltarlo.
</li>
<li>
Haga clic en **Añadir** y, a continuación, **Cerrar**. 
</li>

Haga clic en **Añadir** y, a continuación, **Cerrar**. 
<td width="15%" bgcolor="#83caff">**Sugerencia**</td><td width="85%" valign="top">Mueva el cursor sobre la parte inferior de la tabla Combustible y arrástrelo para hacerlo más grande y para que sea más fácil ver todos los campos de la tabla.</td>

Mueva el cursor sobre la parte inferior de la tabla Combustible y arrástrelo para hacerlo más grande y para que sea más fácil ver todos los campos de la tabla.

### Paso 3: añada campos a la tabla en la parte inferior.

<li value="1">
Haga doble clic en el campo *IdCombustible* en la tabla Combustible.
</li>
<li>
Haga doble clic en el campo *Cuentakilómetros*.
</li>
<li>
Haga doble clic en el campo *CantidadCombustible*.
</li>

Haga doble clic en el campo *Cuentakilómetros*.

La tabla en la parte inferior de la ventana de consulta debería mostrar tres columnas.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/fig48.png)
### Paso 4: establezca los criterios de la consulta.

Queremos que IDCombustible en la consulta empiece por el número 1

<li value="1">
Escriba *&gt;0* en la celda Criterio de la tabla de la consulta.
</li>
<li>
![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/Seleccion_336.png)</li>

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/Seleccion_336.png)
La siguiente imagen muestra la tabla Combustible con mis entradas y el resultado de la consulta basada en la tabla Combustible. La consulta resultante está en la tabla de la derecha.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/Seleccion_335.png)
### Paso 5: guarde y cierre la consulta.

Ya que esta consulta contiene las lecturas finales del cuentakilómetros para nuestros cálculos, llámela Lecturas-finales cuando la guarde. Luego cierre la consulta.

### Paso 6: cree la consulta para calcular el consumo.

<li value="1">
Pulse **Crear consulta en vista diseño** para abrir una consulta nueva.
</li>
<li>
Añada la tabla Combustible a la consulta como hizo en el paso 2: añada las tablas, pero **no** cierre la ventana Añadir tablas.
</li>
<li>
Añada la consulta Lecturas-finales a esta consulta.
</li>

Añada la tabla Combustible a la consulta como hizo en el paso 2: añada las tablas, pero **no** cierre la ventana Añadir tablas.

<li>
Pulse *Consultas* para obtener la lista de consultas de la base de datos.
</li>

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/fig52.png)<ol type="a" start="2">
<li>
Pulse en Lecturas-finales.
</li>
<li>
Haga clic en **Añadir** y , a continuación, en **Cerrar**.
</li>

Haga clic en **Añadir** y , a continuación, en **Cerrar**.

### **Paso 7: añadir campos a la tabla en la parte baja de la consulta.**

Vamos a calcular el consumo de combustible. Para ello necesitamos la CantidadCombustible y la distancia recorrida. Puesto que la CantidadCombustible que queremos usar es a la lectura final del cuentakilómetros, usaremos la consulta Lecturas-finales para obtenerla. Usaremos también el campo Cuentakilómetros de la tabla Combustible y de la consulta Lecturas-finales.

<li>
Haga doble clic en *CantidadCombustible* en la consulta Lecturas-finales.
</li>
<li>
Haga doble clic en *Cuentakilómetros* en la consulta Lecturas-finales
</li>
<li>
Haga doble clic en *Cuentakilómetros* en la tabla Combustible.
</li>

Haga doble clic en *Cuentakilómetros* en la consulta Lecturas-finales

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/fig53.png)
### **P**aso 8: introducir el campo de diferencia IDCombustible.

Queremos que la diferencia entre el valor IDCombustible de la tabla Combustible y el valor IDCombustible de la consulta Lecturas-finales sea igual a uno (“1”).

<li value="1">
Escriba "Lecturas-finales"."IdCombustible"- "Combustible"."IdCombustible" en el campo que hay a la derecha del campo Cuentakilómetros de la tabla Combustible. Escriba el número 1 (uno) en la celda Criterio de esta columna.
</li>

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/fig54.png)
<li>
Calcular la distancia viajada:
</li>

<li>
Escriba "Lecturas-finales"."Cuentakilómetros" – "Combustible"."Cuentakilómetros" en la celda Campo
</li>
<li>
Escriba &gt;0 en la celda Criterio
</li>

Escriba &gt;0 en la celda Criterio

<li>
Calcule el consumo:
</li>

Escriba ("Lecturas-finales"."Cuentakilómetros" - "Combustible"."Cuentakilómetros") / "Lecturas-finales"."CantidadCombustible" en la siguiente columna a la derecha de la palabra Campo.
<td width="15%" bgcolor="#94bd5e">**Nota**</td><td width="85%" valign="top">Cuando introduzca campos para estos cálculos, debe seguir el siguiente formato: nombre de la tabla o consulta seguido por un punto y seguido por un nombre de campo. Para nombres con guiones, espacios, acentos y ñ (tablas o consultas), use el nombre de la tabla o consulta entre comillas dobles. La consulta añadirá el resto de las comillas.Utilice símbolos aritméticos entre los dos. Se puede hacer más de un cálculo utilizando paréntesis para agrupar las operaciones aritméticas.</td>

Cuando introduzca campos para estos cálculos, debe seguir el siguiente formato: nombre de la tabla o consulta seguido por un punto y seguido por un nombre de campo. Para nombres con guiones, espacios, acentos y ñ (tablas o consultas), use el nombre de la tabla o consulta entre comillas dobles. La consulta añadirá el resto de las comillas.

### Paso 9: ejecutar la consulta y realizar alguna modificación.

Después de ejecutar la consulta para asegurarnos de que funciona correctamente, se pueden ocultar todas las columnas que no se necesiten.

<li value="1">
Pulse el icono Ejecutar consulta en la barra de herramientas Diseño de consulta. Los resultados se muestran en la siguiente imagen.
</li>

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/fig57.png)
Fíjese que la etiqueta de la última columna no está totalmente porque algunas de las etiquetas son largas. Podemos arreglar este problema usando un alias para algunos campos. Las etiquetas se sustituyen por sus alias.

<li>
Añadir alias:
</li>

Rellene los alias como se muestra en la siguiente imagen.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/fig58.png)
<li>
Ejecute la consulta nuevamente.
</li>

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/fig59.png)
No se necesita la columna que muestra la diferencia entre los campos IDCombustible de la tabla y la consulta, por eso la ocultamos. Aunque no esté visible se seguirá usando en los cálculos.

<li>
Ocultar un campo que no es necesario que se vea. Elimine la marca en la casilla de la celda Visible y vuelva a ejecutar la consulta.
</li>

### Paso 10: cierre, guarde y nombre la consulta.

Sugiero el nombre Consumo combustible.

Obviamente se pueden hacer otros cálculos en esta consulta, como por ejemplo, el gasto por distancia viajada y cuántos gastos corresponden a cada tipo de pago.
<td width="15%" bgcolor="#94bd5e">**Nota**</td><td width="85%" valign="top">El uso completo de las consultas requiere un conocimiento de un conjunto de operaciones (*complementos, uniones, intersecciones, y, o,* y cualquier combinación de éstos). Para esto, es muy útil que tenga una copia de *Hsqldb User Guide*, en [http://hsqldb.org/](http://hsqldb.org/).</td>

El uso completo de las consultas requiere un conocimiento de un conjunto de operaciones (*complementos, uniones, intersecciones, y, o,* y cualquier combinación de éstos). Para esto, es muy útil que tenga una copia de *Hsqldb User Guide*, en [http://hsqldb.org/](http://hsqldb.org/).


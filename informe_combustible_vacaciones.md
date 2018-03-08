
# Informe Combustible vacaciones


1. Cree una consulta que contenga sólo el combustible comprado en los días de vacaciones.

    - Abra una consulta en vista diseño.
</li>
<li>
Siga los pasos para añadir tablas en “añada las tablas“ en la página 41 para añadir la tabla Combustible.
</li>
<li>
En la tabla Combustible, haga doble clic en *Fecha* y *CosteCombustible* para añadirlos en la tabla que hay debajo de la consulta.
</li>
<li>
En la celda Criterio del campo Fecha, escriba lo siguiente: ENTRE #25/05/2007# Y #26/05/2007#
</li>

    ![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/fig64.png)

1. Guarde la consulta indicando un nombre y ciérrela (sugerencia: *Gastos combustible vacaciones*).
**Sugerencia:**
Cuando use fechas en una consulta, introdúzcalas en forma numérica MM/DD/AAAA o DD/MM/AAAA dependiendo de la configuración por defecto para las fechas de su idioma (mi configuración por defecto es DD/MM/AAAA).
Cada fecha debe tener una # delante y otra detrás. Por lo tanto 25 de mayo de 2007 se escribe #25/05/2007# o #05/25/2007# dependiendo de la configuración para fechas de su idioma.

3. Abra un informe nuevo:

    - Haga clic con el botón secundario sobre la consulta *Gastos combustible vacaciones*.
</li>
<li>
Seleccione Asistente para informes en el menú contextual.
</li>
<td width="15%" bgcolor="#94bd5e"><b>Nota: </b></td><td width="85%" valign="top">Cuando se abre un informe de este modo, la consulta utilizada para abrirlo se selecciona automáticamente en la lista del cuadro combinado Tabla o consulta del Asistente para informes.</td>

1. Cree el informe.
Utilice **&gt;&gt;** para mover ambos campos de la lista *Campos disponibles* a la lista *Campos del informe*. Haga clic en <b>Siguiente</b>.
</li>
<li>
Ponga etiquetas a los campos.
Añada un espacio a CosteCombustible para hacerlo Coste Combustible (dos palabras). Pulse <b>Siguiente</b>.
</li>
<li>
Agrupe campos.
Pulse en Fecha para resaltarlo. Utilice **&gt;** para mover el campo Fecha a la lista Agrupaciones. Pulse <b>Siguiente</b>.
</li>
<li>
Selección del diseño.
No haremos cambios en el diseño. Haga clic en <b>Siguiente</b>.
</li>
<li>
Cree el informe (ajustes finales).
</li>


<li>
Utilice el nombre sugerido, que es el mismo que el de la consulta.
</li>
<li>
Seleccione Informe estático. Haga clic en Finalizar.
</li>



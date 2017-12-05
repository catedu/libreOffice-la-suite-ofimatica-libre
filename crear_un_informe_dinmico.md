
# Crear un informe dinámico

Ahora crearemos un informe con algunas estadísticas de consumo de combustible. Para hacer esto tenemos que modificar dos consultas: Lecturas-finales y Consumo combustible. Añadiremos el campo CosteCombustible a la consulta Lecturas-finales. Posteriormente añadiremos el campo CosteCombustible desde la consulta Lecturas‑finales a la consulta Consumo combustible.
<td width="16%" bgcolor="#83caff">**Sugerencia**</td><td width="84%" valign="top">Si abre una consulta para editarla, podría aparecer como en la Figura 65. Si mueve el cursor sobre la línea negra (rodeada en rojo), se convierte en una doble flecha. Arrástrela a una posición inferior.</td>

Si abre una consulta para editarla, podría aparecer como en la Figura 65. Si mueve el cursor sobre la línea negra (rodeada en rojo), se convierte en una doble flecha. Arrástrela a una posición inferior.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/ConsultaEdicion.png)
<li>
Añada el campo *CosteCombustible* a la consulta Lecturas-finales:
</li>

<li style="list-style-type: none;">
<ul>
<li value="1">
Haga clic con el botón secundario sobre la consulta *Lecturas‑finales* y seleccione **Editar** en el menú contextual.
</li>
<li>
En la lista de la tabla Combustible, haga doble clic para añadir CosteCombustible a la tabla de la parte inferior.
</li>
<li>
Guarde y cierre la consulta.
</li>
</ul>
</li>

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/fig66.png)
<li>
Añada el campo *CosteCombustible* desde la consulta Lecturas‑finales a la consulta Consumo combustible:
</li>

<li style="list-style-type: none;">
<ul>
<li>
Haga clic con el botón secundario sobre la consulta *Consumo combustible* y seleccione **Editar** en el menú contextual.
</li>
<li>
Haga doble clic sobre el campo *CosteCombustible* en la lista de la consulta Lecturas‑finales para añadirlo a la tabla de la consulta en la parte inferior.
</li>

Haga doble clic sobre el campo *CosteCombustible* en la lista de la consulta Lecturas‑finales para añadirlo a la tabla de la consulta en la parte inferior.

<li>
Añada un campo calculado a la derecha del campo CosteCombustible.
</li>

<li style="list-style-type: none;">
<ul>
<li>
Escriba lo siguiente en la celda Campo de la tabla inferior:
"Lecturas-finales"."CosteCombustible" / ( "Lecturas‑finales"."Cuentakilómetros" - "Combustible"."Cuentakilómetros" )
</li>
<li>
Escriba lo siguiente en su celda Alias: coste por milla
</li>

"Lecturas-finales"."CosteCombustible" / ( "Lecturas‑finales"."Cuentakilómetros" - "Combustible"."Cuentakilómetros" )
<td width="15%" bgcolor="#94bd5e">**Nota**</td><td width="85%" valign="top">Si usa el sistema métrico, el alias apropiado es coste por km</td>

Si usa el sistema métrico, el alias apropiado es coste por km

<li>
Guarde y cierre la consulta.
</li>
<li>
Abra un informe nuevo.
<ul>
<li>
Haga clic con el botón secundario en la consulta Consumo combustible y seleccione **Asistente para informes**.
</li>
</ul>
</li>
<li>
Seleccione los campos.
<ul>
<li>
Mueva todos los campos desde Campos disponibles a la lista Campos del informe. Use **&gt;&gt; **para hacerlo. Pulse **Siguiente**.
</li>
</ul>
</li>
<li>
Ponga etiquetas a los campos.
<ul>
<li>
Cambie CosteCombustible a Coste Combustible escribiendo un espacio entre las palabras. Haga clic en **Siguiente**.
</li>
</ul>
</li>
<li>
Agrupe los campos.
<ul>
<li>
Utilice **&gt;** para mover el campo Fecha a la lista *Agrupaciones.* Pulse **Siguiente**.
</li>
</ul>
</li>
<li>
Opciones de ordenación: saltar esta opción.
</li>
<li>
Selección del diseño: acepte el predeterminado. Hacer clic en **Siguiente**.
</li>
<li>
Cree el informe.
</li>

Abra un informe nuevo.

Seleccione los campos.

Ponga etiquetas a los campos.

Agrupe los campos.

Opciones de ordenación: saltar esta opción.

Cree el informe.

<li style="list-style-type: none;">
<ul>
<li>
Cambie el nombre del informe a Estadísticas combustible.
</li>
<li>
La opción predeterminada es Informe dinámico, por lo que no se requieren cambios.
</li>
<li>
Seleccione Modificar diseño de informe.
</li>
<li>
Haga clic en **Finalizar**.
</li>

La opción predeterminada es Informe dinámico, por lo que no se requieren cambios.

Haga clic en **Finalizar**.


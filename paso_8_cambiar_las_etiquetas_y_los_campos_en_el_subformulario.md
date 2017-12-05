
# Paso 8: cambiar las etiquetas y los campos en el subformulario

El subformulario está situado en la parte inferior del formulario. Queremos ensanchar la columna Fecha, cambiar el campo en la columna FormaPago a un Campo combinado y cambiar la etiqueta de la columna FormaPago a dos palabras.

Mueva el cursor sobre la línea divisoria entre las columnas Fecha y CosteCombustible para ensanchar la columna Fecha. Cuando el cursor cambie, pulse y arrástrelo para mover la línea divisoria a la derecha.

Para cambiar la columna FormaPago:

<li>
Haga clic con el botón secundario en la etiqueta FormaPago y en el menú seleccione **Reemplazar por → Campo combinado**.
</li>
<li>
Vuelva a hacer clic con el botón secundario sobre la etiqueta FormaPago para abrir el menú y seleccione **Columna** para abrir la ventana .
</li>
<li>
En la caja Título, cambie FormaPago a Forma Pago.
</li>
<li>
Pulse la pestaña **Datos**.
</li>
<li>
En el campo *Tipo del contenido de lista*, seleccione *Sql*.
</li>
<li>
Escriba exactamente lo siguiente:
</li>

Vuelva a hacer clic con el botón secundario sobre la etiqueta FormaPago para abrir el menú y seleccione **Columna** para abrir la ventana .

Pulse la pestaña **Datos**.

Escriba exactamente lo siguiente:

SELECT "Tipo", "Tipo" FROM "Tipo pago"

<li>
Cierre la ventana Propiedades.
</li>

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/Fig29.png)

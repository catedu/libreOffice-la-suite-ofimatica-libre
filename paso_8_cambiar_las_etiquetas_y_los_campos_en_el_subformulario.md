
# Paso 8: cambiar las etiquetas y los campos en el subformulario

El subformulario está situado en la parte inferior del formulario. Queremos ensanchar la columna Fecha, cambiar el campo en la columna FormaPago a un Campo combinado y cambiar la etiqueta de la columna FormaPago a dos palabras.

Mueva el cursor sobre la línea divisoria entre las columnas Fecha y CosteCombustible para ensanchar la columna Fecha. Cuando el cursor cambie, pulse y arrástrelo para mover la línea divisoria a la derecha.

Para cambiar la columna FormaPago:

1. Haga clic con el botón secundario en la etiqueta FormaPago y en el menú seleccione **Reemplazar por → Campo combinado**.

2. Vuelva a hacer clic con el botón secundario sobre la etiqueta FormaPago para abrir el menú y seleccione **Columna** para abrir la ventana .

3. En la caja Título, cambie FormaPago a Forma Pago.

4. Pulse la pestaña **Datos**.

5. En el campo *Tipo del contenido de lista*, seleccione *Sql*.

6. Escriba exactamente lo siguiente:

        SELECT "Tipo", "Tipo" FROM "Tipo pago"

7. Cierre la ventana Propiedades.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/Fig29.png)

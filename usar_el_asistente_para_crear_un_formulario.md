
# Usar el asistente para crear un formulario

Usaremos el Asistente para formularios para crear un formulario Vacaciones, el cuál contendrá un formulario y un subformulario.

En la ventana principal de la base de datos pulse el icono **Formularios** en la columna de la izquierda. En la lista de tareas, haga doble clic en **Usar el asistente para crear formulario** para abrir el Asistente para formularios. Los formularios simples necesitan solo algunos de estos pasos, mientras que los formularios más complejos puede que usen todos.

**Paso 1: seleccione campos.**

<li>
En *Tabla o consulta* seleccione Tabla: Vacaciones. La sección *Campos disponibles* muestra una lista de los campos de la tabla Vacaciones*.*
</li>
<li>
Pulse la doble flecha de la derecha para mover todos los campos hacia la lista *Campos del formulario*. Haga clic en **Siguiente.**
</li>

Pulse la doble flecha de la derecha para mover todos los campos hacia la lista *Campos del formulario*. Haga clic en **Siguiente.**

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/AistenteForm.png)
**Paso 2: configurar un subformulario.**

Dado que ya hemos creado una relación entre las tablas Combustible y Vacaciones, usaremos esa relación. Si no se hubieran definido relaciones se podría hacer en el paso 4.

<li value="1">
Haga clic en la caja etiquetada *Agregar subformulario.*
</li>
<li>
Pulse en *Subformulario basado en relación existente.*
</li>
<li>
El campo Combustible aparece en la lista de relaciones para agregar, así que pulse en el nombre para resaltarlo. Haga clic en **Siguiente**.
</li>

Pulse en *Subformulario basado en relación existente.*

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/SubForm.png)
**Paso 3: añadir campos a un subformulario.**

Este paso es exactamente igual que el paso 1. La única diferencia es que en el subformulario no se usan todos los campos.

<li value="1">
Combustible aparece preseleccionado en *Tabla o consulta.*
</li>
<li>
Utilice el botón **&gt;&gt;** para mover todos los campos a la derecha.
</li>
<li>
Pulse en el campo IdCombustible para resaltarlo.
</li>
<li>
Utilice el botón **&lt;** para mover el campo IdCombustible hacia la izquierda.
</li>
<li>
Pulse **Siguiente**.
</li>

Utilice el botón **&gt;&gt;** para mover todos los campos a la derecha.

Utilice el botón **&lt;** para mover el campo IdCombustible hacia la izquierda.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/SubForm1.png)
**Paso 4: obtener campos combinados.**

Este paso es para tablas o consultas en las que no se ha definido una relación. Como nosotros ya habíamos definido la relación, el asistente ignora este paso.
<td width="15%" bgcolor="#94bd5e">**Nota**</td><td width="85%" valign="top">Es posible crear una relación entre dos tablas basada en más de un par de campos..</td>

Es posible crear una relación entre dos tablas basada en más de un par de campos..
<td width="15%" bgcolor="#ffd320">**Precaución**</td><td width="85%" valign="top">Cuando se seleccionan un par de campos de dos tablas para usarlos en una relación, éstos tienen que ser del mismo tipo. Por eso utilizamos el campo Fecha de ambas tablas: ambos son del tipo Fecha[DATE].Independientemente de que se seleccione uno, dos o más pares de campos de dos tablas para la relación, es necesario que cumplan algunos requisitos para que el formulario funcione.<ul><li value="1">Ningún campo del subformulario debe ser la clave primaria de su tabla (no se puede usar IDCombustible).</li><li>Cada par de campos combinado debe ser del mismo tipo.</li><li>Uno de los campos del formulario principal debe ser la clave primaria (se debe usar Fecha).</li></ul></td>



Independientemente de que se seleccione uno, dos o más pares de campos de dos tablas para la relación, es necesario que cumplan algunos requisitos para que el formulario funcione.

**Paso 5: organizar los campos de control.**

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/FormySubform.png)
<li>
Disposición del formulario principal: pulse el segundo icono (*En columnas – Etiquetas arriba*). Las etiquetas se colocarán encima de sus campos
</li>
<li>
Disposición del subformulario. Pulse el tercer icono *Como hoja de datos* (las etiquetas son las cabeceras de columna y los datos de los campos están en formato de hoja de cálculo). Pulse **Siguiente**.
</li>

Disposición del subformulario. Pulse el tercer icono *Como hoja de datos* (las etiquetas son las cabeceras de columna y los datos de los campos están en formato de hoja de cálculo). Pulse **Siguiente**.



**Paso 6: control de los datos introducidos.**

A menos que necesite activar alguna de estas opciones, acepte los ajustes por defecto. Haga clic en **Siguiente**.

**Paso 7: aplicar estilos.**

<li value="1">
Seleccione el color que desee en la lista *Aplicar estilos* (He elegido el beige, que es Naranja 4 en la Tabla de colores).
</li>
<li>
Seleccione el borde de campo que prefiera (He elegido 3D. Quizá usted podría experimentar con los diferentes ajustes posibles).
</li>
<li>
Pulse **Siguiente**.
</li>

Seleccione el borde de campo que prefiera (He elegido 3D. Quizá usted podría experimentar con los diferentes ajustes posibles).

**Paso 8:** **establezca un nombre.**

<li value="1">
Introduzca el nombre para el formulario. En este caso, es Combustible.
</li>
<li>
Pulse *Modificar el *formulario.
</li>
<li>
Haga clic en **Finalizar**. El formulario se abre en modo de Edición.
</li>

Pulse *Modificar el *formulario.


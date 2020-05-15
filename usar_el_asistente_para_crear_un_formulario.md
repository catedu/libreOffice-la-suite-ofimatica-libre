
# Usar el asistente para crear un formulario

Usaremos el Asistente para formularios para crear un formulario Vacaciones, el cuál contendrá un formulario y un subformulario.

En la ventana principal de la base de datos pulse el icono **Formularios** en la columna de la izquierda. En la lista de tareas, haga doble clic en **Usar el asistente para crear formulario** para abrir el Asistente para formularios. Los formularios simples necesitan solo algunos de estos pasos, mientras que los formularios más complejos puede que usen todos.

**Paso 1: seleccione campos.**

1. En *Tabla o consulta* seleccione Tabla: Vacaciones. La sección *Campos disponibles* muestra una lista de los campos de la tabla Vacaciones*.*

2. Pulse la doble flecha de la derecha para mover todos los campos hacia la lista *Campos del formulario*. Haga clic en **Siguiente.**

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/AistenteForm.png)

**Paso 2: configurar un subformulario.**

Dado que ya hemos creado una relación entre las tablas Combustible y Vacaciones, usaremos esa relación. Si no se hubieran definido relaciones se podría hacer en el paso 4.

1. Haga clic en la caja etiquetada *Agregar subformulario.*

2. Pulse en *Subformulario basado en relación existente.*

3. El campo Combustible aparece en la lista de relaciones para agregar, así que pulse en el nombre para resaltarlo. Haga clic en **Siguiente**.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/SubForm.png)

**Paso 3: añadir campos a un subformulario.**

Este paso es exactamente igual que el paso 1. La única diferencia es que en el subformulario no se usan todos los campos.

1. Combustible aparece preseleccionado en *Tabla o consulta.*

2. Utilice el botón **&gt;&gt;** para mover todos los campos a la derecha.

3. Pulse en el campo IdCombustible para resaltarlo.

4. Utilice el botón **&lt;** para mover el campo IdCombustible hacia la izquierda.

5. Pulse **Siguiente**.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/SubForm1.png)

**Paso 4: obtener campos combinados.**

Este paso es para tablas o consultas en las que no se ha definido una relación. Como nosotros ya habíamos definido la relación, el asistente ignora este paso.

**Nota**: Es posible crear una relación entre dos tablas basada en más de un par de campos..

**Precaución**: Cuando se seleccionan un par de campos de dos tablas para usarlos en una relación, éstos tienen que ser del mismo tipo. Por eso utilizamos el campo Fecha de ambas tablas: ambos son del tipo Fecha[DATE].

Independientemente de que se seleccione uno, dos o más pares de campos de dos tablas para la relación, es necesario que cumplan algunos requisitos para que el formulario funcione. 

- Ningún campo del subformulario debe ser la clave primaria de su tabla (no se puede usar IDCombustible).

- Cada par de campos combinado debe ser del mismo tipo.
 
- Uno de los campos del formulario principal debe ser la clave primaria (se debe usar Fecha).

**Paso 5: organizar los campos de control.**
Cada control en un formulario consiste en dos partes: etiqueta y campo. En este paso de la creación del formulario se determina dónde se colocan las etiquetas en relación con los campos. Las cuatro posibilidades, de izquierda a derecha son En columnas–Etiquetas a la izquierda, En columnas–Etiquetas arriba, Como hoja de datos y En bloques-Etiquetas arriba.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/FormySubform.png)

1. Disposición del formulario principal: pulse el segundo icono (*En columnas – Etiquetas arriba*). Las etiquetas se colocarán encima de sus campos

2. Disposición del subformulario. Pulse el tercer icono *Como hoja de datos* (las etiquetas son las cabeceras de columna y los datos de los campos están en formato de hoja de cálculo). Pulse **Siguiente**.

**Paso 6: control de los datos introducidos.**

A menos que necesite activar alguna de estas opciones, acepte los ajustes por defecto. Haga clic en **Siguiente**.

**Paso 7: aplicar estilos.**

1. Seleccione el color que desee en la lista *Aplicar estilos* (He elegido el beige, que es Naranja 4 en la Tabla de colores).

2. Seleccione el borde de campo que prefiera (He elegido 3D. Quizá usted podría experimentar con los diferentes ajustes posibles).

3. Pulse **Siguiente**.

**Paso 8:** **establezca un nombre.**

1. Introduzca el nombre para el formulario. En este caso, es Combustible.

2. Pulse *Modificar el *formulario.

3. Haga clic en **Finalizar**. El formulario se abre en modo de Edición.


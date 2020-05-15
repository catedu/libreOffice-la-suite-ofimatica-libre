
# Crear tablas en la vista de diseño

La vista de diseño es un método más avanzado para crear una tabla, en el que se introduce directamente la información de cada campo. Usaremos este método para las tablas de nuestra base de datos.

**Nota**: Aunque *Tipo de campo* y *formato* son diferentes en la *vista de diseño*, los conceptos son los mismos que en el asistente.

La primera tabla que crearemos será *Combustible*. Sus campos son *IDCombustible, Fecha, CosteCombustible, CantidadCombustible, Cuentakilometros y FormaPago*.

1. Pulse *Crear tabla* en la vista de diseño.

2. En el campo *IDCombustible:*

    - Escriba *IDCombustible* en el primer nombre de campo. Pulse la tecla *Tabulador* para moverse a la columna *Tipo del campo*.

    - Como tipo de campo seleccione *Integer** **[INTEGER]* en la lista desplegable (el tipo predeterminado es Texto [VARCHAR]).

**Sugerencia**:Un atajo para seleccionar en la lista desplegable Tipo de campo: escriba la primera letra del tipo elegido. Puede alternar entre todas las elecciones que comienzan por esa letra presionándola repetidamente.

- Cambie las propiedades del campo en la sección inferior.
- Cambie *Valor automático* de *No* a *Sí.*
- Marque IDCombustible como *Llave primaria*.

Haga clic con el botón secundario sobre el triángulo verde que hay junto a *IDCombustible*, a la izquierda y seleccione *Llave primaria* en el menú. Se colocará un icono con una llave delante del campo *IDCombustible.*

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/IdPrimaria.png)

**Nota**La clave primaria tiene un único propósito: identificar el registro de forma única. Se puede utilizar cualquier nombre para este campo. Nosotros hemos utilizado IDCombustible por conveniencia, así sabemos a qué tabla pertenece.
La clave primaria tiene un único propósito: identificar el registro de forma única. Se puede utilizar cualquier nombre para este campo. Nosotros hemos utilizado IDCombustible por conveniencia, así sabemos a qué tabla pertenece.

3. Para el resto de campos (*Fecha, CosteCombustible, CantidadCombustible, Cuentakilometros y FormaPago):*

- Escriba el nombre del campo en la columna *Nombre del campo*.
- Seleccione el *Tipo del campo* para cada campo.
    - Para *Fecha* use *Fecha[DATE]* (pulse *F* para seleccionarlo).
- *FormaPago* usa *Texto [VARCHAR]*, el predeterminado.
    - Para los demás campos, elija *Número [NUMERIC]* (pulse la tecla *N* una vez para seleccionarlo).
- *CosteCombustible, CantidadCombustible* y *Cuentakilometros* necesitan algunos cambios en la sección *Propiedades*.
    - *CantidadCombustible*: cambie *Tamaño* a 6 y *Decimales *a 3 (muchos surtidores miden el combustible en milésimas).
    - *Cuentakilómetros*: cambie *Tamaño* a 10 y *Decimales* a 1.
    - *CosteCombustible*: cambie *Tamaño* a 5 y *Decimales* a 2. Pulse *Ejemplo de formato.* Esto abre la ventana *Formato de campo*. Seleccione *Moneda* como categoría y su moneda como *Formato*. Mi moneda tiene dos decimales. Seleccione la apropiada para su caso.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/CreandoCampos.png)

4. Descripción puede ser cualquier cosa, o puede dejarse en blanco.

5. Para guardar y cerrar la tabla seleccione **Archivo → Guardar**. Llame a la tabla *Combustible*. Cierre la tabla *Combustible*.

Siga los mismos pasos para crear la tabla *Vacaciones*. Los campos y su tipo se indican en la siguiente imagen. Asegúrese de que el campo *Fecha* sea la clave principal antes de cerrar. Guarde la tabla con el nombre *Vacaciones* y ciérrela.

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/TablaVacaciones.png)

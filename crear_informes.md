
# Crear informes

Los informes proporcionan de forma útil la información que se encuentra en la base de datos, de forma similar a las consultas. **Los informes se generan desde las tablas o consultas de la base de datos**. Pueden contener todos los campos de la tabla o consulta, o solamente un grupo seleccionado de campos. Los informes pueden ser **estáticos** o **dinámicos**. Los informes estáticos contienen los datos de los campos seleccionados en el momento de generar el informe mientras que los dinámicos se pueden actualizar para que muestren los últimos datos.

Por ejemplo, un informe de gastos de unas vacaciones en el pasado podría ser un informe estático porque está basado en datos específicos que no cambian. Sin embargo, un informe de datos de combustible sería probablemente un informe dinámico porque depende de datos que cambian.
<td width="661" bgcolor="#ffd320">**Precaución**</td><td width="3684">Los informes dinámicos actualizan sólo los *datos* que se cargan o añaden a la tabla o consulta. **No** muestran ningún cambio hecho a la tabla o la consulta en sí. Por ejemplo, después de crear el ejemplo siguiente, abra la consulta Consumo combustible creada antes. Cambie el número 1 por el número 3 en la columna “Lecturas‑finales”.”Cuentakilómetros” – “Combustible”.Cuentakilómetros”. El informe será idéntico antes y después de que haga los cambios.</td>



Todos los informes se basan en una tabla o consulta única. Por eso, debe decidir qué campos quiere usar en el informe. Si quiere usar campos de diferentes tablas, antes debe combinar esos campos en una única consulta, después puede crear un informe basado en esa consulta.

Por ejemplo, un informe de gastos de vacaciones incluye gastos de combustible y gastos de comida. Estos campos están contenidos en dos tablas diferentes: Vacaciones y Combustible y, por lo tanto, se necesita crear una consulta.


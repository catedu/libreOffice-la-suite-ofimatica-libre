
# Crear un informe estático

Crearemos un informe de gastos de vacaciones. Es necesario **contestar algunas preguntas** antes de crear el informe.

<li>
¿Qué información queremos en el informe?
</li>
<li>
¿Cómo queremos ordenar la información?
</li>
<li>
¿Qué campos se necesitan para proporcionar esta información?
</li>
<li>
¿Es necesario crear una consulta porque estos campos están en tablas diferentes?
</li>
<li>
¿Se necesita algún cálculo en los datos antes de añadirlos al informe?
</li>


Los gastos de nuestras vacaciones son motel, peajes, misceláneos, desayuno, almuerzo, cena, tapas y combustible. Un posible informe simplemente mostraría una lista con los **totales de cada uno de estos grupos de gastos**. Otro informe posible mostraría los **gastos totales para cada día de las vacaciones**. Un tercer informe mostraría los **totales para cada grupo de gastos por tipo de pago** (esto nos permitiría saber de dónde vino el dinero para pagar los gastos). **La mejor manera de crear informes como éstos es crear las consultas necesarias para obtener los datos que se requieren, insertar los datos en una hoja de cálculo y utilizar las funciones de Calc que se necesiten en estos datos.**

Crearemos **dos informes**, uno con la lista de gastos de cada día distintos del combustible y otro con los gastos de combustible de cada día.

Los datos que necesitamos para el primer informe de la tabla Vacaciones son: Fecha, Motel, Peaje, Desayuno, Almuerzo, Cena, CosteTapas y Misceláneos. Este informe no requiere una consulta adicional.

El segundo informe utiliza la tabla Combustible. Puesto que esta tabla contiene gastos de combustible de otros momentos diferentes a las vacaciones, necesitamos crear una consulta que contenga sólo gastos de combustible realizados en las vacaciones.


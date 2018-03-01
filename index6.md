
# ¿Qué es Base?

Una fuente de datos, o base de datos, es una colección de trozos de información a los que se puede acceder o que se pueden gestionar desde LibreOffice. Por ejemplo, una lista de nombres y direcciones es una base de datos que se puede usar para producir correo mediante combinación de correspondencia. Una lista del inventario de una tienda podría ser una fuente de datos manejada por LibreOffice.

**Nota:** LibreOffice usa los términos “base de datos” y “fuente de datos” para referirse a lo mismo, lo que puede ser una base de datos como MySQL o dBase o una hoja de cálculo o un documento de texto que contenga datos.

Este capítulo cubre la forma de crear una base de datos, mostrar el contenido de una base de datos y cómo se usan las distintas partes en LibreOffice. También cubre cómo usar el componente Base de LibreOffice para registrar otras fuentes de datos. Una fuente de datos puede ser una base de datos, una hoja de cálculo o un documento de texto.

**Nota:** LibreOffice Base utiliza el motor de base de datos HSQL. Todos los archivos creados por este motor se guardan en un archivo comprimido. Los formularios de la base de datos se incluyen en dicho archivo comprimido.

Una *base de datos* consiste en un número de *campos* que contienen los fragmentos individuales de datos. Cada *tabla* de la base de datos es un grupo de campos. Al crear una base de datos, también se determinan las características de cada campo de la tabla. Los *formularios* se usan para introducir datos en los campos de una o más tablas asociadas con el formulario. También se pueden usar para ver los campos de una o más tablas asociadas con el formulario. Una *consulta* crea una tabla nueva a partir de las tablas existentes dependiendo de la forma en que se ha creado la consulta. Un *informe* organiza la información de los campos de una consulta en un documento según sus necesidades.
 
**Precaución** La base de datos LibreOffice necesita la máquina virtual de Java (*Java Runtime Environment,*JRE). Si no está en su equipo, puede descargarla de [www.java.com](http://www.java.com/) e instalarla siguiendo las instrucciones que encontrará en el sitio. Debe ser Java 5.0 o una versión superior. En LibreOffice, use **Herramientas → Opciones → LibreOffice → Java** para registrar Java. La versión Java de Windows no puede usarse, sin embargo, otras versiones sí.

Base crea *bases de datos relacionales*. Esto hace mucho más fácil crear una base de datos en la que los campos tienen relaciones unos con otros.

Por ejemplo: considere una base de datos para una biblioteca. Tendrá un campo para los nombres de los autores y otro campo para los nombres de los libros. Obviamente, hay una relación entre los autores y los libros que han escrito. La biblioteca puede tener más de un libro para un mismo autor. Esto es lo que se conoce como una relación de uno a varios: un autor y más de un libro. La mayoría, si no todas, las relaciones en una base de datos son relaciones uno a varios.

Imagine una base de datos de empleados para la misma biblioteca. Uno de los campos contendría los nombres de los empleados mientras que otro contendría el número de la seguridad social y otros datos personales. La relación entre los nombres y el número de la seguridad social es una relación uno a uno: sólo un número de la seguridad social para cada nombre.

Si está familiarizado con los conjuntos matemáticos, una base de datos relacional puede explicarse fácilmente en términos de conjuntos: elementos, subconjuntos, uniones e intersecciones. Los campos son los elementos. Las tablas son los subconjuntos. Las relaciones se definen en base a uniones e intersecciones de los subconjuntos (tablas).

Para explicar cómo se usa una base de datos, crearemos una para los gastos del coche. En el proceso explicaremos cómo funciona una base de datos.


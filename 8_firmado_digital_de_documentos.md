
# 8. Firmado digital de documentos

<br />Para firmar un documento digitalmente, necesita una clave personal, el certificado. La clave personal se guarda en su computadora como una combinación de una clave privada, que debe mantenerse en secreto, y una clave pública, que debe agregar a sus documentos cuando los firma. Puede obtener un certificado de una autoridad certificadora, que puede ser una compañía privada o una institución gubernamental.

Cuando aplique una firma digital a un documento, una suerte de checksum (suma de control) se obtiene del contenido del documento añadido a su clave personal. El checksum y su clave pública se almacenan juntos en el documento. 

Cuandomás tarde, alguien abra el documento en cualquier computadora con una versión reciente de LibreOffice, el programa calculará el checksum nuevamente y lo comparará con el checksum almacenado. Si ambos son iguales, el programa dará la señal de que se está viendo el documento original, inalterado. Además, el programa puede mostrarle la información de la clave pública desde el certificado. Puede comparar la clave pública con la que esté publicada en el sitio web de la autoridad certificadora.

Cuando alguien cambie algo en el documento, este cambió rompe la firma digital.

En los sistemas operativos Windows, se usan las funciones de validación de firma digital de Windows. En los sistemas Solaris y Linux, se usan los archivos proporcionados por Thunderbird, Mozilla o Firefox. Para una descripción más detallada acerca de cómo conseguir y administrar un certificado y una validación de firma, vea “Aplicar firmas digitales” en la ayuda de LibreOffice.

Para firmar un documento:

<li value="1">
Vaya a **Archivo**** → Firmas digitales**.
</li>
<li>
Si no ha guardado el documento desde el último cambio, aparecerá un cuadro de mensaje. Haga clic en **Sí** para guardar el archivo.
</li>
<li>
Después de guardar, verá el cuadro de diálogo de firmas digitales. Haga clic en **Añadir** para añadir una clave pública al documento.
</li>
<li>
En el cuadro de diálogo Seleccionar certificado, seleccione su certificado y haga clic en **Aceptar**. 
</li>
<li>
Verá nuevamente el cuadro de diálogo Firmas digitales, donde podrá añadir más certificados si lo desea. Haga clic en **Aceptar** para añadir la clave pública al archivo guardado.
</li>

Si no ha guardado el documento desde el último cambio, aparecerá un cuadro de mensaje. Haga clic en **Sí** para guardar el archivo.

En el cuadro de diálogo Seleccionar certificado, seleccione su certificado y haga clic en **Aceptar**. 

![](https://raw.githubusercontent.com/catedu/libreOffice-la-suite-ofimatica-libre/master/img/image18.png)

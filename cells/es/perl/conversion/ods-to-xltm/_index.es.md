---
title:  Convierta ODS a XLTM usando Perl
description: Utilizar el SDK de la nube Aspose.Cells para Perl para convertir un archivo de formato ODS a un archivo de formato XLTM.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir ODS a XLTM" h2="Biblioteca Perl para convertir ODS a XLTM" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en Perl proyectos. Esta es una solución profesional para convertir ODS a XLTM y otros formatos de documentos en línea usando Perl." urlsection="conversion/ods-to-xltm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierta ODS a XLTM usando Cells Cloud SDK para Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de ODS a XLTM puede ser una tarea compleja. Nuestro SDK Perl maneja todas las conversiones de formato ODS a XLTM al tiempo que conserva el contenido estructural y lógico principal de la hoja de cálculo ODS de origen. Nuestra biblioteca Perl proporciona una solución profesional para convertir archivos ODS a XLTM en línea. Este SDK de nube brinda a los desarrolladores Perl una potente funcionalidad y garantiza una salida XLTM de alta calidad.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl Ejemplo de código para convertir ODS a XLTM usando Cells Cloud SDK" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "xltm";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.ods");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.ods") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.xltm") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Perl SDK para convertir ODS a XLTM" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Utilice el método `put_convert_workbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

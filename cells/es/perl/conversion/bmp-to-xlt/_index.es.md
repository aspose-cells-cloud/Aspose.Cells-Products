---
title:  BMP a XLT Convertir API para Perl
description:  Usando Aspose.Cells Cloud SDK para Perl para convertir un archivo de formato BMP a un archivo de formato XLT.
url: /es/perl/conversion/bmp-to-xlt/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API para convertir BMP a XLT" h2="Perl biblioteca para convertir BMP a XLT" p="Use Cells Conversión REST API para crear flujos de trabajo de hojas de cálculo personalizados en Perl. Esta es una solución profesional para convertir BMP a XLT y otros formatos de documentos en línea usando Perl." urlsection="conversion/bmp-to-xlt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierta un archivo BMP a XLT en Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de BMP a XLT es una tarea compleja. Todas las transiciones de formato BMP a XLT se realizan mediante nuestro SDK Perl mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo fuente BMP. Nuestra biblioteca Perl es una solución profesional para convertir BMP a archivos XLT en línea. Este SDK de Cloud ofrece a los desarrolladores de Perl una potente funcionalidad y una salida XLT perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Perl usando REST API para convertir BMP al formato XLT" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "xlt";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.bmp");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.bmp") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.xlt") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Perl API para convertir BMP a XLT" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llamar a celdas_libro de trabajo_poner_convertir_método del libro de trabajo para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

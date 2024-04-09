---
title: Convierta FODS a XPS usando Perl
description:  Utilizar el SDK de la nube Aspose.Cells para Perl para convertir un archivo de formato FODS a un archivo de formato XPS.
kwords: Excel, Convert FODS to XPS, REST, Perl
howto: How to convert FODS to XPS using Aspose.Cells Cloud Perl library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir FODS a XPS" h2="Biblioteca Perl para convertir FODS a XPS" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en Perl proyectos. Esta es una solución profesional para convertir FODS a XPS y otros formatos de documentos en línea usando Perl." urlsection="conversion/fods-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta FODS a XPS usando Cells Cloud SDK para Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de FODS a XPS puede ser una tarea compleja. Nuestro SDK Perl maneja todas las conversiones de formato FODS a XPS y al mismo tiempo conserva el contenido estructural y lógico principal de la hoja de cálculo FODS de origen. Nuestra biblioteca Perl proporciona una solución profesional para convertir archivos FODS a XPS en línea. Este SDK de nube brinda a los desarrolladores de Perl una potente funcionalidad y garantiza resultados de XPS de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Ejemplo de código para convertir FODS a XPS usando Cells Cloud SDK" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "xps";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.fods");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.fods") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.xps") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo convertir FODS a XPS usando la biblioteca Cells Cloud Perl." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale el paquete Perl y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Perl.</li>
<li>Utilice el método `put_convert_workbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

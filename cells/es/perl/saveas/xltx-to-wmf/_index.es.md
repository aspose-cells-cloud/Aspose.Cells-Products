﻿---
title:  Guarde XLTX como WMF usando Perl
description:  Utilizando Aspose.Cells Cloud SDK para Perl para guardar el archivo en formato XLTX como archivo en formato WMF.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Guarde XLTX como WMF" h2="Biblioteca Perl para guardar XLTX como WMF" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Perl. Esta es una solución profesional para guardar XLTX como WMF y otros formatos de documentos en línea usando Perl." urlsection="saveas/xltx-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo XLTX como WMF en Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de XLTX como WMF es una tarea compleja. Todas las transiciones de formato XLTX a WMF se realizan mediante nuestro SDK Perl mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo XLTX de origen. Nuestra biblioteca Perl es una solución profesional para guardar XLTX como archivos WMF en línea. Este SDK de nube ofrece a los desarrolladores de Perl una potente funcionalidad y una salida WMF perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Perl Ejemplo de código para guardar XLTX como WMF usando REST API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.xltx';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.wmf';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para Perl para guardar archivos Excel en otros formatos XLTX como WMF" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Publicación de llamada_libro de trabajo_método save_as para obtener la secuencia resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

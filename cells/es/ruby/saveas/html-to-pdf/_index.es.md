﻿---
title:  Guarde HTML como PDF API para Ruby
description:  Usando Aspose.Cells Cloud SDK para Ruby para guardar el archivo de formato HTML como archivo de formato PDF.
url: /es/ruby/saveas/html-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API para guardar HTML como PDF" h2="Biblioteca Ruby para guardar HTML como PDF" p="Utilice Cells SaveAs REST API para crear flujos de trabajo de hojas de cálculo personalizados en Ruby. Esta es una solución profesional para guardar HTML como PDF y otros formatos de documentos en línea usando Ruby." urlsection="saveas/html-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Guarde un archivo HTML como PDF en Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo desde HTML como PDF es una tarea compleja. Todas las transiciones de formato HTML a PDF son realizadas por nuestro Ruby SDK mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo fuente HTML. Nuestra biblioteca Ruby es una solución profesional para guardar archivos HTML como PDF en línea. Este SDK de Cloud ofrece a los desarrolladores de Ruby una potente funcionalidad y un resultado PDF perfecto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Ruby usando REST API para guardar HTML como formato PDF" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.html'
    save_options = nil
    newfilename = 'Book1Saveas.pdf'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Ruby API para guardar HTML como PDF" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llamar a celdas_ahorrar_como_correo_documento_ahorrar_como método para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>rubí 2.5 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
---
title:  Guarde XLSM como FODS usando Ruby
description:  Utilizando Aspose.Cells Cloud SDK para Ruby para guardar el archivo en formato XLSM como archivo en formato FODS.
kwords: Excel, Save XLSM as FODS, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLSM as FODS using the Cells Cloud Ruby library.","description": "How to save XLSM as FODS using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/saveas/xlsm-to-fods/","step": [{ "@type": "HowToStep","name": "How to save XLSM as FODS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xlsm-to-fods/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLSM as FODS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xlsm-to-fods/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLSM as FODS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xlsm-to-fods/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to save XLSM as FODS using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/xlsm-to-fods/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Guarde XLSM como FODS" h2="Biblioteca Ruby para guardar XLSM como FODS" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Ruby. Esta es una solución profesional para guardar XLSM como FODS y otros formatos de documentos en línea usando Ruby." urlsection="saveas/xlsm-to-fods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Guarde un archivo XLSM como FODS en Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de XLSM como FODS es una tarea compleja. Todas las transiciones de formato XLSM a FODS las realiza nuestro Ruby SDK mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo XLSM de origen. Nuestra biblioteca Ruby es una solución profesional para guardar XLSM como archivos FODS en línea. Este SDK de Cloud ofrece a los desarrolladores de Ruby una funcionalidad potente y una salida FODS perfecta.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código Ruby para guardar XLSM como FODS usando REST API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.xlsm'
    save_options = nil
    newfilename = 'Book1Saveas.fods'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo guardar XLSM como FODS usando la biblioteca Cloud Ruby Cells." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Ruby y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Ruby.</li>
<li>Utilice el método `post_workbook_save_as` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>rubí 2.5 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

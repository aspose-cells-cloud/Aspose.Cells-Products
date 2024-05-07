---
title:  Exporte HOJA DE TRABAJO a JSON desde Excel usando Cells Cloud SDK para Ruby
description:  Aspose.Cells Cloud REST API admite la exportación de archivos de formato {0} a {1} usando {2}.
kwords: Excel, worksheet, json, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKSHEET to JSON","description": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKSHEET to JSON","image": {"@type": "ImageObject"},"url": "/ruby/export/worksheet-to-json/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKSHEET to JSON step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/worksheet-to-json/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKSHEET to JSON step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/worksheet-to-json/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Ruby to export objects from Excel WORKSHEET to JSON step 1", "image": {"@type": "ImageObject",},"url": "/ruby/export/worksheet-to-json/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportar HOJA DE TRABAJO a JSON desde Excel" h2="Biblioteca Ruby para exportar HOJA DE TRABAJO a archivo JSON" p="Utilice Exportar API de Cells Cloud para exportar flujos de trabajo de objetos internos de archivos Excel en Ruby. Esta es una solución profesional para exportar HOJA DE TRABAJO a un archivo en formato JSON desde una hoja de cálculo en línea usando Ruby." urlsection="export/worksheet-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exporte el objeto WORKSHEET a un archivo en formato JSON usando Cells Cloud SDK para Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportar el objeto WORKSHEET a un archivo JSON desde el archivo Excel es una tarea compleja. Nuestro SDK de Ruby realiza la exportación de transiciones de HOJA DE TRABAJO a formato JSON mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo de HOJA DE TRABAJO de origen. Nuestra biblioteca Ruby es una solución profesional para exportar objetos WORKSHEET a archivos en formato JSON en línea. Este SDK de Cloud ofrece a los desarrolladores de Ruby una funcionalidad potente y una salida JSON perfecta.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código en Ruby usando REST API para exportar HOJA DE TRABAJO a formato JSON desde una hoja de cálculo" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::LiteCellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            files = {}      
            name = $DataSourceXlsx
            files[name] = ::File.open(File.expand_path("data/"+name),"r") 
            name =$AssemblyTestXlsx 
            files[name] = ::File.open(File.expand_path("data/"+name),"r")
            format = 'json'
            objectType =  'worksheet'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para Ruby para exportar objetos de Excel WORKSHEET a JSON" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Llame al método post_export para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>rubí 2.5 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

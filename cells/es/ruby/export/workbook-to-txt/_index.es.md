---
title:  Exporte WORKBOOK a TXT desde Excel usando Cells Cloud SDK para Ruby
description:  Aspose.Cells Cloud REST API admite la exportación de archivos de formato {0} a {1} usando {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportar LIBRO DE TRABAJO a TXT desde Excel" h2="Biblioteca Ruby para exportar WORKBOOK a archivo TXT" p="Utilice Exportar API de Cells Cloud para exportar flujos de trabajo de objetos internos de archivos Excel en Ruby. Esta es una solución profesional para exportar WORKBOOK a un archivo en formato TXT desde una hoja de cálculo en línea usando Ruby." urlsection="export/workbook-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exporte el objeto WORKBOOK a un archivo en formato TXT usando Cells Cloud SDK para Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportar el objeto WORKBOOK a un archivo TXT desde el archivo Excel es una tarea compleja. Nuestro SDK de Ruby realiza la exportación de transiciones de WORKBOOK a formato TXT mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo de WORKBOOK de origen. Nuestra biblioteca Ruby es una solución profesional para exportar objetos WORKBOOK a archivos en formato TXT en línea. Este SDK de Cloud ofrece a los desarrolladores de Ruby una funcionalidad potente y una salida TXT perfecta.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código en Ruby usando REST API para exportar WORKBOOK a formato TXT desde una hoja de cálculo" gistPath="" %}}
  
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
            format = 'txt'
            objectType =  'workbook'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para Ruby para exportar objetos de Excel WORKBOOK a TXT" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Llame al método post_export para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>rubí 2.5 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

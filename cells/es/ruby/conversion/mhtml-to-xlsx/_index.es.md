﻿---
title:  MHTML a XLSX Convertir API para Ruby
description:  Usando Aspose.Cells Cloud SDK para Ruby para convertir un archivo de formato MHTML a un archivo de formato XLSX.
url: /es/ruby/conversion/mhtml-to-xlsx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API para convertir MHTML a XLSX" h2="Biblioteca Ruby para convertir MHTML a XLSX" p="Use Cells Conversion REST API para crear flujos de trabajo de hojas de cálculo personalizados en Ruby. Esta es una solución profesional para convertir MHTML a XLSX y otros formatos de documentos en línea usando Ruby." urlsection="conversion/mhtml-to-xlsx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierta un archivo MHTML a XLSX en Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de MHTML a XLSX es una tarea compleja. Todas las transiciones de formato MHTML a XLSX se realizan mediante nuestro Ruby SDK mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo MHTML de origen. Nuestra biblioteca Ruby es una solución profesional para convertir archivos MHTML a XLSX en línea. Este SDK de Cloud brinda a los desarrolladores de Ruby una funcionalidad poderosa y una salida XLSX perfecta.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Ruby usando REST API para convertir MHTML a formato XLSX" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.mhtml"
            format = 'xlsx'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Ruby API para convertir MHTML a XLSX" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llamar a celdas_libro de trabajo_poner_convertir_método del libro de trabajo para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>rubí 2.5 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
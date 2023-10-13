﻿---
title:  XLSB a PDF Convertir API para Ruby
description:  Usando Aspose.Cells Cloud SDK para Ruby para convertir un archivo de formato XLSB a un archivo de formato PDF.
url: /es/ruby/conversion/xlsb-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API para convertir XLSB a PDF" h2="Biblioteca Ruby para convertir XLSB a PDF" p="Use Cells Conversion REST API para crear flujos de trabajo de hojas de cálculo personalizados en Ruby. Esta es una solución profesional para convertir XLSB a PDF y otros formatos de documentos en línea usando Ruby." urlsection="conversion/xlsb-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierta un archivo XLSB a PDF en Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de XLSB a PDF es una tarea compleja. Todas las transiciones de formato XLSB a PDF se realizan mediante nuestro Ruby SDK mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo XLSB de origen. Nuestra biblioteca Ruby es una solución profesional para convertir archivos XLSB a PDF en línea. Este SDK de Cloud ofrece a los desarrolladores de Ruby una potente funcionalidad y un resultado PDF perfecto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Ruby usando REST API para convertir XLSB al formato PDF" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xlsb"
            format = 'pdf'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Ruby API para convertir XLSB a PDF" >}}
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
﻿---
title:  Convertir SXC a CSV usando Ruby
description: Utilizar el SDK de Cloud Aspose.Cells para Ruby para convertir un archivo de formato SXC a un archivo de formato CSV.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convertir SXC a CSV" h2="Biblioteca Ruby para convertir SXC a CSV" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en proyectos Ruby. Esta es una solución profesional para convertir SXC a CSV y otros formatos de documentos en línea usando Ruby." urlsection="conversion/sxc-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Convierta SXC a CSV usando Cells Cloud SDK para Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de SXC a CSV puede ser una tarea compleja. Nuestro Ruby SDK maneja todas las conversiones de formato SXC a CSV mientras preserva el contenido estructural y lógico principal de la hoja de cálculo SXC de origen. Nuestra biblioteca Ruby proporciona una solución profesional para convertir archivos SXC a CSV en línea. Este SDK de Cloud brinda a los desarrolladores de Ruby una potente funcionalidad y garantiza una salida CSV de alta calidad.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código Ruby para convertir SXC a CSV usando Cells Cloud SDK" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.sxc"
            format = 'csv'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para Ruby para convertir archivos Excel a otros formatos SXC a CSV" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Utilice el método `put_convert_workbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>rubí 2.5 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

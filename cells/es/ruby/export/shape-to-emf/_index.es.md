﻿---
title:  Exporte SHAPE a EMF desde una hoja de cálculo usando Ruby API
description:  Aspose.Cells Cloud REST API admite la exportación de archivos de formato {0} a {1} mediante {2}.
url: /es/ruby/export/shape-to-emf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API para exportar SHAPE al archivo EMF" h2="Biblioteca Ruby para exportar SHAPE al archivo EMF" p="Use Cells Exportar REST API para exportar flujos de trabajo de objetos internos de hojas de cálculo en Ruby. Esta es una solución profesional para exportar SHAPE a un archivo de formato EMF desde una hoja de cálculo en línea usando Ruby." urlsection="export/shape-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Exportar objeto SHAPE al archivo de formato EMF en Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportar un objeto SHAPE al archivo EMF desde una hoja de cálculo es una tarea compleja. Nuestro SDK de Ruby realiza la exportación de SHAPE a las transiciones de formato EMF mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo SHAPE de origen. Nuestra biblioteca Ruby es una solución profesional para exportar objetos SHAPE a archivos de formato EMF en línea. Este SDK de Cloud ofrece a los desarrolladores de Ruby una potente funcionalidad y un resultado EMF perfecto.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ejemplo de código en Ruby usando REST API para exportar SHAPE al formato EMF desde una hoja de cálculo" gistPath="" %}}
  
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
            format = 'emf'
            objectType =  'shape'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo usar Ruby API para exportar SHAPE a EMF" >}}
<li> Crea una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener la cuota API gratis y los detalles de autorización</li>
<li>Inicialice CellsApi con ID de cliente, secreto de cliente, URL base y versión API</li>
<li>Llame al método post_export para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>rubí 2.5 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
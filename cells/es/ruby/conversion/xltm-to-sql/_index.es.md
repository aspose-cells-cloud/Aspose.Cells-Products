---
title: Convierta XLTM a SQL usando Ruby
description:  Utilizar el SDK de Cloud Aspose.Cells para Ruby para convertir un archivo de formato XLTM a un archivo de formato SQL.
kwords: Excel, Convert XLTM to SQL, REST, Ruby
howto: How to convert XLTM to SQL using Aspose.Cells Cloud Ruby library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Convertir XLTM a SQL" h2="Biblioteca Ruby para convertir XLTM a SQL" p="Utilice la nube de conversión API de Cells para crear flujos de trabajo de hojas de cálculo personalizados en proyectos Ruby. Esta es una solución profesional para convertir XLTM a SQL y otros formatos de documentos en línea usando Ruby." urlsection="conversion/xltm-to-sql/" >}}

{{< blocks/products/cells/cells-cloud-section title="Convierta XLTM a SQL usando Cells Cloud SDK para Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Convertir formatos de archivo de XLTM a SQL puede ser una tarea compleja. Nuestro Ruby SDK maneja todas las conversiones de formato XLTM a SQL mientras preserva el contenido estructural y lógico principal de la hoja de cálculo XLTM de origen. Nuestra biblioteca Ruby proporciona una solución profesional para convertir archivos XLTM a SQL en línea. Este SDK de Cloud brinda a los desarrolladores de Ruby una potente funcionalidad y garantiza resultados SQL de alta calidad.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código Ruby para convertir XLTM a SQL usando Cells Cloud SDK" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xltm"
            format = 'sql'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Aprenda cómo convertir XLTM a SQL usando la biblioteca Cells Cloud Ruby." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Ruby y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Ruby.</li>
<li>Utilice el método `put_convert_workbook` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>rubí 2.5 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

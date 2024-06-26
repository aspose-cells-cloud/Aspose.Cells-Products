---
title:  Guarde CSV como FODS usando PHP
description: Utilizando Aspose.Cells Cloud SDK para PHP para guardar el archivo en formato CSV como archivo en formato FODS.
kwords: Excel, Save CSV as FODS, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save CSV as FODS using the Cells Cloud PHP library.","description": "How to save CSV as FODS using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/saveas/csv-to-fods/","step": [{ "@type": "HowToStep","name": "How to save CSV as FODS using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/csv-to-fods/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save CSV as FODS using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/csv-to-fods/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save CSV as FODS using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/csv-to-fods/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to save CSV as FODS using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/csv-to-fods/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Guardar CSV como FODS" h2="Biblioteca PHP para guardar CSV como FODS" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en PHP. Esta es una solución profesional para guardar CSV como FODS y otros formatos de documentos en línea usando PHP." urlsection="saveas/csv-to-fods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Guarde un archivo CSV como FODS en PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de CSV como FODS es una tarea compleja. Todas las transiciones de formato CSV a FODS se realizan mediante nuestro SDK PHP mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo CSV de origen. Nuestra biblioteca PHP es una solución profesional para guardar CSV como archivos FODS en línea. Este SDK de nube ofrece a los desarrolladores de PHP una potente funcionalidad y una salida FODS perfecta.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Ejemplo de código para guardar CSV como FODS usando REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.csv';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "fods";
    $newfilename = "Book1Saveas.fods";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo guardar CSV como FODS usando la biblioteca Cells Cloud PHP." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca PHP y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en PHP.</li>
<li>Utilice el método `PostWorkbookSaveAs` para recuperar la secuencia resultante.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>PHP 7.4 o más reciente</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

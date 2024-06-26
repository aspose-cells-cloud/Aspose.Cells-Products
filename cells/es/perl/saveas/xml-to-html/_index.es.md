---
title:  Guarde XML como HTML usando Perl
description:  Utilizando Aspose.Cells Cloud SDK para Perl para guardar el archivo en formato XML como archivo en formato HTML.
kwords: Excel, Save XML as HTML, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XML as HTML using the Cells Cloud Perl library.","description": "How to save XML as HTML using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/saveas/xml-to-html/","step": [{ "@type": "HowToStep","name": "How to save XML as HTML using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/xml-to-html/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XML as HTML using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/xml-to-html/","text": "Install Perl library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XML as HTML using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/xml-to-html/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to save XML as HTML using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/xml-to-html/","text": "Call post_workbook_save_as method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Guardar XML como HTML" h2="Biblioteca Perl para guardar XML como HTML" p="Utilice SaveAs API de Cells Cloud para crear flujos de trabajo de hojas de cálculo personalizados en Perl. Esta es una solución profesional para guardar XML como HTML y otros formatos de documentos en línea usando Perl." urlsection="saveas/xml-to-html/" >}}

{{< blocks/products/cells/cells-cloud-section title="Guarde un archivo XML como HTML en Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Guardar formatos de archivo de XML como HTML es una tarea compleja. Todas las transiciones de formato XML a HTML las realiza nuestro SDK Perl mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo XML de origen. Nuestra biblioteca Perl es una solución profesional para guardar XML como archivos HTML en línea. Este SDK de nube ofrece a los desarrolladores de Perl una funcionalidad potente y un resultado de HTML perfecto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Ejemplo de código para guardar XML como HTML usando REST API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.xml';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.html';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo guardar XML como HTML usando la biblioteca Cells Cloud Perl." >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Instale la biblioteca Perl y agregue la referencia (importe la biblioteca) a su proyecto.</li>
<li>Abra el archivo fuente en Perl.</li>
<li>Publicación de llamada_libro de trabajo_método save_as para obtener la secuencia resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

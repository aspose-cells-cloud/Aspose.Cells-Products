---
title:  Exporte WORKBOOK a SVG desde Excel usando Cells Cloud SDK para Perl
description:  Aspose.Cells Cloud REST API admite la exportación de archivos de formato {0} a {1} usando {2}.
kwords: Excel, workbook, svg, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to SVG","description": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to SVG","image": {"@type": "ImageObject"},"url": "/perl/export/workbook-to-svg/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to SVG step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/workbook-to-svg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to SVG step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/workbook-to-svg/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to SVG step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/workbook-to-svg/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Exportar LIBRO DE TRABAJO a SVG desde Excel" h2="Biblioteca Perl para exportar WORKBOOK al archivo SVG" p="Utilice Exportar API de Cells Cloud para exportar flujos de trabajo de objetos internos de archivos Excel en Perl. Esta es una solución profesional para exportar WORKBOOK a un archivo de formato SVG desde una hoja de cálculo en línea usando Perl." urlsection="export/workbook-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Exporte el objeto WORKBOOK a un archivo de formato SVG usando Cells Cloud SDK para Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Exportar el objeto WORKBOOK al archivo SVG desde el archivo Excel es una tarea compleja. Nuestro SDK Perl realiza la exportación de transiciones de WORKBOOK a formato SVG mientras se mantiene el contenido estructural y lógico principal de la hoja de cálculo de WORKBOOK de origen. Nuestra biblioteca Perl es una solución profesional para exportar objetos WORKBOOK a archivos con formato SVG en línea. Este SDK de nube ofrece a los desarrolladores de Perl una funcionalidad potente y un resultado de SVG perfecto.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ejemplo de código en Perl usando REST API para exportar WORKBOOK al formato SVG desde una hoja de cálculo" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use MIME::Base64;
    use AsposeCellsCloud::LightCellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::LightCellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $filemap = { 'Book1.xlsx' => '~/TestData/Book1.xlsx', 'myDocument.xlsx' => ~/TestData/myDocument.xlsx'};
    my $result = $instance->post_export(file => $filemap , object_type => 'workbook',format => 'svg');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cómo utilizar Cells Cloud SDK para Perl para exportar objetos de Excel WORKBOOK a SVG" >}}
<li> Registre una cuenta en<a href="https://dashboard.aspose.cloud/">Panel</a> para obtener gratis API cuota y detalles de autorización</li>
<li>Inicialice Cells API con su ID de cliente, secreto de cliente, URL base y versión API.</li>
<li>Llame al método post_export para obtener el flujo resultante</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Requisitos del sistema" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

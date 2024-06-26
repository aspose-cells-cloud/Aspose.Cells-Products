---
title: Export WORKBOOK to MARKDOWN from Excel using Cells Cloud SDK for Perl  
description: Aspose.Cells Cloud REST API support exporting {0} to {1} format files using {2}. 
kwords: Excel, workbook, markdown, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to MARKDOWN","description": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to MARKDOWN","image": {"@type": "ImageObject"},"url": "/perl/export/workbook-to-markdown/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to MARKDOWN step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/workbook-to-markdown/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to MARKDOWN step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/workbook-to-markdown/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to MARKDOWN step 1", "image": {"@type": "ImageObject",},"url": "/perl/export/workbook-to-markdown/","text": "Call post_export method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Export WORKBOOK to MARKDOWN from Excel" h2="Perl library for exporting WORKBOOK to MARKDOWN file" p="Use Export API of Cells Cloud to export Excel file internal object workflows in Perl. This is a professional solution to export WORKBOOK to MARKDOWN format file from spreadsheet online using Perl." urlsection="export/workbook-to-markdown/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Export WORKBOOK object to MARKDOWN format file using Cells Cloud SDK for Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/export  apireferenceurl=https://apireference.aspose.cloud/cells/#/LightCells/PostExport  apimethod=POST %}}
<br/>
Export WORKBOOK object to MARKDOWN file from Excel file is a complex task. Export WORKBOOK to MARKDOWN format transitions is performed by our Perl SDK while maintaining the source WORKBOOK spreadsheet's main structural and logical content. Our Perl library is a professional solution to export WORKBOOK objects to MARKDOWN format files online. This Cloud SDK gives Perl developers powerful functionality and perfect MARKDOWN output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Code example in Perl using REST API to export WORKBOOK to MARKDOWN format from spreadsheet" gistPath="" %}}
  
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
    my $result = $instance->post_export(file => $filemap , object_type => 'workbook',format => 'markdown');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Cells Cloud SDK for Perl to export objects from Excel WORKBOOK to MARKDOWN" >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.</li>
<li>Call post_export method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

---
title: Save SXC as XLSM using Perl 
description: Utilizing Aspose.Cells Cloud SDK for Perl to save SXC format file as XLSM format file. 
kwords: Excel, Save SXC as XLSM, REST, Perl
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save SXC as XLSM using the Cells Cloud Perl library.","description": "How to save SXC as XLSM using the Cells Cloud Perl library.","image": {"@type": "ImageObject"},"url": "/perl/saveas/sxc-to-xlsm/","step": [{ "@type": "HowToStep","name": "How to save SXC as XLSM using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/sxc-to-xlsm/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save SXC as XLSM using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/sxc-to-xlsm/","text": "Install Perl library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save SXC as XLSM using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/sxc-to-xlsm/","text": "Open the source file in Perl.",},{ "@type": "HowToStep","name": "How to save SXC as XLSM using the Cells Cloud Perl library. step 1", "image": {"@type": "ImageObject",},"url": "/perl/saveas/sxc-to-xlsm/","text": "Call post_workbook_save_as method to get the resultant stream",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "VIM, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Save SXC as XLSM" h2="Perl library for saving SXC as XLSM" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Perl. This is a professional solution to save SXC as XLSM and other document formats online using Perl." urlsection="saveas/sxc-to-xlsm/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a SXC file as XLSM in Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from SXC as XLSM is a complex task. All SXC to XLSM format transitions is performed by our Perl SDK while maintaining the source SXC spreadsheet's main structural and logical content. Our Perl library is a professional solution to save SXC as XLSM files online. This Cloud SDK gives Perl developers powerful functionality and perfect XLSM output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Code Example for saving SXC as XLSM using REST API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.sxc';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.xlsm';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to save SXC as XLSM using the Cells Cloud Perl library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Perl library and add the reference (import the library) to your project.</li>
<li>Open the source file in Perl.</li>
<li>Call post_workbook_save_as method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

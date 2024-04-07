---
title: Save FODS as XLTM using Perl 
description: Utilizing Aspose.Cells Cloud SDK for Perl to save FODS format file as XLTM format file. 
kwords: Excel, Save FODS as XLTM, REST, Perl
howto: How to save FODS as XLTM using Aspose.Cells Cloud Perl library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save FODS as XLTM" h2="Perl library for saving FODS as XLTM" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Perl. This is a professional solution to save FODS as XLTM and other document formats online using Perl." urlsection="saveas/fods-to-xltm/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a FODS file as XLTM in Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from FODS as XLTM is a complex task. All FODS to XLTM format transitions is performed by our Perl SDK while maintaining the source FODS spreadsheet's main structural and logical content. Our Perl library is a professional solution to save FODS as XLTM files online. This Cloud SDK gives Perl developers powerful functionality and perfect XLTM output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Code Example for saving FODS as XLTM using REST API" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.fods';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.xltm';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to save FODS as XLTM using the Cells Cloud Perl library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Perl library and add the reference (import the library) to your project.</li>
<li>Open the source file in Perl.</li>
<li>Call post_workbook_save_as method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

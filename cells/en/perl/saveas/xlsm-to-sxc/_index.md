---
title: Save XLSM as SXC API for Perl 
description: Using Aspose.Cells Cloud SDK for Perl to save XLSM format file as SXC format file. 
url: /perl/saveas/xlsm-to-sxc/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API to save XLSM as SXC" h2="Perl library to save XLSM as SXC" p="Use Cells SaveAs REST API to create customized spreadsheet workflows in Perl. This is a professional solution to save XLSM as SXC and other document formats online using Perl." urlsection="saveas/xlsm-to-sxc/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Save a XLSM file as SXC in Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from XLSM as SXC is a complex task. All XLSM to SXC format transitions is performed by our Perl SDK while maintaining the source XLSM spreadsheet's main structural and logical content. Our Perl library is a professional solution to save XLSM as SXC files online. This Cloud SDK gives Perl developers powerful functionality and perfect SXC output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in Perl using REST API to save XLSM as SXC format" gistPath="" %}}
  
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $name = 'Book1.xlsm';
    my $save_options = undef;
    my $folder = 'CellsTests';
    my $newfilename = 'Book1Saveas.sxc';
    $result = $instance->cells_save_as_post_document_save_as(name => $name,save_options => $save_options, newfilename => $newfilename, folder => $folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Perl API to save  XLSM as SXC" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call cells_save_as_post_document_save_as method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

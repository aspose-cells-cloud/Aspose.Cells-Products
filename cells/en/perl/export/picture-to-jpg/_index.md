---
title: Export PICTURE to JPG from Excel using Cells Cloud SDK for Perl  
description: Aspose.Cells Cloud REST API support exporting {0} to {1} format files using {2}. 
kwords: 
howto: 
---


{{< blocks/products/cells/cells-cloud-banner h1="Export PICTURE to JPG from Excel" h2="Perl library for exporting PICTURE to JPG file" p="Use Export API of Cells Cloud to export Excel file internal object workflows in Perl. This is a professional solution to export PICTURE to JPG format file from spreadsheet online using Perl." urlsection="export/picture-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Export PICTURE object to JPG format file using Cells Cloud SDK for Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/export  apireferenceurl=https://apireference.aspose.cloud/cells/#/LightCells/PostExport  apimethod=POST %}}
<br/>
Export PICTURE object to JPG file from Excel file is a complex task. Export PICTURE to JPG format transitions is performed by our Perl SDK while maintaining the source PICTURE spreadsheet's main structural and logical content. Our Perl library is a professional solution to export PICTURE objects to JPG format files online. This Cloud SDK gives Perl developers powerful functionality and perfect JPG output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Code example in Perl using REST API to export PICTURE to JPG format from spreadsheet" gistPath="" %}}
  
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
    my $result = $instance->post_export(file => $filemap , object_type => 'picture',format => 'jpg');
    my $decoded = decode_base64($result->{'files'}[0]->{'file_content'});
    open(my $fh, '>',$result->{'files'}[0]->{'filename'}) or die "Could not open file!";
    binmode $fh;
    print $fh $decoded;
    close $fh;
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Cells Cloud SDK for Perl to export objects from Excel PICTURE to JPG" >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.</li>
<li>Call post_export method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

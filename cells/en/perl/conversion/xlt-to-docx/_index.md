---
title: XLT to DOCX Convert API for Perl 
description: Using Aspose.Cells Cloud SDK for Perl to convert XLT format file to DOCX format file. 
url: /perl/conversion/xlt-to-docx/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Perl API to convert XLT to DOCX" h2="Perl library to convert XLT to DOCX" p="Use Cells Conversion REST API to create customized spreadsheet workflows in Perl. This is a professional solution to convert XLT to DOCX and other document formats online using Perl." urlsection="conversion/xlt-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Convert a XLT file to DOCX in Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from XLT to DOCX is a complex task. All XLT to DOCX format transitions is performed by our Perl SDK while maintaining the source XLT spreadsheet's main structural and logical content. Our Perl library is a professional solution to convert XLT to DOCX files online. This Cloud SDK gives Perl developers powerful functionality and perfect DOCX output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in Perl using REST API to convert XLT to DOCX format" gistPath="" %}}
 
```perl
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    use strict;
    use warnings;
    use utf8; 
    use File::Slurp;
    use AsposeCellsCloud::CellsApi;
    my $config = AsposeCellsCloud::Configuration->new( client_id => $ENV{'ProductClientId'}, client_secret => $ENV{'ProductClientSecret'});
    my $instance = AsposeCellsCloud::CellsApi->new(AsposeCellsCloud::ApiClient->new( $config));
    my $format = "docx";
    my $Book1Data = undef;
    my $result =undef;
    my @fileinfos = stat("Book1.xlt");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.xlt") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.docx") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Perl API to convert  XLT to DOCX" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call cells_workbook_put_convert_workbook method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

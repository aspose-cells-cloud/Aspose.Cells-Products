---
title: Convert NUMBERS to DOCX using Perl 
description: Utilizing the Aspose.Cells Cloud SDK for Perl to convert a NUMBERS format file to a DOCX format file. 
kwords: Excel, Convert NUMBERS to DOCX, REST, Perl
howto: How to convert NUMBERS to DOCX using Aspose.Cells Cloud Perl library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert NUMBERS to DOCX" h2="Perl library for converting NUMBERS to DOCX" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Perl projects. This is a professional solution to convert NUMBERS to DOCX and other document formats online using Perl." urlsection="conversion/numbers-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert NUMBERS to DOCX using Cells Cloud SDK for Perl" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from NUMBERS to DOCX can be a complex task. Our Perl SDK handles all NUMBERS to DOCX format conversions while preserving the main structural and logical content of the source NUMBERS spreadsheet. Our Perl library provides a professional solution for converting NUMBERS to DOCX files online. This Cloud SDK empowers Perl developers with powerful functionality and ensures high-quality DOCX output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Perl Code Example for converting NUMBERS to DOCX using Cells Cloud SDK" gistPath="" %}}
 
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
    my @fileinfos = stat("Book1.numbers");
    my $filelength = $fileinfos[7];
    open(DATA, '<', "Book1.numbers") or die "file can not open, $!";
    binmode(DATA);
    read (DATA, $Book1Data, $filelength);
    close (DATA); 
    $result = $instance->cells_workbook_put_convert_workbook(workbook => $Book1Data, format => $format);
    open(my $fh, '>', "Dest.docx") or die "Could not open file!";
    binmode $fh;
    print $fh $result;
    close $fh;
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to convert NUMBERS to DOCX using the Cells Cloud Perl library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Perl package and add the reference (import the library) to your project.</li>
<li>Open the source file in Perl.</li>
<li>Use the `put_convert_workbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Perl 5</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

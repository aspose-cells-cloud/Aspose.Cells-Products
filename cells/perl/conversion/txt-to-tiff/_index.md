---
title: Convert TXT to TIFF via Perl
description: Create, Edit or Convert Excel files with Cloud API & Open Source .NET SDK
url: /perl/conversion/txt-to-tiff/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert TXT to  TIFF in the Cloud" h2="Excel & OpenOffice spreadsheet conversion with open source Cloud SDK for Perl">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="TXT to TIFF Conversion in Cloud SDK for Perl " %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```CellsApi``` with Client Id, Client Secret, Base URL & API version
1. Call ```CellsApi.CellsWorkbookPutConvertWorkbook``` method to get the resultant TIFF stream
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel REST API" %}}
Get Excel Cloud SDK for .NET source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl) to compile the SDK yourself or head to the [Releases](https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/releases) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Perl Code for TXT to TIFF Conversion" gistPath="" %}}
```perl
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-perl/
    my $client = AsposeCellsCloud::ApiClient->new( 
        AsposeCellsCloud::Configuration->new('base_url' =>'https://api.aspose.cloud/',
        'api_version' => 'v3.0', client_id => $ENV{'ProductClientId'}, 
        client_secret =>  $ENV{'ProductClientSecret'}));
    my $api = AsposeCellsCloud::CellsApi->new($client);
    my $format = 'tiff'; # replace NULL with a proper value
    my $password = undef; # replace NULL with a proper value
    my $out_path = undef; # replace NULL with a proper value
    my $Book1_data =undef;
    my @fileinfos = stat(get_path(file=>"Book1.txt"));
    my $filelength = $fileinfos[7];
    open(DATA, "<".get_path(file=>"Book1.txt")) or die "file.txt  can not open, $!";
    binmode(DATA);
    read (DATA, $Book1_data, $filelength);
    close (DATA);    
    my $folder = $TEMPFOLDER; # replace NULL with a proper value
    $result = $api->cells_workbook_put_convert_workbook( workbook => $Book1_data, format => $format, password => $password, out_path => $out_path,folder =>$folder);
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

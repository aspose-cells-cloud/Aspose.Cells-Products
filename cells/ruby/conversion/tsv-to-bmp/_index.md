---
title: Convert TSV to BMP via Ruby
description: Cloud APIs & SDKs for Microsoft Excel & OpenOffice Calc. Create, Edit, Render or Convert spreadsheet in the Cloud.
url: /ruby/conversion/tsv-to-bmp/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert TSV to  BMP in the Cloud" h2="Excel & OpenOffice spreadsheet conversion with open source Cloud SDK for Ruby">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="TSV to BMP Conversion in Cloud SDK for Ruby " %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```CellsApi``` with Client Id, Client Secret, Base URL & API version
1. Call ```cells_workbook_put_convert_workbook``` method to get the resultant BMP stream
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel REST API" %}}
Get Excel Cloud SDK for .NET source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby) to compile the SDK yourself or head to the [Releases](https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/releases) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Ruby Code for TSV to BMP Conversion" gistPath="" %}}
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
    it "should work" do
        @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
        name = "BOOK1.tsv"
        format = 'bmp'
        @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
    end
    end
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{% blocks/products/cells/cells-cloud-api-run-conversion  inputformat=tsv  outputformat=bmp  %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

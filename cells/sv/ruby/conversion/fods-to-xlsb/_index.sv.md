---
title:  Konvertera från Excel FODS till XLSB via Ruby
description: Skapa, redigera eller konvertera Excel-filer med REST API & Open Source Ruby SDK
url: /sv/ruby/conversion/fods-to-xlsb/
family: cells
platformtag: ruby
feature: conversion
informat: FODS
outformat: XLSB
platform: Ruby
otherformats: XLTM XLSX MHTML XPS TXT DIF TSV XLSM ODS MD SVG CSV PDF XLTX FODS XLSB 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Konvertera FODS till XLSB med Ruby" h2="Läs, redigera och exportera Excel data till andra format med open source Cloud SDK för Ruby" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="FODS till XLSB Konvertering med Ruby" %}}
1.  Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation
1. Initiera ```CellsApi``` med klient-id, klienthemlighet, basadress och API-version
1. Ladda upp FODS-fil till standardmolnlagring med metoden ```CellsApi.upload_file```
1. Ring ```CellsApi.cells_save_as_post_document_save_as```-metoden för att få den resulterande XLSB-filen
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Kom igång med Excel API & Ruby SDK" %}}
Få Excel Cloud SDK för Ruby källkod från[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby) för att kompilera SDK själv eller gå till[Släpps](https://releases.aspose.cloud/) för alternativa nedladdningsalternativ.

 Ta också en titt på Swagger-baserad[API Referens](https://apireference.aspose.cloud/cells/) att veta mer om[Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Ruby-kod för FODS till XLSB-konvertering" gistPath="" %}}
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby

require 'aspose_cells_cloud'

class Workbook
  include AsposeCellsCloud
  def initialize
    @instance =  AsposeCellsCloud::CellsApi.new($client_id, $client_secret, $api_version, $baseurl) 
  end
  
  # Convert document and save result to storage
  def post_document_save_as
    name = $BOOK1
    save_options = nil
    newfilename = 'output.xlsb'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = $TEMPFOLDER
    result = @instance.upload_file( folder + "/" + name, ::File.open(File.expand_path("data/" + name), "r") {|io| io.read(io.size) })
    expect(result.uploaded.size).to  be > 0
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder + "/" + newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
  end
end

workbook = Workbook.new()
puts workbook.post_document_save_as
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
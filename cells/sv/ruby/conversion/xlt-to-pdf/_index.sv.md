﻿---
title:  XLT till PDF Konvertera API för Ruby
description:  Använder Aspose.Cells Cloud SDK för Ruby för att konvertera fil i XLT-format till fil i PDF-format.
url: /sv/ruby/conversion/xlt-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API för att konvertera XLT till PDF" h2="Ruby-bibliotek för att konvertera XLT till PDF" p="Använd Cells Conversion REST API för att skapa anpassade arbetsflöden för kalkylblad i Ruby. Detta är en professionell lösning för att konvertera XLT till PDF och andra dokumentformat online med Ruby." urlsection="conversion/xlt-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera en XLT-fil till PDF i Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från XLT till PDF är en komplex uppgift. Alla formatövergångar från XLT till PDF utförs av vår Ruby SDK samtidigt som det huvudsakliga strukturella och logiska innehållet i källbladets XLT-kalkylblad bibehålls. Vårt Ruby-bibliotek är en professionell lösning för att konvertera XLT till PDF-filer online. Denna Cloud SDK ger Ruby-utvecklare kraftfull funktionalitet och perfekt PDF-utgång.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i Ruby med REST API för att konvertera XLT till PDF-format" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xlt"
            format = 'pdf'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Ruby API för att konvertera XLT till PDF" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Ring celler_arbetsbok_sätta_konvertera_arbetsboksmetod för att få den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>ruby 2.5 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
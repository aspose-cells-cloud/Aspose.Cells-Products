---
title:  Konvertera PNG till JSON med Ruby
description:  Använda Aspose.Cells Cloud SDK för Ruby för att konvertera en fil i PNG-format till en fil i JSON-format.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertera PNG till JSON" h2="Ruby-bibliotek för att konvertera PNG till JSON" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Ruby-projekt. Detta är en professionell lösning för att konvertera PNG till JSON och andra dokumentformat online med Ruby." urlsection="conversion/png-to-json/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera PNG till JSON med Cells Cloud SDK för Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från PNG till JSON kan vara en komplex uppgift. Vår Ruby SDK hanterar alla PNG till JSON-formatkonverteringar samtidigt som det huvudsakliga strukturella och logiska innehållet i källarket PNG bevaras. Vårt Ruby-bibliotek tillhandahåller en professionell lösning för att konvertera PNG till JSON-filer online. Denna Cloud SDK ger Ruby-utvecklare kraftfull funktionalitet och säkerställer JSON-utdata av hög kvalitet.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Ruby Code Exempel för att konvertera PNG till JSON med Cells Cloud SDK" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.png"
            format = 'json'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Cells Cloud SDK för Ruby för att konvertera Excel-filer till andra format PNG till JSON" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Använd metoden `put_convert_workbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>ruby 2.5 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

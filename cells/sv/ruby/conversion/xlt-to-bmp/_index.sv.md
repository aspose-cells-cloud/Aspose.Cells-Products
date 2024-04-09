---
title: Konvertera XLT till BMP med Ruby
description:  Använda Aspose.Cells Cloud SDK för Ruby för att konvertera en fil i XLT-format till en fil i BMP-format.
kwords: Excel, Convert XLT to BMP, REST, Ruby
howto: How to convert XLT to BMP using Aspose.Cells Cloud Ruby library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera XLT till BMP" h2="Ruby-bibliotek för att konvertera XLT till BMP" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Ruby-projekt. Detta är en professionell lösning för att konvertera XLT till BMP och andra dokumentformat online med Ruby." urlsection="conversion/xlt-to-bmp/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera XLT till BMP med Cells Cloud SDK för Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från XLT till BMP kan vara en komplicerad uppgift. Vår Ruby SDK hanterar alla XLT- till BMP-formatkonverteringar samtidigt som det huvudsakliga strukturella och logiska innehållet i käll-XLT-kalkylarket bevaras. Vårt Ruby-bibliotek tillhandahåller en professionell lösning för att konvertera XLT till BMP-filer online. Denna Cloud SDK ger Ruby-utvecklare kraftfull funktionalitet och säkerställer högkvalitativa BMP-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Ruby Code Exempel för att konvertera XLT till BMP med Cells Cloud SDK" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xlt"
            format = 'bmp'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Lär dig hur du konverterar XLT till BMP med hjälp av Cells Cloud Ruby-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera Ruby-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i Ruby.</li>
<li>Använd metoden `put_convert_workbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>ruby 2.5 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

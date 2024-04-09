---
title:  Konvertera XLT till XLS med C#
description:  Använda Aspose.Cells Cloud SDK för C# för att konvertera en fil i XLT-format till en fil i XLS-format.
kwords: Excel, Convert XLT to XLS, REST, C#
howto: How to convert XLT to XLS using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera XLT till XLS" h2="C# bibliotek för att konvertera XLT till XLS" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Net-projekt. Detta är en professionell lösning för att konvertera XLT till XLS och andra dokumentformat online med C#." urlsection="conversion/xlt-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera XLT till XLS med Cells Cloud SDK för C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från XLT till XLS kan vara en komplicerad uppgift. Vår C# SDK hanterar alla konverteringar av XLT till XLS-format samtidigt som det huvudsakliga strukturella och logiska innehållet i källbladets XLT-kalkylblad bevaras. Vårt C#-bibliotek erbjuder en professionell lösning för att konvertera XLT- till XLS-filer online. Denna Cloud SDK ger C# utvecklare kraftfull funktionalitet och säkerställer högkvalitativ XLS-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Kodexempel för att konvertera XLT till XLS med Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xlt";
    string format = "xls";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.xls";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Lär dig hur du konverterar XLT till XLS med hjälp av Cells Cloud Net-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera C#-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i C#</li>
<li>Använd metoden `PutConvertWorkbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>NET Framework 4.5.2 eller senare</li>
<li>Net Standard 2.0 eller senare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

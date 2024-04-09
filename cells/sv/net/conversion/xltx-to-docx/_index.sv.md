---
title:  Konvertera XLTX till DOCX med C#
description:  Använda Aspose.Cells Cloud SDK för C# för att konvertera en fil i XLTX-format till en fil i DOCX-format.
kwords: Excel, Convert XLTX to DOCX, REST, C#
howto: How to convert XLTX to DOCX using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera XLTX till DOCX" h2="C# bibliotek för att konvertera XLTX till DOCX" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Net-projekt. Detta är en professionell lösning för att konvertera XLTX till DOCX och andra dokumentformat online med C#." urlsection="conversion/xltx-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera XLTX till DOCX med Cells Cloud SDK för C#" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från XLTX till DOCX kan vara en komplex uppgift. Vår C# SDK hanterar alla XLTX- till DOCX-formatkonverteringar samtidigt som det huvudsakliga strukturella och logiska innehållet i källarket XLTX bevaras. Vårt C#-bibliotek tillhandahåller en professionell lösning för att konvertera XLTX till DOCX-filer online. Denna Cloud SDK ger C# utvecklare kraftfull funktionalitet och säkerställer DOCX-utdata av hög kvalitet.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# Kodexempel för att konvertera XLTX till DOCX med Cells Cloud SDK" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.xltx";
    string format = "docx";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.docx";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Lär dig hur du konverterar XLTX till DOCX med hjälp av Cells Cloud Net-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera C#-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i C#</li>
<li>Använd metoden `PutConvertWorkbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>NET Framework 4.5.2 eller senare</li>
<li>Net Standard 2.0 eller senare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

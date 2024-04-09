---
title:  Konvertera ODS till JPG med Python
description:  Använda Aspose.Cells Cloud SDK för Python för att konvertera en ODS-formatfil till en JPG-fil.
kwords: Excel, Convert ODS to JPG, REST, Python
howto: How to convert ODS to JPG using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera ODS till JPG" h2="Python bibliotek för att konvertera ODS till JPG" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Python projekt. Detta är en professionell lösning för att konvertera ODS till JPG och andra dokumentformat online med Python." urlsection="conversion/ods-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera ODS till JPG med Cells Cloud SDK för Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från ODS till JPG kan vara en komplicerad uppgift. Vår Python SDK hanterar alla ODS- till JPG-formatkonverteringar samtidigt som det huvudsakliga strukturella och logiska innehållet i källarket för ODS bevaras. Vårt Python-bibliotek tillhandahåller en professionell lösning för att konvertera ODS till JPG-filer online. Denna Cloud SDK ger Python utvecklare kraftfull funktionalitet och säkerställer högkvalitativa JPG-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Kodexempel för att konvertera ODS till JPG med Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.ods",format="jpg")
    shutil.move(file1, "destFile.jpg")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Lär dig hur du konverterar ODS till JPG med hjälp av Cells Cloud Python-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera Python-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i Python.</li>
<li>Använd metoden `put_convert_workbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Python 2.7 eller nyare</li>
<li>Python 3.10 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

---
title:  Konvertera XLSM till ODS med Python
description:  Använder Aspose.Cells Cloud SDK för Python för att konvertera en fil i XLSM-format till en fil i ODS-format.
kwords: Excel, Convert XLSM to ODS, REST, Python
howto: How to convert XLSM to ODS using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera XLSM till ODS" h2="Python bibliotek för att konvertera XLSM till ODS" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Python projekt. Detta är en professionell lösning för att konvertera XLSM till ODS och andra dokumentformat online med Python." urlsection="conversion/xlsm-to-ods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera XLSM till ODS med Cells Cloud SDK för Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från XLSM till ODS kan vara en komplex uppgift. Vår Python SDK hanterar alla XLSM- till ODS-formatkonverteringar samtidigt som det huvudsakliga strukturella och logiska innehållet i källarket XLSM bevaras. Vårt Python-bibliotek tillhandahåller en professionell lösning för att konvertera XLSM till ODS-filer online. Denna Cloud SDK ger Python utvecklare kraftfull funktionalitet och säkerställer högkvalitativa ODS-utdata.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Kodexempel för att konvertera XLSM till ODS med Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xlsm",format="ods")
    shutil.move(file1, "destFile.ods")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Lär dig hur du konverterar XLSM till ODS med hjälp av Cells Cloud Python-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera Python-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i Python.</li>
<li>Använd metoden `put_convert_workbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Python 2.7 eller nyare</li>
<li>Python 3.10 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

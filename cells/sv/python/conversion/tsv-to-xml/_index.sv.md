---
title:  Konvertera TSV till XML med Python
description:  Använda Aspose.Cells Cloud SDK för Python för att konvertera en fil i TSV-format till en fil i XML-format.
kwords: Excel, Convert TSV to XML, REST, Python
howto: How to convert TSV to XML using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Konvertera TSV till XML" h2="Python bibliotek för att konvertera TSV till XML" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Python projekt. Detta är en professionell lösning för att konvertera TSV till XML och andra dokumentformat online med Python." urlsection="conversion/tsv-to-xml/" >}}

{{< blocks/products/cells/cells-cloud-section title="Konvertera TSV till XML med Cells Cloud SDK för Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från TSV till XML kan vara en komplex uppgift. Vår Python SDK hanterar alla konverteringar av TSV till XML-format samtidigt som det huvudsakliga strukturella och logiska innehållet i käll-TSV-kalkylarket bevaras. Vårt Python-bibliotek tillhandahåller en professionell lösning för att konvertera TSV till XML-filer online. Denna Cloud SDK ger Python utvecklare kraftfull funktionalitet och säkerställer XML-utdata av hög kvalitet.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Kodexempel för att konvertera TSV till XML med Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.tsv",format="xml")
    shutil.move(file1, "destFile.xml")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Lär dig hur du konverterar TSV till XML med hjälp av Cells Cloud Python-biblioteket." >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Installera Python-biblioteket och lägg till referensen (importera biblioteket) till ditt projekt.</li>
<li>Öppna källfilen i Python.</li>
<li>Använd metoden `put_convert_workbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Python 2.7 eller nyare</li>
<li>Python 3.10 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

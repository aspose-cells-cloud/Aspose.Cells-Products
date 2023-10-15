---
title:  Konvertera XLS till DOCX med Python
description: Använda Aspose.Cells Cloud SDK för Python för att konvertera en fil i XLS-format till en fil i DOCX-format.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertera XLS till DOCX" h2="Python bibliotek för att konvertera XLS till DOCX" p="Använd Conversion API av av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Python projekt. Detta är en professionell lösning för att konvertera XLS till DOCX och andra dokumentformat online med Python." urlsection="conversion/xls-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera XLS till DOCX med Cells Cloud SDK för Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från XLS till DOCX kan vara en komplex uppgift. Vår Python SDK hanterar alla konverteringar av XLS till DOCX-format samtidigt som det huvudsakliga strukturella och logiska innehållet i källbladets XLS-kalkylblad bevaras. Vårt Python-bibliotek erbjuder en professionell lösning för att konvertera XLS till DOCX-filer online. Denna Cloud SDK ger Python utvecklare kraftfull funktionalitet och säkerställer DOCX-utdata av hög kvalitet.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Kodexempel för att konvertera XLS till DOCX med Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xls",format="docx")
    shutil.move(file1, "destFile.docx")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Cells Cloud SDK för Python för att konvertera Excel filer till andra format XLS till DOCX" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Använd metoden `put_convert_workbook` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Python 2.7 eller nyare</li>
<li>Python 3.10 eller nyare</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

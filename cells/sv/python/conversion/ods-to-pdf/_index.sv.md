﻿---
title:  ODS till PDF Konvertera API till Python
description:  Använder Aspose.Cells Cloud SDK för Python för att konvertera fil i ODS-format till fil i PDF-format.
url: /sv/python/conversion/ods-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API för att konvertera ODS till PDF" h2="Python bibliotek för att konvertera ODS till PDF" p="Använd Cells Conversion REST API för att skapa anpassade arbetsflöden för kalkylblad i Python. Detta är en professionell lösning för att konvertera ODS till PDF och andra dokumentformat online med Python." urlsection="conversion/ods-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Konvertera en ODS-fil till PDF i Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Att konvertera filformat från ODS till PDF är en komplex uppgift. Alla ODS till PDF formatövergångar utförs av vår Python SDK samtidigt som källkodens ODS-kalkylblads huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Python-bibliotek är en professionell lösning för att konvertera ODS till PDF-filer online. Denna Cloud SDK ger Python-utvecklare kraftfull funktionalitet och perfekt PDF-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i Python med REST API för att konvertera ODS till PDF-format" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.ods",format="pdf")
    shutil.move(file1, "destFile.pdf")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Python API för att konvertera ODS till PDF" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Ring celler_arbetsbok_sätta_konvertera_arbetsboksmetod för att få den resulterande strömmen</li>
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
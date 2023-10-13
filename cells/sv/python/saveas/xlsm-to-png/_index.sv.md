﻿---
title:  Spara XLSM som PNG API för Python
description:  Använder Aspose.Cells Cloud SDK för Python för att spara fil i XLSM-format som fil i PNG-format.
url: /sv/python/saveas/xlsm-to-png/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API för att spara XLSM som PNG" h2="Python bibliotek för att spara XLSM som PNG" p="Använd Cells SaveAs REST API för att skapa anpassade arbetsflöden för kalkylblad i Python. Detta är en professionell lösning för att spara XLSM som PNG och andra dokumentformat online med Python." urlsection="saveas/xlsm-to-png/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Spara en XLSM-fil som PNG i Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från XLSM som PNG är en komplex uppgift. Alla formatövergångar från XLSM till PNG utförs av vår Python SDK samtidigt som källbladets XLSM-kalkylblads huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Python-bibliotek är en professionell lösning för att spara XLSM som PNG-filer online. Denna Cloud SDK ger Python-utvecklare kraftfull funktionalitet och perfekt PNG-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i Python med REST API för att spara XLSM som PNG-format" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xlsm'    
    saveOptions = None
    newfilename = "Book1Saveas.png"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Python API för att spara XLSM som PNG" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Ring celler_spara_som_posta_dokumentera_spara_som metod för att få den resulterande strömmen</li>
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
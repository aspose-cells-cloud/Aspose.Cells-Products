---
title: Exportera Ods till XLSX-fil via Python
description: Aspose.Cells Cloud REST API stöder export av Excel-filer och interna objekt till olika formatfiler. SDK stöder olika utvecklingsspråk. De inkluderar Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby och swift.
url: /sv/python/export/ods-to-xlsx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Exportera ODS till XLSX-fil i molnet" h2="Excel & OpenOffice-kalkylbladsexport med open source Cloud SDK för Python" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=" Exoprera ODS till XLSX-fil i Cloud SDK för Python" %}}
1.  Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation
1. Initiera ```CellsApi``` med klient-id, klienthemlighet, basadress och API-version
1. Ring ```cells_workbook_put_convert_workbook```-metoden för att få den resulterande XLSX-strömmen
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Kom igång med Excel REST API" %}}
 Få Excel Cloud SDK for .NET källkod från[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-python) för att kompilera SDK själv eller gå till[Släpps](https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/releases) för alternativa nedladdningsalternativ.

 Ta också en titt på Swagger-baserad[API Referens]() att veta mer om[Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Python Kod för ODS till XLSX-konvertering" gistPath="" %}}
```python
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xlsx",format="xlsx")
    shutil.move(file1, "destFile.xlsx")     
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

﻿---
title:  Spara SXC som SQL API för Android
description: Använder Aspose.Cells Cloud SDK för Android för att spara SXC-formatfil som SQL-formatfil.
url: /sv/android/saveas/sxc-to-sql/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API för att spara SXC som SQL" h2="Android-bibliotek för att spara SXC som SQL" p="Använd Cells SaveAs REST API för att skapa anpassade kalkylbladsarbetsflöden i Android. Detta är en professionell lösning för att spara SXC som SQL och andra dokumentformat online med Android." urlsection="saveas/sxc-to-sql/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Spara en SXC-fil som SQL i Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från SXC som SQL är en komplex uppgift. Alla SXC- till SQL-formatövergångar utförs av vår Android SDK samtidigt som käll-SXC-kalkylarkets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Android-bibliotek är en professionell lösning för att spara SXC som SQL-filer online. Denna Cloud SDK ger Android-utvecklare kraftfull funktionalitet och perfekt SQL-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i Android med REST API för att spara SXC som SQL-format" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.sxc";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.sql";
    String folder ="CellsTests";
    try
    {
        CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
        cellsApi.cellsSaveAsPostDocumentSaveAs(name , saveOptions,newfilename,false,false,folder,null,null,null,true);                       
    }
    catch(Exception exception )
    {
        System.out.print(exception);
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Java API för att spara SXC som SQL" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Anrop cellsSaveAsPostDocumentSaveAs-metoden för att hämta den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Android 7 eller senare</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
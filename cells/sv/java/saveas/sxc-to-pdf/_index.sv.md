﻿---
title:  Spara SXC som PDF API for Java
description:  Använd Aspose.Cells Cloud SDK for Java för att spara SXC-formatfil som PDF-fil.
url: /sv/java/saveas/sxc-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API för att spara SXC som PDF" h2="Java bibliotek för att spara SXC som PDF" p="Använd Cells SaveAs REST API för att skapa anpassade arbetsflöden för kalkylblad i Java. Detta är en professionell lösning för att spara SXC som PDF och andra dokumentformat online med Java." urlsection="saveas/sxc-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Spara en SXC-fil som PDF i Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från SXC som PDF är en komplex uppgift. Alla SXC- till PDF-formatövergångar utförs av vår Java SDK samtidigt som käll-SXC-kalkylbladets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Java-bibliotek är en professionell lösning för att spara SXC som PDF-filer online. Denna Cloud SDK ger Java-utvecklare kraftfull funktionalitet och perfekt PDF-utdata.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Kodexempel i Java med REST API för att spara SXC som PDF-format" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.sxc";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.pdf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Java API för att spara SXC som PDF" >}}
<li> Skapa ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera CellsApi med klient-id, klienthemlighet, basadress och version API</li>
<li>Anrop cellsSaveAsPostDocumentSaveAs-metoden för att hämta den resulterande strömmen</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Maven 2.2.0 eller nyare</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
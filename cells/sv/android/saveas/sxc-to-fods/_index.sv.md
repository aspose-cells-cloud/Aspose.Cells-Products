﻿---
title:  Spara SXC som FODS med Android
description:  Använder Aspose.Cells Cloud SDK för Android för att spara SXC-formatfil som FODS-formatfil.
kwords: Excel, Save SXC as FODS, REST, Android
howto: How to save SXC as FODS using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Spara SXC som FODS" h2="Android-bibliotek för att spara SXC som FODS" p="Använd SaveAs API av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Android. Detta är en professionell lösning för att spara SXC som FODS och andra dokumentformat online med Android." urlsection="saveas/sxc-to-fods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Spara en SXC-fil som FODS i Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från SXC som FODS är en komplex uppgift. Alla SXC- till FODS-formatövergångar utförs av vår Android-SDK samtidigt som käll-SXC-kalkylarkets huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Android-bibliotek är en professionell lösning för att spara SXC som FODS-filer online. Denna Cloud SDK ger Android-utvecklare kraftfull funktionalitet och perfekt FODS-utgång.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Android-kodexempel för att spara SXC som FODS med REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.sxc";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.fods";
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
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Så här använder du Cells Cloud SDK för Android för att spara Excel-filer som andra format" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Använd metoden `postWorkbookSaveAs` för att hämta den resulterande strömmen.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Systemkrav" >}}
<li>Android 7 eller senare</li>
<li>Java(TM) SE Runtime Environment</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

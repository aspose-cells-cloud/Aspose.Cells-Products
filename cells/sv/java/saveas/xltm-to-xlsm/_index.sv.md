---
title:  Spara XLTM som XLSM med Java
description: Använder Aspose.Cells Cloud SDK for Java för att spara XLTM-formatfil som XLSM-formatfil.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Spara XLTM som XLSM" h2="Java bibliotek för att spara XLTM som XLSM" p="Använd SaveAs API av Cells Cloud för att skapa anpassade kalkylbladsarbetsflöden i Java. Detta är en professionell lösning för att spara XLTM som XLSM och andra dokumentformat online med Java." urlsection="saveas/xltm-to-xlsm/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Spara en XLTM-fil som XLSM i Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Att spara filformat från XLTM som XLSM är en komplex uppgift. Alla XLTM till XLSM-formatövergångar utförs av vår Java SDK samtidigt som källkodens XLTM-kalkylblads huvudsakliga strukturella och logiska innehåll bibehålls. Vårt Java-bibliotek är en professionell lösning för att spara XLTM som XLSM-filer online. Denna Cloud SDK ger Java utvecklare kraftfull funktionalitet och perfekt XLSM-utgång.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java Kod Exempel för att spara XLTM som XLSM med REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.xltm";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xlsm";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Hur man använder Cells Cloud SDK for Java för att spara Excel filer som andra format XLTM som XLSM" >}}
<li> Registrera ett konto på<a href="https://dashboard.aspose.cloud/">instrumentbräda</a> för att få gratis API kvot & auktoriseringsinformation</li>
<li>Initiera Cells API med ditt klient-ID, klienthemlighet, basadress och version API.</li>
<li>Använd metoden `postWorkbookSaveAs` för att hämta den resulterande strömmen.</li>
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

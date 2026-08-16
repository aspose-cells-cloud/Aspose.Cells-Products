---
title: Convertit une plage d'une feuille de calcul sur un lecteur local en fichier HTML.
description: Cette méthode lit un fichier de feuille de calcul depuis le système de fichiers local, convertit sa plage en fichier HTML souhaité et renvoie le résultat converti. \nLe chemin du fichier source et le format cible doivent être spécifiés correctement. \nAssurez-vous que les autorisations nécessaires sont en place pour lire le fichier source et écrire le fichier converti le cas échéant. \nLe processus de conversion s'effectue entièrement sur le serveur cloud, éliminant le besoin de tout stockage cloud ou téléchargement externe. \nSi le fichier source n'existe pas, est inaccessible, ou si une erreur survient durant le processus de conversion, une exception appropriée sera levée. \nLes formats pris en charge pour la conversion dépendent des bibliothèques disponibles et de leurs capacités.
kwords: aspose cells
url: /fr/java/convert-range-to-html/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Fonctionnalité Cells Cloud" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convertir des fichiers Excel en d'autres formats" indexdesc="Aspose.Cells Cloud offre un support robuste pour la conversion de formats de fichiers Excel, un processus connu pour sa complexité. Aspose.Cells Cloud prend en charge plus de 30 formats de fichiers, dont Excel, PDF, Markdown, JSON, XML, CSV, HTML, etc." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Fonctionnalités prises en charge" featuremsg="Aspose.Cells Cloud propose une API REST qui prend en charge la conversion de fichiers Excel vers divers formats et offre des SDK pour plusieurs langages de programmation. Ces langages comprennent .NET, Java, Go, NodeJS, Python, etc." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/range/html"  %}}

<!-- {{< blocks/products/cells/cells-cloud-run-conversion btName="RunCode" OutResultType="Variable" OutResultDataType="Stream" ResponseType="Stream" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/?urls.primaryName=API+v4#/Conversion/ConvertSpreadsheet" >}} -->
<!-- {{< blocks/products/cells/cells-cloud-upload>}} -->

<!-- {{< blocks/products/cells/cells-cloud-parameters itName="format"  required="False" prompt="The format to convert(CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers).">}} -->
<!-- {{< blocks/products/cells/cells-cloud-showparameters >}} -->
{{% blocks/products/cells/cells-cloud-showcode request="format,password,outPath,storageName,checkExcelRestriction,streamFormat,region,pageWideFitOnPerSheet,pageTallFitOnPerSheet" requestvalue="pdf,,,,true,,,true,true" %}}

```java
    package com.aspose.cloud.cells.api;
    import com.aspose.cloud.cells.api.CellsApi;
    import com.aspose.cloud.cells.request.*;
    public class ConvertSpreadsheetExample {
    public static void main(String[] args) {
        try {
            CellsApi api = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
            ConvertRangeToHtmlRequest request = new ConvertRangeToHtmlRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.setrange("A1:C10");
            api.ConvertRangeToHtml(request);
        } catch (ApiException e) {
            e.printStackTrace();
        }
    }
}
```

{{% /blocks/products/cells/cells-cloud-showcode %}}
<!-- {{< /blocks/products/cells/cells-cloud-run-conversion >}} -->



{{< blocks/products/cells/cells-cloud-available-sdks >}}





{{< /blocks/products/pf/main-container >}}


{{< blocks/products/cells/cells-cloud-resource-links >}}
{{< /blocks/products/pf/main-wrap-class >}}
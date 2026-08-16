---
title: Convertit un graphique de feuille de calcul sur un disque local en image.
description: Cette méthode lit un graphique d’un fichier de feuille de calcul depuis le système de fichiers local, le convertit au format d’image souhaité (par exemple : PNG, SVG, Tiff) et renvoie le résultat converti.\nLe chemin du fichier source et le format cible doivent être spécifiés correctement.\nAssurez‑vous que les autorisations nécessaires sont en place pour lire le fichier source et écrire le fichier converti le cas échéant.\nLe processus de conversion s’effectue entièrement sur le serveur cloud, éliminant ainsi le besoin de tout stockage cloud ou téléchargements externes.\nSi le fichier source n’existe pas, est inaccessible, ou si une erreur survient pendant le processus de conversion, une exception appropriée sera levée.\nLes formats pris en charge pour la conversion dépendent des bibliothèques disponibles et de leurs capacités.
kwords: aspose cells
url: /fr/java/convert-chart-to-image/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Fonctionnalité Cells Cloud" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convertir des fichiers Excel en d’autres formats" indexdesc="Aspose.Cells Cloud offre un support solide pour la conversion de formats de fichiers Excel, un processus réputé pour sa complexité. Aspose.Cells Cloud prend en charge plus de 30 formats de fichiers, y compris Excel, PDF, Markdown, JSON, XML, CSV, HTML, etc." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Fonctionnalités prises en charge" featuremsg="Aspose.Cells Cloud propose une API REST qui prend en charge la conversion de fichiers Excel vers divers formats et offre des SDK pour plusieurs langages de programmation. Ces langages comprennent .NET, Java, Go, Node.js, Python, etc." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/chart/image"  %}}

{{% blocks/products/cells/cells-cloud-showcode request="format,password,outPath,storageName,checkExcelRestriction,streamFormat,region,pageWideFitOnPerSheet,pageTallFitOnPerSheet" requestvalue="pdf,,,,true,,,true,true" %}}

```java
    package com.aspose.cloud.cells.api;
    import com.aspose.cloud.cells.api.CellsApi;
    import com.aspose.cloud.cells.request.*;
    public class ConvertSpreadsheetExample {
    public static void main(String[] args) {
        try {
            CellsApi api = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
            ConvertChartToImageRequest request = new ConvertChartToImageRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.setchartIndex(0);
            request.setformat("png");
            api.ConvertChartToImage(request);
        } catch (ApiException e) {
            e.printStackTrace();
        }
    }
}
```

{{% /blocks/products/cells/cells-cloud-showcode %}}



{{< blocks/products/cells/cells-cloud-available-sdks >}}





{{< /blocks/products/pf/main-container >}}


{{< blocks/products/cells/cells-cloud-resource-links >}}
{{< /blocks/products/pf/main-wrap-class >}}
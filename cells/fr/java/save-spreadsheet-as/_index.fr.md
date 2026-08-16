---
title: Convertit une feuille de calcul dans le stockage cloud au format spécifié.
description: Cette méthode accède directement à un fichier de feuille de calcul depuis le stockage cloud, le convertit au format de sortie souhaité (par exemple, XLSX, PDF, CSV) et renvoie le résultat converti sans télécharger le fichier sur le système local. \nAssurez‑vous que la configuration du stockage cloud (telle que les informations d’identification d’accès et le chemin du fichier) est correctement définie. \nLe processus de conversion se déroule entièrement dans l’environnement cloud, minimisant le transfert de données et améliorant la sécurité en gardant les données sensibles au sein de l’infrastructure cloud. \nSi le fichier source n’existe pas, ou si une erreur survient durant le processus de conversion, une exception appropriée sera levée. \nLes formats de sortie pris en charge dépendent des capacités du service de conversion sous‑jacent.
kwords: aspose cells
url: /fr/net/save-spreadsheet-as/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convertir des fichiers Excel vers d’autres formats" indexdesc="Aspose.Cells Cloud offre une prise en charge robuste de la conversion de formats de fichiers Excel, un processus connu pour sa complexité. Aspose.Cells Cloud prend en charge plus de 30 formats de fichiers, y compris Excel, PDF, Markdown, JSON, XML, CSV, HTML, etc." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Fonctionnalités prises en charge" featuremsg="Aspose.Cells Cloud propose une API REST qui prend en charge la conversion de fichiers Excel vers divers formats et propose des SDK pour plusieurs langages de programmation. Ces langages de programmation incluent .NET, Java, Go, NodeJS, Python, etc." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/{name}/saveas"  %}}

<!-- {{< blocks/products/cells/cells-cloud-run-conversion btName="RunCode" OutResultType="Variable" OutResultDataType="Stream" ResponseType="Stream" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/?urls.primaryName=API+v4#/Conversion/ConvertSpreadsheet" >}} -->
<!-- {{< blocks/products/cells/cells-cloud-upload>}} -->

<!-- {{< blocks/products/cells/cells-cloud-parameters itName="format"  required="False" prompt="Le format à convertir (CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)." >}} -->
<!-- {{< blocks/products/cells/cells-cloud-showparameters >}} -->
{{% blocks/products/cells/cells-cloud-showcode request="format,password,outPath,storageName,checkExcelRestriction,streamFormat,region,pageWideFitOnPerSheet,pageTallFitOnPerSheet" requestvalue="pdf,,,,true,,,true,true" %}}


```java
    package com.aspose.cloud.cells.api;
    import com.aspose.cloud.cells.api.CellsApi;
    import com.aspose.cloud.cells.request.*;
    public class Example {
    public static void main(String[] args) {
        try {
            CellsApi api = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
            SaveSpreadsheetAsRequest request = new SaveSpreadsheetAsRequest();
            request.setname("EmployeeSalesSummary.xlsx");
            request.setformat("pdf");
            api.SaveSpreadsheetAs(request);
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
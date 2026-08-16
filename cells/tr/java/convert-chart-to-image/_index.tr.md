---
title: Yerel sürücünüzdeki bir elektronik tablo grafiğini görüntüye dönüştürür.
description: Bu yöntem, yerel dosya sisteminden bir elektronik tablo dosyasının grafiğini okur, istediğiniz görüntü formatına (örn., PNG, SVG, Tiff) dönüştürür ve dönüştürülmüş sonucu döndürür. \nKaynak dosya yolu ve hedef format doğru şekilde belirtilmelidir. \nGerekli izinlerin, kaynak dosyayı okuyabilmek ve gerekirse dönüştürülmüş dosyayı yazabilmek için mevcut olduğundan emin olun. \nDönüştürme işlemi tamamen bulut sunucusunda gerçekleşir ve herhangi bir bulut depolama ya da dış indirme ihtiyacını ortadan kaldırır. \nKaynak dosya mevcut değilse, erişilemezse veya dönüştürme sürecinde bir hata oluşursa, uygun bir istisna fırlatılacaktır. \nDönüştürme için desteklenen formatlar, mevcut kütüphanelere ve bu kütüphanelerin yeteneklerine bağlıdır.
kwords: aspose hücreler
url: /tr/java/convert-chart-to-image/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convert Excel files to other formats" indexdesc="Aspose.Cells Cloud provides robust support for Excel file format conversion, a process known for its intricacy. Aspose.Cells Cloud supports 30+ file formats, including Excel, Pdf, Markdown, Json, XML, Csv, Html, and so on.">}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Supported Features" featuremsg="Aspose.Cells Cloud provides REST API which supports converting Excel files to various format and offers SDKs for multiple programming languages. These programming languages are include of Net, Java, Go, NodeJS, Python, and so on. .">}}
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
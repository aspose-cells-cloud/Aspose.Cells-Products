---
title: Yerel sürücüdeki bir elektronik tablo grafiğini pdf'ye dönüştürür.
description: Bu yöntem, yerel dosya sisteminden bir elektronik tablo dosyasının grafiğini okur, istenen pdf formatına dönüştürür ve dönüştürülmüş sonucu döndürür. \nKaynak dosya yolu ve hedef format doğru şekilde belirtilmelidir. \nGerekli izinlerin, kaynak dosyayı okuma ve gerektiğinde dönüştürülmüş dosyayı yazma izni sağlayacak şekilde ayarlandığından emin olun. \nDönüştürme işlemi tamamen bulut sunucusunda gerçekleşir, herhangi bir bulut depolama veya dış indirme ihtiyacını ortadan kaldırır. \nKaynak dosya mevcut değilse, erişilemezse veya dönüşüm sırasında bir hata oluşursa uygun bir istisna fırlatılır. \nDönüştürme için desteklenen formatlar, mevcut kütüphanelere ve bunların yeteneklerine bağlıdır.
kwords: aspose hücreler
url: /tr/net/convert-chart-to-pdf/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Excel dosyalarını diğer formatlara dönüştürün" indexdesc="Aspose.Cells Cloud, karmaşıklığıyla bilinen Excel dosya formatı dönüşümüne kapsamlı destek sağlar. Aspose.Cells Cloud, Excel, Pdf, Markdown, Json, XML, Csv, Html ve daha fazlası dahil olmak üzere 30'dan fazla dosya formatını destekler." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Desteklenen Özellikler" featuremsg="Aspose.Cells Cloud, Excel dosyalarını çeşitli formatlara dönüştürmeyi destekleyen REST API sağlar ve birden fazla programlama dili için SDK'lar sunar. Bu programlama dilleri .NET, Java, Go, NodeJS, Python ve benzerlerini içerir." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/chart/pdf"  %}}

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
            ConvertChartToImageRequest request = new ConvertChartToImageRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.setchartIndex(0);
            api.ConvertChartToImage(request);
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
{{< blocks/products/pf/main-wrap-class >}}
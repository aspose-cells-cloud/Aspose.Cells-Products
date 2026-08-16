---
title: Yerel sürücüdeki bir hesap tablosunun tablosunu csv dosyasına dönüştürür.
description: Bu yöntem, yerel dosya sisteminden bir hesap tablosu dosyasını okur, tablosunu istenen csv dosyasına dönüştürür ve dönüştürülmüş sonucu döndürür. \nKaynak dosya yolu ve hedef format doğru bir şekilde belirtilmelidir. \nGerekli izinlerin, kaynak dosyayı okuma ve gerektiğinde dönüştürülmüş dosyayı yazma izni sağlandığından emin olun. \nDönüştürme işlemi tamamen bulut sunucusunda gerçekleşir, herhangi bir bulut depolama veya harici indirme ihtiyacını ortadan kaldırır. \nKaynak dosya mevcut değilse, erişilemezse veya dönüşüm işlemi sırasında bir hata oluşursa uygun bir istisna fırlatılır. \nDönüşüm için desteklenen formatlar, mevcut kütüphanelere ve bunların yeteneklerine bağlıdır.
kwords: aspose hücreleri
url: /tr/java/convert-table-to-csv/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Excel dosyalarını diğer formatlara dönüştür" indexdesc="Aspose.Cells Cloud, karmaşık olduğu bilinen Excel dosya formatı dönüşümü için güçlü destek sağlar. Aspose.Cells Cloud, Excel, Pdf, Markdown, Json, XML, Csv, Html ve daha fazlası dahil 30'dan fazla dosya formatını destekler." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Desteklenen Özellikler" featuremsg="Aspose.Cells Cloud, Excel dosyalarını çeşitli formatlara dönüştürmeyi destekleyen REST API sağlar ve birden fazla programlama dili için SDK'lar sunar. Bu programlama dilleri .NET, Java, Go, NodeJS, Python ve benzerlerini içerir." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/table/csv"  %}}

<!-- {{< blocks/products/cells/cells-cloud-run-conversion btName="RunCode" OutResultType="Variable" OutResultDataType="Stream" ResponseType="Stream" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/?urls.primaryName=API+v4#/Conversion/ConvertSpreadsheet" >}} -->
<!-- {{< blocks/products/cells/cells-cloud-upload>}} -->

<!-- {{< blocks/products/cells/cells-cloud-parameters itName="format"  required="False" prompt="The format to convert(CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers).">}} -->
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
            ConvertWorksheetToImageRequest request = new ConvertWorksheetToImageRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.settableName("table1");
            api.ConvertWorksheetToImage(request);
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
---
title: Yerel sürücüdeki bir elektronik tablonun belirli bir aralığını CSV dosyasına dönüştürür.
description: Bu yöntem, yerel dosya sisteminden bir elektronik tablo dosyasını okur, aralığını istenen CSV dosyasına dönüştürür ve dönüştürülmüş sonucu döndürür. Kaynak dosya yolu ve hedef format doğru şekilde belirtilmelidir. Gerekli izinlerin kaynak dosyayı okumak ve gerektiğinde dönüştürülen dosyayı yazmak için mevcut olduğundan emin olun. Dönüştürme işlemi tamamen bulut sunucusunda gerçekleşir, böylece herhangi bir bulut depolama veya dış indirme gerekmez. Kaynak dosya mevcut değilse, erişilemezse veya dönüşüm sürecinde bir hata oluşursa uygun bir istisna fırlatılır. Dönüştürme için desteklenen formatlar, mevcut kütüphanelere ve bunların yeteneklerine bağlıdır.
kwords: aspose cells
url: /tr/net/convert-range-to-csv/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Özelliği" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Excel dosyalarını diğer formatlara dönüştür" indexdesc="Aspose.Cells Cloud, karmaşık bir süreç olarak bilinen Excel dosya formatı dönüşümüne kapsamlı destek sağlar. Aspose.Cells Cloud, Excel, Pdf, Markdown, Json, XML, Csv, Html ve daha fazlası dahil olmak üzere 30+ dosya formatını destekler." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Desteklenen Özellikler" featuremsg="Aspose.Cells Cloud, Excel dosyalarını çeşitli formatlara dönüştürmeyi destekleyen REST API sağlar ve birden fazla programlama dili için SDK'lar sunar. Bu programlama dilleri arasında .NET, Java, Go, NodeJS, Python ve benzerleri bulunur." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/range/csv"  %}}

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
            ConvertRangeToCsvRequest request = new ConvertRangeToCsvRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.setcloud("A1:C10");
            api.ConvertRangeToCsv(request);
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
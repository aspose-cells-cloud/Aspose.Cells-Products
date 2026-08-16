---
title: Yerel sürücüdeki bir elektronik tablo aralığını görüntü dosyasına dönüştürür.
description: Bu yöntem, yerel dosya sisteminden bir elektronik tablo dosyasını okur, aralığını istenen görüntü dosyasına dönüştürür ve dönüştürülmüş sonucu döndürür. \nKaynak dosya yolu ve hedef format doğru şekilde belirtilmelidir. \nKaynak dosyayı okumak ve gerektiğinde dönüştürülmüş dosyayı yazmak için gerekli izinlerin bulunduğundan emin olun. \nDönüştürme süreci tamamen bulut sunucusunda gerçekleşir, böylece herhangi bir bulut depolama veya harici indirme ihtiyacı ortadan kalkar. \nKaynak dosya mevcut değilse, erişilemezse veya dönüştürme sürecinde bir hata oluşursa uygun bir istisna fırlatılır. \nDönüştürme için desteklenen formatlar, mevcut kütüphanelere ve bunların yeteneklerine bağlıdır.
kwords: aspose hücreleri
url: /tr/java/convert-table-to-json/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Excel dosyalarını diğer formatlara dönüştürün" indexdesc="Aspose.Cells Cloud, karmaşıklığıyla bilinen Excel dosya formatı dönüşümü için kapsamlı destek sağlar. Aspose.Cells Cloud, Excel, Pdf, Markdown, Json, XML, Csv, Html ve daha fazlası dahil olmak üzere 30'dan fazla dosya formatını destekler." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Desteklenen Özellikler" featuremsg="Aspose.Cells Cloud, Excel dosyalarını çeşitli formatlara dönüştüren REST API'si sağlar ve birden çok programlama dili için SDK'lar sunar. Bu programlama dilleri .NET, Java, Go, NodeJS, Python ve benzerlerini içerir." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/range/image"  %}}

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
            ConvertRangeToImageRequest request = new ConvertRangeToImageRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.setrange("A1:C10");
            request.setformat("png");
            api.ConvertRangeToImage(request);
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
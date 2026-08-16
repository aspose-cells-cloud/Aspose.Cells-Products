---
title: Yerel sürücüdeki bir elektronik tablonun tablosunu PDF dosyasına dönüştürür.
description: Bu yöntem, yerel dosya sisteminden bir elektronik tablo dosyasını okur, tablosunu istenen PDF dosyasına dönüştürür ve dönüştürülmüş sonucu döndürür.\nKaynak dosya yolu ve hedef format doğru şekilde belirtilmelidir.\nKaynak dosyayı okumak ve gerektiğinde dönüştürülmüş dosyayı yazmak için gerekli izinlerin mevcut olduğundan emin olun.\nDönüştürme işlemi tamamen bulut sunucusunda gerçekleşir, böylece herhangi bir bulut depolama veya harici indirme ihtiyacı ortadan kalkar.\nKaynak dosya mevcut değilse, erişilemezse veya dönüşüm sırasında bir hata oluşursa uygun bir istisna fırlatılacaktır.\nDönüştürme için desteklenen formatlar, mevcut kütüphanelere ve bunların yeteneklerine bağlıdır.
kwords: aspose hücreleri
url: /tr/java/convert-table-to-pdf/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Excel dosyalarını diğer formatlara dönüştürün" indexdesc="Aspose.Cells Cloud, karmaşık bir süreç olarak bilinen Excel dosya formatı dönüşümü için güçlü destek sağlar. Aspose.Cells Cloud, Excel, Pdf, Markdown, Json, XML, Csv, Html ve benzeri dahil olmak üzere 30+ dosya formatını destekler.">}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Supported Features" featuremsg="Aspose.Cells Cloud, Excel dosyalarını çeşitli formatlara dönüştürmeyi destekleyen REST API sağlar ve birden fazla programlama dili için SDK'lar sunar. Bu programlama dilleri .NET, Java, Go, NodeJS, Python ve benzerlerini içerir." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/table/pdf"  %}}

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
            ConvertTableToPdfRequest request = new ConvertTableToPdfRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.settableName("table1");
            api.ConvertTableToPdf(request);
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
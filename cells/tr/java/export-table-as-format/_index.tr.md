---
title: Bulut depolamadaki bir elektronik tablo tablosunu belirtilen formata dönüştürür.
description: Bu yöntem, bir elektronik tablo tablosunu doğrudan bulut depolamada işleyerek, dosyanın yerel makineye indirilmesini gerektirmeden, istenen çıkış formatına (PDF veya Görüntü formatı) dönüştürür.\nİşlem, geçerli bulut depolama kimlik bilgilerine ve erişilebilir bir dosya yolu veya tanımlayıcısına dayanır.\nDönüştürme uzaktan gerçekleştirilir, veri transferini azaltır ve büyük dosyalar için performansı artırır.\nKaynak dosya bulunamazsa, erişim reddedilirse veya dönüştürme sırasında bir hata oluşursa, uygun bir istisna fırlatılacaktır.\nDesteklenen çıkış formatları, temel bulut dönüşüm hizmetinin yeteneklerine göre belirlenir.
kwords: aspose hücreler
url: /tr/java/export-table-as-format/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Excel dosyalarını diğer formatlara dönüştürme" indexdesc="Aspose.Cells Cloud, karmaşıklığıyla bilinen Excel dosya formatı dönüşümü için güçlü bir destek sağlar. Aspose.Cells Cloud, Excel, Pdf, Markdown, Json, XML, Csv, Html ve daha fazlası dahil olmak üzere 30'dan fazla dosya formatını destekler." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Desteklenen Özellikler" featuremsg="Aspose.Cells Cloud, Excel dosyalarını çeşitli formatlara dönüştürmeyi destekleyen bir REST API sağlar ve birden çok programlama dili için SDK'lar sunar. Bu programlama dilleri .NET, Java, Go, NodeJS, Python ve benzerlerini içerir." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="GET"  apiurl="/cells/{name}/worksheets/{worksheet}/tables/{tableName}"  %}}

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
            ExportTableAsFormatRequest request = new ExportTableAsFormatRequest();
            request.setname("EmployeeSalesSummary.xlsx");
            request.setformat("pdf");
            api.ExportTableAsFormat(request);
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
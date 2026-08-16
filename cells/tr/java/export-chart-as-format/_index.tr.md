---
title: Bulut depolamadaki bir e-tablo grafiğini belirtilen formata dönüştürür.
description: Bu yöntem, bir e-tablo grafiğini doğrudan bulut depolamada işleyerek, dosyanın yerel makineye indirilmesini gerektirmeden istenen çıktı formatına (PDF veya Görüntü formatı) dönüştürür. \nİşlem, geçerli bulut depolama kimlik bilgilerine ve erişilebilir bir dosya yoluna veya tanımlayıcısına dayanır. \nDönüştürme uzaktan gerçekleştirilir, veri transferini azaltır ve büyük dosyalar için performansı iyileştirir. \nKaynak dosya bulunamazsa, erişim reddedilirse veya dönüştürme sırasında bir hata oluşursa uygun bir istisna fırlatılır. \nDesteklenen çıktı formatları, temel bulut dönüştürme hizmetinin yetenekleriyle belirlenir.
kwords: aspose hücreleri
url: /tr/java/export-chart-as-format/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Excel dosyalarını diğer formatlara dönüştür" indexdesc="Aspose.Cells Cloud, karmaşıklığıyla bilinen Excel dosya formatı dönüşümüne sağlam destek sunar. Aspose.Cells Cloud, Excel, Pdf, Markdown, Json, XML, Csv, Html ve benzeri dahil olmak üzere 30+ dosya formatını destekler." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Desteklenen Özellikler" featuremsg="Aspose.Cells Cloud, Excel dosyalarını çeşitli formatlara dönüştürmeyi destekleyen bir REST API sağlar ve birçok programlama dili için SDK'lar sunar. Bu programlama dilleri .Net, Java, Go, NodeJS, Python ve benzeri dilleri içerir." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="GET"  apiurl="https://api.aspose.cloud/v4.0/cells/{name}/worksheets/{worksheet}/charts/{chartIndex}"  %}}

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
            ExportChartAsFormatRequest request = new ExportChartAsFormatRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setformat("pdf");
            api.ExportChartAsFormat(request);
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
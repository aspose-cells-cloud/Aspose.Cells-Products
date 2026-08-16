---
title: Конвертирует лист электронных таблиц на локальном диске в PDF‑файл.
description: Этот метод читает файл электронных таблиц из локальной файловой системы, конвертирует его лист в требуемый PDF‑файл и возвращает результат конвертации. \nПуть к исходному файлу и целевой формат должны быть указаны корректно. \nУбедитесь, что доступны необходимые разрешения для чтения исходного файла и записи конвертированного файла, если это применимо. \nПроцесс конвертации происходит полностью на облачном сервере, что исключает необходимость использования облачного хранилища или внешних загрузок. \nЕсли исходный файл не существует, недоступен, или произошла ошибка во время процесса конвертации, будет выброшено соответствующее исключение. \nПоддерживаемые форматы конвертации зависят от доступных библиотек и их возможностей.
kwords: aspose cells
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Преобразование файлов Excel в другие форматы" indexdesc="Aspose.Cells Cloud обеспечивает надёжную поддержку конвертации форматов файлов Excel, процесс которой известен своей сложностью. Aspose.Cells Cloud поддерживает более 30 форматов файлов, включая Excel, PDF, Markdown, JSON, XML, CSV, HTML и др." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Поддерживаемые функции" featuremsg="Aspose.Cells Cloud предоставляет REST API, который поддерживает конвертацию файлов Excel в различные форматы и предлагает SDK для нескольких языков программирования. Эти языки включают .NET, Java, Go, NodeJS, Python и др." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/worksheet/pdf"  %}}

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
            ConvertWorksheetToPdfRequest request = new ConvertWorksheetToPdfRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            api.ConvertWorksheetToPdf(request);
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
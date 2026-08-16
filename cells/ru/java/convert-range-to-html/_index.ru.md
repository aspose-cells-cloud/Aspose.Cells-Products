---
title: Преобразует диапазон электронных таблиц на локальном диске в HTML‑файл.
description: Этот метод читает файл электронной таблицы из локальной файловой системы, преобразует его диапазон в требуемый HTML‑файл и возвращает результат преобразования. \nПуть к исходному файлу и целевой формат должны быть указаны корректно. \nУбедитесь, что имеются необходимые разрешения для чтения исходного файла и, при необходимости, записи преобразованного файла. \nПроцесс конвертации происходит полностью на облачном сервере, устраняя необходимость в облачном хранилище или внешних загрузках. \nЕсли исходный файл не существует, недоступен, или во время процесса конвертации произошла ошибка, будет выброшено соответствующее исключение. \nПоддерживаемые форматы конвертации зависят от доступных библиотек и их возможностей.
kwords: aspose cells
url: /ru/java/convert-range-to-html/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Функция Cells Cloud" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Преобразование файлов Excel в другие форматы" indexdesc="Aspose.Cells Cloud обеспечивает надёжную поддержку конвертации формата файлов Excel, процесс, известный своей сложностью. Aspose.Cells Cloud поддерживает более 30 форматов файлов, включая Excel, PDF, Markdown, JSON, XML, CSV, HTML и другие." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Поддерживаемые функции" featuremsg="Aspose.Cells Cloud предоставляет REST API, поддерживающий конвертацию файлов Excel в различные форматы, и предлагает SDK для нескольких языков программирования. Эти языки включают .NET, Java, Go, NodeJS, Python и другие." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/range/html"  %}}

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
            ConvertRangeToHtmlRequest request = new ConvertRangeToHtmlRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.setrange("A1:C10");
            api.ConvertRangeToHtml(request);
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
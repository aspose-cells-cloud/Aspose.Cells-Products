---
title: Преобразует диапазон электронной таблицы в облачном хранилище в указанный формат.
description: Этот метод обрабатывает диапазон электронной таблицы непосредственно в облачном хранилище, преобразуя его в запрашиваемый формат вывода (PDF или формат изображения) без необходимости загрузки файла на локальный компьютер.\nОперация опирается на действительные учетные данные облачного хранилища и доступный путь к файлу или его идентификатор.\nПреобразование выполняется удаленно, снижая передачу данных и улучшая производительность при работе с большими файлами.\nЕсли исходный файл не найден, доступ запрещен или во время преобразования произошла ошибка, будет выброшено соответствующее исключение.\nПоддерживаемые форматы вывода определяются возможностями подлежащего облачного сервиса преобразования.
kwords: aspose cells
url: /ru/java/export-range-as-format/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Преобразование файлов Excel в другие форматы" indexdesc="Aspose.Cells Cloud обеспечивает надежную поддержку конвертации файлов Excel, процесс которой известен своей сложностью. Aspose.Cells Cloud поддерживает более 30 форматов файлов, включая Excel, PDF, Markdown, JSON, XML, CSV, HTML и др." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Поддерживаемые функции" featuremsg="Aspose.Cells Cloud предоставляет REST API, который поддерживает конвертацию файлов Excel в различные форматы и предлагает SDK для нескольких языков программирования. Эти языки включают .NET, Java, Go, NodeJS, Python и др." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="GET"  apiurl="/cells/{name}/worksheets/{worksheet}/ranges/{range}"  %}}

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
            ExportRangeAsFormatRequest request = new ExportRangeAsFormatRequest();
            request.setname("EmployeeSalesSummary.xlsx");
            request.setformat("pdf");
            api.ExportRangeAsFormat(request);
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
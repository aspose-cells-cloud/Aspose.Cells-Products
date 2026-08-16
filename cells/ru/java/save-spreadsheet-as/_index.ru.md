---
title: Преобразует электронную таблицу в облачном хранилище в указанный формат.
description: Этот метод получает файл электронной таблицы напрямую из облачного хранилища, преобразует его в требуемый выходной формат (например, XLSX, PDF, CSV) и возвращает результат конвертации без загрузки файла на локальную систему. \nУбедитесь, что конфигурация облачного хранилища (например, учетные данные доступа и путь к файлу) настроена правильно. \nПроцесс конвертации происходит полностью в облачной среде, что минимизирует нагрузку передачи данных и повышает безопасность, сохраняя конфиденциальные данные внутри облачной инфраструктуры. \nЕсли исходный файл не существует или во время процесса конвертации произошла ошибка, будет выброшено соответствующее исключение. \nПоддерживаемые форматы вывода зависят от возможностей базового сервиса конвертации.
kwords: aspose cells
url: /ru/net/save-spreadsheet-as/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Convert Excel files to other formats" indexdesc="Aspose.Cells Cloud предоставляет надежную поддержку преобразования файлов Excel, процесс, известный своей сложностью. Aspose.Cells Cloud поддерживает более 30 форматов файлов, включая Excel, Pdf, Markdown, Json, XML, Csv, Html и т.д." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Supported Features" featuremsg="Aspose.Cells Cloud предоставляет REST API, который поддерживает конвертацию файлов Excel в различные форматы и предлагает SDK для нескольких языков программирования. Эти языки программирования включают .NET, Java, Go, NodeJS, Python и т.д." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/{name}/saveas"  %}}

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
            SaveSpreadsheetAsRequest request = new SaveSpreadsheetAsRequest();
            request.setname("EmployeeSalesSummary.xlsx");
            request.setformat("pdf");
            api.SaveSpreadsheetAs(request);
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
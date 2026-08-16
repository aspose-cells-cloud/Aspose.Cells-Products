---
title: Конвертирует диаграмму электронной таблицы на локальном диске в изображение.
description: Этот метод считывает диаграмму файла электронной таблицы из локальной файловой системы, преобразует её в требуемый формат изображения (например, PNG, SVG, Tiff) и возвращает результат конвертации.\nПуть к исходному файлу и целевой формат должны быть указаны правильно.\nУбедитесь, что имеются необходимые разрешения для чтения исходного файла и записи преобразованного файла, если это применимо.\nПроцесс конвертации происходит полностью на облачном сервере, исключая необходимость в облачном хранилище или внешних загрузках.\nЕсли исходный файл не существует, недоступен или происходит ошибка во время процесса конвертации, будет выброшено соответствующее исключение.\nПоддерживаемые форматы конвертации зависят от доступных библиотек и их возможностей.
kwords: aspose cells
url: /ru/java/convert-chart-to-image/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Функция Cells Cloud" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Преобразовать файлы Excel в другие форматы" indexdesc="Aspose.Cells Cloud обеспечивает надежную поддержку конвертации форматов файлов Excel, процесс, известный своей сложностью. Aspose.Cells Cloud поддерживает более 30 форматов файлов, включая Excel, PDF, Markdown, JSON, XML, CSV, HTML и т.д." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Поддерживаемые функции" featuremsg="Aspose.Cells Cloud предоставляет REST API, который поддерживает преобразование файлов Excel в различные форматы и предлагает SDK для нескольких языков программирования. Эти языки программирования включают .NET, Java, Go, NodeJS, Python и т.д." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT"  apiurl="/cells/convert/chart/image"  %}}

{{% blocks/products/cells/cells-cloud-showcode request="format,password,outPath,storageName,checkExcelRestriction,streamFormat,region,pageWideFitOnPerSheet,pageTallFitOnPerSheet" requestvalue="pdf,,,,true,,,true,true" %}}

```java
    package com.aspose.cloud.cells.api;
    import com.aspose.cloud.cells.api.CellsApi;
    import com.aspose.cloud.cells.request.*;
    public class ConvertSpreadsheetExample {
    public static void main(String[] args) {
        try {
            CellsApi api = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
            ConvertChartToImageRequest request = new ConvertChartToImageRequest();
            request.setSpreadsheet("EmployeeSalesSummary.xlsx");
            request.setworksheet("Sheet1");
            request.setchartIndex(0);
            request.setformat("png");
            api.ConvertChartToImage(request);
        } catch (ApiException e) {
            e.printStackTrace();
        }
    }
}
```

{{% /blocks/products/cells/cells-cloud-showcode %}}



{{< blocks/products/cells/cells-cloud-available-sdks >}}





{{< /blocks/products/pf/main-container >}}


{{< blocks/products/cells/cells-cloud-resource-links >}}
{{< /blocks/products/pf/main-wrap-class >}}
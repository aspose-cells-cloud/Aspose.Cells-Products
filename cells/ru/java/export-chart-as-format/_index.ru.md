---
title: Преобразует диаграмму электронной таблицы в облачном хранилище в указанный формат.
description: Этот метод обрабатывает диаграмму электронной таблицы непосредственно в облачном хранилище, преобразуя её в требуемый формат вывода (PDF или формат изображения) без необходимости загрузки файла на локальный компьютер.\nОперация опирается на действительные учетные данные облачного хранилища и доступный путь к файлу или его идентификатор.\nКонверсия выполняется удалённо, снижая объём передачи данных и повышая производительность при работе с большими файлами.\nЕсли исходный файл не найден, доступ запрещён или во время конвертации происходит ошибка, будет выброшено соответствующее исключение.\nПоддерживаемые форматы вывода определяются возможностями базового облачного сервиса конвертации.
kwords: aspose cells
url: /ru/java/export-chart-as-format/
---
{{< blocks/products/pf/main-wrap-class >}}


{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Функция Cells Cloud" >}}

{{< blocks/products/cells/cells-cloud-languageindex indextitle="Преобразование файлов Excel в другие форматы" indexdesc="Aspose.Cells Cloud предоставляет надежную поддержку конвертации файлов Excel, процесс которой известен своей сложностью. Aspose.Cells Cloud поддерживает более 30 форматов файлов, включая Excel, PDF, Markdown, JSON, XML, CSV, HTML и т.д." >}}
    {{< blocks/products/cells/cells-cloud-languageindex-msg feature="Поддерживаемые функции" featuremsg="Aspose.Cells Cloud предоставляет REST API, который поддерживает конвертацию файлов Excel в различные форматы и предлагает SDK для множества языков программирования. Эти языки включают .NET, Java, Go, NodeJS, Python и т.д." >}}
{{< /blocks/products/cells/cells-cloud-languageindex >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="GET"  apiurl="https://api.aspose.cloud/v4.0/cells/{name}/worksheets/{worksheet}/charts/{chartIndex}"  %}}

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

{{< blocks/products/cells/cells-cloud-available-sdks >}}

{{< /blocks/products/pf/main-container >}}


{{< blocks/products/cells/cells-cloud-resource-links >}}
{{< /blocks/products/pf/main-wrap-class >}}
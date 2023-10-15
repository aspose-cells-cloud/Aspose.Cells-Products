---
title: Экспорт коэффициентов в файл XLSX via Python
description: Aspose.Cells Cloud REST API поддерживает экспорт Excel файлов и внутренних объектов в различные форматы файлов. SDK поддерживает различные языки разработки. К ним относятся Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby и Swift.
url: /ru/python/export/ods-to-xlsx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Экспорт ODS в файл XLSX в облаке" h2="Excel и экспорт таблиц OpenOffice с помощью Cloud SDK с открытым исходным кодом для Python" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=" Преобразовать ODS в файл XLSX в Cloud SDK для Python." %}}
1.  Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API
1. Инициализируйте ```CellsApi```, используя идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.
1. Вызовите метод ```cells_workbook_put_convert_workbook```, чтобы получить результирующий поток XLSX.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начните с Excel REST API" %}}
 Получите исходный код Excel Cloud SDK for .NET с сайта[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-python) скомпилировать SDK самостоятельно или перейти к[Релизы](https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/releases) альтернативные варианты загрузки.

 Также взгляните на Swagger на основе[API Ссылка]() чтобы узнать больше о[Excel ОТДЫХ API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Python Код для преобразования ODS в XLSX" gistPath="" %}}
```python
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xlsx",format="xlsx")
    shutil.move(file1, "destFile.xlsx")     
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

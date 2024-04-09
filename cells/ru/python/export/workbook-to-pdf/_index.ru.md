---
title:  Экспортируйте WORKBOOK в PDF из Excel с помощью Cloud SDK Cells для Python.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Экспортировать РАБОЧУЮ КНИГУ на номер PDF из Excel." h2="Библиотека Python для экспорта WORKBOOK в файл PDF" p="Используйте экспорт API из Cells Cloud для экспорта рабочих процессов внутренних объектов файла Excel в Python. Это профессиональное решение для экспорта WORKBOOK в файл формата PDF из электронной таблицы онлайн с помощью Python." urlsection="export/workbook-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Экспортируйте объект WORKBOOK в файл формата PDF с помощью Cloud SDK Cells для Python." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта WORKBOOK в файл PDF из файла Excel — сложная задача. Экспорт WORKBOOK в формат переходов PDF выполняется нашим SDK Python с сохранением основного структурного и логического содержимого исходной таблицы WORKBOOK. Наша библиотека Python — это профессиональное решение для онлайн-экспорта объектов WORKBOOK в файлы формата PDF. Этот Cloud SDK предоставляет разработчикам Python мощные функциональные возможности и идеальный результат PDF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода в Python с использованием REST API для экспорта WORKBOOK в формат PDF из электронной таблицы" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import base64
    from asposecellscloud.apis.light_cells_api import LightCellsApi
    cells_api = LightCellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    files ={ 
        "myDocument.xlsx" :  "c:/myDocument.xlsx",
        "Book1.xlsx" :  "c:/Book1.xlsx" 
        }
    result = cells_api.post_export(files ,"workbook","pdf")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK для Python для экспорта объектов из Excel WORKBOOK в PDF" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Вызовите метод post_export, чтобы получить результирующий поток.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Python 2.7 или новее</li>
<li>Python 3.10 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

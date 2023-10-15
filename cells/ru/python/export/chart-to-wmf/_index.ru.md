---
title:  Экспортируйте CHART в WMF из Excel с помощью Cloud SDK Cells для Python.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Экспортировать CHART в WMF с номера Excel." h2="Python библиотека для экспорта CHART в файл WMF" p="Используйте экспорт API из Cells Cloud для экспорта рабочих процессов внутренних объектов файла Excel в Python. Это профессиональное решение для экспорта CHART в файл формата WMF из электронной таблицы онлайн с использованием Python." urlsection="export/chart-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Экспортируйте объект CHART в файл формата WMF с помощью Cloud SDK Cells для Python." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта CHART в файл WMF из файла Excel — сложная задача. Экспорт переходов формата CHART в WMF выполняется нашим SDK Python с сохранением основного структурного и логического содержимого исходной таблицы CHART. Наша библиотека Python — это профессиональное решение для онлайн-экспорта объектов CHART в файлы формата WMF. Этот Cloud SDK предоставляет разработчикам Python мощные функциональные возможности и отличный результат в формате WMF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Python с использованием REST API для экспорта CHART в формат WMF из электронной таблицы." gistPath="" %}}
  
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
    result = cells_api.post_export(files ,"chart","wmf")
    base64_string  = result.files[0].file_content
    base64_bytes = base64_string.encode("ascii")
    sample_string_bytes = base64.b64decode(base64_bytes)
    f = open(result.files[0].filename, 'w+b')
    f.write(sample_string_bytes)
    f.close()    
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cloud SDK Cells для Python для экспорта объектов из Excel CHART в WMF" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Вызовите метод post_export, чтобы получить результирующий поток.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Python 2.7 или новее</li>
<li>Python 3.10 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

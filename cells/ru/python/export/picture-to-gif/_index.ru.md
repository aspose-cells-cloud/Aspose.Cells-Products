﻿---
title:  Экспорт ИЗОБРАЖЕНИЯ в GIF из электронной таблицы с помощью Python API
description: Aspose.Cells Облачный REST API поддерживает экспорт Excel файлов и внутренних объектов в различные форматы файлов. SDK поддерживает различные языки разработки. Среди них Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby и swift.
url: /ru/python/export/picture-to-gif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API для экспорта ИЗОБРАЖЕНИЯ в файл GIF" h2="Python библиотека для экспорта ИЗОБРАЖЕНИЯ в файл GIF" p="Используйте Cells Экспорт REST API для экспорта рабочих процессов внутренних объектов электронной таблицы в Python. Это профессиональное решение для экспорта ИЗОБРАЖЕНИЯ в файл формата GIF из электронной таблицы онлайн с использованием Python." urlsection="export/picture-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Экспорт объекта PICTURE в файл формата GIF в Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта PICTURE в файл GIF из электронной таблицы является сложной задачей. Экспорт переходов формата ИЗОБРАЖЕНИЕ в GIF выполняется нашим SDK Python при сохранении основного структурного и логического содержания исходной электронной таблицы ИЗОБРАЖЕНИЯ. Наша библиотека Python — это профессиональное решение для онлайн-экспорта объектов PICTURE в файлы формата GIF. Этот облачный SDK предоставляет Python разработчикам мощные функциональные возможности и идеальный вывод GIF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Python с использованием REST API для экспорта ИЗОБРАЖЕНИЯ в формат GIF из электронной таблицы" gistPath="" %}}
  
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
    result = cells_api.post_export(files ,"picture","gif")
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Python API для экспорта ИЗОБРАЖЕНИЯ в GIF" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод post_export, чтобы получить результирующий поток</li>
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
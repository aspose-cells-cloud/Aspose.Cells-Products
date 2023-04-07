﻿---
title:  Сохраните JSON как SQL API для Python.
description:  Облачные API и SDK для Microsoft Excel и OpenOffice Calc. Преобразование электронной таблицы в файл другого формата.
url: /ru/python/saveas/json-to-sql/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API для сохранения JSON как SQL" h2="Python библиотека для сохранения JSON как SQL" p="Используйте Cells SaveAs REST API для создания настраиваемых рабочих процессов электронных таблиц в Python. Это профессиональное решение для сохранения JSON как SQL и других форматов документов в Интернете с использованием Python." urlsection="saveas/json-to-sql/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл JSON как SQL в Python." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из JSON в виде SQL — сложная задача. Все переходы формата JSON в формат SQL выполняются нашим пакетом SDK Python с сохранением основного структурного и логического содержимого исходной электронной таблицы JSON. Наша библиотека Python — это профессиональное решение для сохранения JSON в виде файлов SQL в Интернете. Этот Cloud SDK предоставляет Python разработчикам мощные функциональные возможности и идеальный вывод SQL.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Python с использованием REST API для сохранения JSON в формате SQL" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.json'    
    saveOptions = None
    newfilename = "Book1Saveas.sql"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Python API для сохранения JSON как SQL" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызов ячеек_сохранять_как_почта_документ_сохранять_как метод получения результирующего потока</li>
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
---
title: Преобразование XLSB в JSON API для Python
description:  Использование Aspose.Cells Cloud SDK для Python для преобразования файла формата XLSB в файл формата JSON.
url: /ru/python/conversion/xlsb-to-json/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API для преобразования XLSB в JSON" h2="Python библиотека для преобразования XLSB в JSON" p="Используйте Cells Преобразование REST API для создания настраиваемых рабочих процессов электронных таблиц в Python. Это профессиональное решение для онлайн-конвертации XLSB в JSON и другие форматы документов с использованием Python." urlsection="conversion/xlsb-to-json/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразование файла XLSB в JSON в Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из XLSB в JSON — сложная задача. Все переходы формата XLSB в формат JSON выполняются нашим SDK Python, при этом сохраняется основное структурное и логическое содержимое исходной электронной таблицы XLSB. Наша библиотека Python — это профессиональное решение для онлайн-конвертации файлов XLSB в JSON. Этот Cloud SDK предоставляет Python разработчикам мощные функциональные возможности и превосходный вывод в формате JSON.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Python с использованием REST API для преобразования XLSB в формат JSON" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xlsb",format="json")
    shutil.move(file1, "destFile.json")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Python API для преобразования XLSB в JSON" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызов ячеек_рабочая тетрадь_помещать_конвертировать_метод рабочей книги для получения результирующего потока</li>
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

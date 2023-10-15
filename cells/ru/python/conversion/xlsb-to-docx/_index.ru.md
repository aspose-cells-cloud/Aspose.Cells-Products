---
title:  Конвертируйте XLSB в DOCX, используя Python.
description: Использование Cloud SDK Aspose.Cells для Python для преобразования файла формата XLSB в файл формата DOCX.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Конвертировать XLSB в DOCX" h2="Python библиотека для конвертации XLSB в DOCX" p="Используйте преобразование API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Python. Это профессиональное решение для онлайн-конвертирования XLSB в DOCX и другие форматы документов с использованием номера Python." urlsection="conversion/xlsb-to-docx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразуйте XLSB в DOCX с помощью Cloud SDK Cells для Python." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из XLSB в DOCX может оказаться сложной задачей. Наш SDK Python обрабатывает все преобразования формата XLSB в DOCX, сохраняя при этом основное структурное и логическое содержимое исходной электронной таблицы XLSB. Наша библиотека Python предоставляет профессиональное решение для онлайн-конвертирования файлов XLSB в DOCX. Этот Cloud SDK предоставляет разработчикам Python мощные функциональные возможности и обеспечивает высококачественный вывод в формате DOCX.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Пример кода для преобразования XLSB в DOCX с помощью Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xlsb",format="docx")
    shutil.move(file1, "destFile.docx")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cloud SDK Cells для Python для преобразования файлов Excel в другие форматы XLSB в DOCX" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `put_convert_workbook` для получения результирующего потока.</li>
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

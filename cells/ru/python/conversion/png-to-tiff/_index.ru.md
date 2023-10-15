---
title:  Преобразуйте PNG в TIFF, используя Python.
description:  Использование Cloud SDK Aspose.Cells для Python для преобразования файла формата PNG в файл формата TIFF.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Преобразовать PNG в TIFF" h2="Python библиотека для преобразования PNG в TIFF" p="Используйте преобразование API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Python. Это профессиональное решение для онлайн-конвертации PNG в TIFF и других форматов документов с использованием Python." urlsection="conversion/png-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразуйте PNG в TIFF с помощью Cloud SDK Cells для Python." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов с PNG в TIFF может оказаться сложной задачей. Наш SDK Python обрабатывает все преобразования форматов PNG в TIFF, сохраняя при этом основное структурное и логическое содержимое исходной таблицы PNG. Наша библиотека Python предоставляет профессиональное решение для онлайн-конвертации файлов PNG в TIFF. Этот Cloud SDK предоставляет разработчикам Python мощные функциональные возможности и обеспечивает высококачественный результат TIFF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Пример кода для преобразования PNG в TIFF с помощью Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.png",format="tiff")
    shutil.move(file1, "destFile.tiff")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cloud SDK Cells для Python для преобразования файлов Excel в другие форматы с PNG по TIFF." >}}
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

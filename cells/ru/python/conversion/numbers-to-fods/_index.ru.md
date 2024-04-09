---
title:  Преобразуйте ЧИСЛА в FODS, используя Python.
description:  Использование Cloud SDK Aspose.Cells для Python для преобразования файла формата NUMBERS в файл формата FODS.
kwords: Excel, Convert NUMBERS to FODS, REST, Python
howto: How to convert NUMBERS to FODS using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Преобразовать ЧИСЛА в FODS" h2="Python библиотека для преобразования ЧИСЕЛ в FODS" p="Используйте преобразование API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Python. Это профессиональное решение для онлайн-конвертации ЧИСЕЛ в FODS и другие форматы документов с помощью Python." urlsection="conversion/numbers-to-fods/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразуйте ЧИСЛА в FODS с помощью Cells Cloud SDK для Python." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из NUMBERS в FODS может оказаться сложной задачей. Наш SDK Python обрабатывает все преобразования формата NUMBERS в FODS, сохраняя при этом основное структурное и логическое содержимое исходной таблицы NUMBERS. Наша библиотека Python предоставляет профессиональное решение для онлайн-конвертирования ЧИСЕЛ в файлы FODS. Этот Cloud SDK предоставляет разработчикам Python мощные функциональные возможности и обеспечивает высококачественный вывод FODS.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Пример кода для преобразования ЧИСЕЛ в FODS с помощью Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.numbers",format="fods")
    shutil.move(file1, "destFile.fods")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как преобразовать ЧИСЛА в FODS, используя библиотеку Cells Cloud Python." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Python и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру Python.</li>
<li>Используйте метод `put_convert_workbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Python 2.7 или новее</li>
<li>Python 3.10 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

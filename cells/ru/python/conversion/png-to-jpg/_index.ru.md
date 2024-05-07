---
title:  Конвертируйте PNG в JPG, используя Python.
description:  Использование Cloud SDK Aspose.Cells для Python для преобразования файла формата PNG в файл формата JPG.
kwords: Excel, Convert PNG to JPG, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert PNG to JPG using the Cells Cloud Python library.","description": "How to convert PNG to JPG using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/conversion/png-to-jpg/","step": [{ "@type": "HowToStep","name": "How to convert PNG to JPG using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/png-to-jpg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert PNG to JPG using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/png-to-jpg/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert PNG to JPG using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/png-to-jpg/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to convert PNG to JPG using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/conversion/png-to-jpg/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Конвертировать PNG в JPG" h2="Python библиотека для конвертации PNG в JPG" p="Используйте преобразование API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Python. Это профессиональное решение для онлайн-конвертирования PNG в JPG и другие форматы документов с помощью Python." urlsection="conversion/png-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразуйте PNG в JPG с помощью Cloud SDK Cells для Python." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов PNG в JPG может оказаться сложной задачей. Наш SDK Python обрабатывает все преобразования формата PNG в JPG, сохраняя при этом основное структурное и логическое содержимое исходной таблицы PNG. Наша библиотека Python предоставляет профессиональное решение для онлайн-конвертирования PNG в файлы JPG. Этот Cloud SDK предоставляет разработчикам Python мощные функциональные возможности и обеспечивает высококачественный вывод в формате JPG.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Пример кода для преобразования PNG в JPG с помощью Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.png",format="jpg")
    shutil.move(file1, "destFile.jpg")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как конвертировать PNG в JPG с помощью библиотеки Cells Cloud Python." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Python и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру Python.</li>
<li>Используйте метод `put_convert_workbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Python 2.7 или новее</li>
<li>Python 3.10 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

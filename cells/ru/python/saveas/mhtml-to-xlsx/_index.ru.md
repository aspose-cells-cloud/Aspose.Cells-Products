---
title:  Сохраните MHTML как XLSX, используя Python.
description:  Использование Aspose.Cells Cloud SDK для Python для сохранения файла формата MHTML в формате XLSX.
kwords: Excel, Save MHTML as XLSX, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save MHTML as XLSX using the Cells Cloud Python library.","description": "How to save MHTML as XLSX using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/saveas/mhtml-to-xlsx/","step": [{ "@type": "HowToStep","name": "How to save MHTML as XLSX using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/mhtml-to-xlsx/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save MHTML as XLSX using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/mhtml-to-xlsx/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save MHTML as XLSX using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/mhtml-to-xlsx/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to save MHTML as XLSX using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/mhtml-to-xlsx/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить MHTML как XLSX." h2="Python библиотека для сохранения MHTML в формате XLSX" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Python. Это профессиональное решение для сохранения MHTML как XLSX и других форматов документов в Интернете с помощью Python." urlsection="saveas/mhtml-to-xlsx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл MHTML как XLSX по номеру Python." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из MHTML в формате XLSX — сложная задача. Все переходы формата MHTML в XLSX выполняются нашим SDK Python с сохранением основного структурного и логического содержимого исходной электронной таблицы MHTML. Наша библиотека Python — это профессиональное решение для сохранения файлов MHTML в формате XLSX онлайн. Этот Cloud SDK предоставляет разработчикам Python мощные функциональные возможности и идеальный вывод в формате XLSX.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Пример кода для сохранения MHTML в формате XLSX с использованием REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.mhtml'    
    saveOptions = None
    newfilename = "Book1Saveas.xlsx"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как сохранить MHTML в формате XLSX, используя библиотеку Cells Cloud Python." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Python и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру Python.</li>
<li>Используйте метод `post_workbook_save_as` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Python 2.7 или новее</li>
<li>Python 3.10 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

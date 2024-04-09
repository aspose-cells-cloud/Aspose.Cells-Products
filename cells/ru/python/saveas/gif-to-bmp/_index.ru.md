---
title:  Сохраните GIF как BMP, используя Python.
description:  Использование Aspose.Cells Cloud SDK для Python для сохранения файла формата GIF как файла формата BMP.
kwords: Excel, Save GIF as BMP, REST, Python
howto: How to save GIF as BMP using Aspose.Cells Cloud Python library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить GIF как BMP" h2="Python библиотека для сохранения GIF как BMP" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Python. Это профессиональное решение для сохранения GIF как BMP и других форматов документов в Интернете с помощью Python." urlsection="saveas/gif-to-bmp/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните GIF-файл под номером BMP в Python." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение формата файлов GIF как BMP — сложная задача. Все переходы форматов GIF в BMP выполняются нашим SDK Python с сохранением основного структурного и логического содержимого исходной таблицы GIF. Наша библиотека Python — это профессиональное решение для сохранения GIF в виде файлов BMP онлайн. Этот Cloud SDK предоставляет разработчикам Python мощные функциональные возможности и идеальный результат BMP.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Пример кода для сохранения GIF как BMP с использованием REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.gif'    
    saveOptions = None
    newfilename = "Book1Saveas.bmp"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как сохранить GIF как BMP, используя библиотеку Cells Cloud Python." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Python и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру Python.</li>
<li>Используйте метод `post_workbook_save_as` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Python 2.7 или новее</li>
<li>Python 3.10 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

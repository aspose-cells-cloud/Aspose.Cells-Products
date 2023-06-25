---
title:  Сохраните XLTM как XML API для Python
description:  Использование Aspose.Cells Cloud SDK для Python для сохранения файла формата XLTM в виде файла формата XML.
url: /ru/python/saveas/xltm-to-xml/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API, чтобы сохранить XLTM как XML" h2="Python библиотека для сохранения XLTM в формате XML" p="Используйте Cells SaveAs REST API для создания настраиваемых рабочих процессов электронных таблиц в Python. Это профессиональное решение для сохранения XLTM как XML и других форматов документов в Интернете с использованием Python." urlsection="saveas/xltm-to-xml/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл XLTM в формате XML по адресу Python." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из XLTM в виде XML — сложная задача. Все переходы формата XLTM в формат XML выполняются нашим SDK Python при сохранении основного структурного и логического содержимого исходной электронной таблицы XLTM. Наша библиотека Python — это профессиональное решение для сохранения XLTM в виде XML-файлов в Интернете. Этот облачный SDK предоставляет Python разработчикам мощные функциональные возможности и идеальный вывод XML.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Python с использованием REST API для сохранения XLTM в формате XML" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xltm'    
    saveOptions = None
    newfilename = "Book1Saveas.xml"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Python API для сохранения XLTM в формате XML" >}}
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

---
title:  Сохранить PNG как BMP API для Python
description: Использование Aspose.Cells Cloud SDK для Python для сохранения файла формата PNG как файла формата BMP.
url: /ru/python/saveas/png-to-bmp/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API, чтобы сохранить PNG как BMP" h2="Python библиотека для сохранения PNG как BMP" p="Используйте Cells SaveAs REST API для создания настраиваемых рабочих процессов электронных таблиц в Python. Это профессиональное решение для сохранения PNG как BMP и других форматов документов в Интернете с использованием Python." urlsection="saveas/png-to-bmp/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл PNG как BMP в Python." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов с PNG как BMP — сложная задача. Все переходы форматов с PNG на BMP выполняются нашим SDK Python с сохранением основного структурного и логического содержимого исходной электронной таблицы PNG. Наша библиотека Python — это профессиональное решение для сохранения файлов PNG как BMP онлайн. Этот облачный SDK предоставляет Python разработчикам мощную функциональность и идеальный результат BMP.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Python с использованием REST API для сохранения PNG в формате BMP" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.png'    
    saveOptions = None
    newfilename = "Book1Saveas.bmp"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Python API, чтобы сохранить PNG как BMP" >}}
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

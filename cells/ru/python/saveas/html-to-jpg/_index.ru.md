---
title: Сохранить HTML как JPG API для Python
description:  Использование Aspose.Cells Cloud SDK для Python для сохранения файла формата HTML в виде файла формата JPG.
url: /ru/python/saveas/html-to-jpg/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API, чтобы сохранить HTML в формате JPG" h2="Python библиотека для сохранения HTML в формате JPG" p="Используйте Cells SaveAs REST API для создания настраиваемых рабочих процессов электронных таблиц в Python. Это профессиональное решение для сохранения HTML в формате JPG и других форматах документов в Интернете с использованием Python." urlsection="saveas/html-to-jpg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл HTML в формате JPG в Python." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов с HTML в виде JPG — сложная задача. Все переходы HTML в формат JPG выполняются нашим SDK Python при сохранении основного структурного и логического содержимого исходной электронной таблицы HTML. Наша библиотека Python — это профессиональное решение для сохранения HTML в виде файлов JPG онлайн. Этот облачный SDK предоставляет Python разработчикам мощные функциональные возможности и превосходный вывод в формате JPG.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Python с использованием REST API для сохранения HTML в формате JPG" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.html'    
    saveOptions = None
    newfilename = "Book1Saveas.jpg"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Python API для сохранения HTML в формате JPG" >}}
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

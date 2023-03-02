---
title: Конвертировать из Excel FODS в CSV via Python
description: Создавайте, редактируйте или конвертируйте Excel файлы с помощью REST API и Open Source Python SDK
url: /ru/python/conversion/fods-to-csv/
family: cells
platformtag: python
feature: conversion
informat: FODS
outformat: CSV
platform: Python
otherformats: SVG CSV XLSM PDF ODS DIF XLSB MHTML XLT TSV XLSX XLTX TIFF XLTM FODS TXT 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Преобразование FODS в CSV с помощью Python" h2="Чтение, редактирование и экспорт Excel данных в другие форматы с помощью Cloud SDK с открытым исходным кодом для Python" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Преобразование FODS в CSV с Python" %}}
1.  Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API
1. Инициализируйте ```CellsApi``` с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.
1. Загрузите файл FODS в облачное хранилище по умолчанию с помощью метода ```CellsApi.upload_file```.
1. Вызовите метод ```CellsApi.cells_save_as_post_document_save_as```, чтобы получить результирующий CSV-файл.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начните работу с Excel, API и Python SDK" %}}
 Получите Excel Cloud SDK для исходного кода Python из[Гитхаб](https://github.com/aspose-cells-cloud/aspose-cells-cloud-python) скомпилировать SDK самостоятельно или обратиться к[Релизы](https://releases.aspose.cloud/) для альтернативных вариантов загрузки.

 Также взгляните на Swagger-based[API Ссылка](https://apireference.aspose.cloud/cells/) узнать больше о[Excel ОТДЫХ API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Python Код для преобразования FODS в CSV" gistPath="" %}}
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python
import os
import sys
import asposecellscloud
from asposecellscloud.apis.cells_api import CellsApi
api  = asposecellscloud.apis.cells_api.CellsApi(os.getenv('CellsCloudClientId'), os.getenv('CellsCloudClientSecret'), "v3.0" ,os.getenv('CellsCloudApiBaseUrl'))

name ='template.fods'    
saveOptions = None
newfilename = "output.csv"
isAutoFitRows= True
isAutoFitColumns= True
folder = "temp"
result = api.upload_file(folder + '/' + name,  "c:/TestData/" + name)
 
result = api.cells_save_as_post_document_save_as(name, save_options=saveOptions, newfilename=(folder +'/' + newfilename), is_auto_fit_rows=isAutoFitRows, is_auto_fit_columns=isAutoFitColumns, folder=folder)
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
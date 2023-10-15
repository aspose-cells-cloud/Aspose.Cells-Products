---
title:  Преобразование FODS в TIFF в облаке via PHP
description: Создавайте, редактируйте или конвертируйте файлы Excel с помощью REST API и SDK с открытым исходным кодом PHP.
url: /ru/php/conversion/fods-to-tiff/
family: cells
platformtag: php
feature: conversion
informat: FODS
outformat: TIFF
platform: PHP
otherformats: CSV FODS TSV PDF TXT MHTML XLS DIF XLSX SVG XLSM XLTM XLTX XLSB XPS TIFF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Преобразуйте FODS в TIFF с помощью PHP" h2="Автоматизируйте преобразование файлов Excel и OpenOffice с помощью Cloud SDK с открытым исходным кодом для PHP." >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Быстро конвертируйте FODS в TIFF via PHP" %}}
1.  Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API
1. Инициализируйте ```CellsApi```, используя идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.
1. Загрузите файл FODS в облачное хранилище по умолчанию с помощью метода ```CellsApi.uploadFile```.
1. Позвоните по номеру ```CellsApi.cellsSaveAsPostDocumentSaveAs```, чтобы получить результирующий файл TIFF.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начало работы с Excel, API и PHP SDK" %}}
 Получите Excel Cloud SDK для исходного кода PHP с сайта[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) скомпилировать SDK самостоятельно или перейти к[Релизы](https://releases.aspose.cloud/) альтернативные варианты загрузки.

 Также взгляните на Swagger на основе[API Ссылка](https://apireference.aspose.cloud/cells/) чтобы узнать больше о[Excel ОТДЫХ API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Код PHP для преобразования FODS в TIFF" gistPath="" %}}
```php

# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php

$name ='template.fods';    
$saveOptions = null;
$newfilename = "output.tiff";
$isAutoFitRows= 'true';
$isAutoFitColumns= 'true';
$folder = "Temp";
CellsApi::ready( $this->instance, $name, $folder );
$result = $this->instance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename, $isAutoFitRows, $isAutoFitColumns, $folder);
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
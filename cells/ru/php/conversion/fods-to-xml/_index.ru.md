﻿---
title:  Преобразование FODS в XML в облаке via PHP
description: Создавайте, редактируйте или конвертируйте файлы Excel с помощью REST API и SDK с открытым исходным кодом PHP.
url: /ru/php/conversion/fods-to-xml/
family: cells
platformtag: php
feature: conversion
informat: FODS
outformat: XML
platform: PHP
otherformats: MD XLT XML DIF HTML XLSM PDF XLTM XLTX TSV TIFF XLSX FODS SVG TXT XPS 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Конвертируйте FODS в XML с помощью PHP" h2="Автоматизируйте преобразование файлов Excel и OpenOffice с помощью Cloud SDK с открытым исходным кодом для PHP." >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Быстрое преобразование FODS в XML via PHP" %}}
1.  Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API
1. Инициализируйте ```CellsApi```, используя идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.
1. Загрузите файл FODS в облачное хранилище по умолчанию с помощью метода ```CellsApi.uploadFile```.
1. Позвоните по номеру ```CellsApi.cellsSaveAsPostDocumentSaveAs```, чтобы получить результирующий XML-файл.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начало работы с Excel, API и PHP SDK" %}}
 Получите Excel Cloud SDK для исходного кода PHP с сайта[GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) скомпилировать SDK самостоятельно или перейти к[Релизы](https://releases.aspose.cloud/) альтернативные варианты загрузки.

 Также взгляните на Swagger на основе[API Ссылка](https://apireference.aspose.cloud/cells/) чтобы узнать больше о[Excel ОТДЫХ API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP Код для преобразования FODS в XML" gistPath="" %}}
```php

# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php

$name ='template.fods';    
$saveOptions = null;
$newfilename = "output.xml";
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
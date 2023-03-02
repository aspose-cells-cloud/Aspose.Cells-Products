---
title:  Преобразование FODS в HTML в облаке via PHP
description: Создавайте, редактируйте или конвертируйте Excel файлы с помощью REST API и Open Source PHP SDK
url: /ru/php/conversion/fods-to-html/
family: cells
platformtag: php
feature: conversion
informat: FODS
outformat: HTML
platform: PHP
otherformats: ODS TXT XLT XLSX XML CSV TSV MHTML FODS DIF XLSB XLTM PDF XLSM MD TIFF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Преобразование FODS в HTML с помощью PHP" h2="Автоматизируйте преобразование файлов Excel и OpenOffice с помощью Cloud SDK с открытым исходным кодом для PHP" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Быстрое преобразование FODS в HTML via PHP" %}}
1.  Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API
1. Инициализируйте ```CellsApi``` с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.
1. Загрузите файл FODS в облачное хранилище по умолчанию с помощью метода ```CellsApi.uploadFile```.
1. Позвоните по номеру ```CellsApi.cellsSaveAsPostDocumentSaveAs```, чтобы получить результирующий файл HTML.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Начните работу с Excel, API и PHP SDK" %}}
 Получите Excel Cloud SDK для исходного кода PHP из[Гитхаб](https://github.com/aspose-cells-cloud/aspose-cells-cloud-php) скомпилировать SDK самостоятельно или обратиться к[Релизы](https://releases.aspose.cloud/) для альтернативных вариантов загрузки.

 Также взгляните на Swagger-based[API Ссылка](https://apireference.aspose.cloud/cells/) узнать больше о[Excel ОТДЫХ API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="PHP Код FODS для конвертации HTML" gistPath="" %}}
```php

# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php

$name ='template.fods';    
$saveOptions = null;
$newfilename = "output.html";
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
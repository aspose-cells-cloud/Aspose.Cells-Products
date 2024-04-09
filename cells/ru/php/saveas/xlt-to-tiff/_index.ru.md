---
title:  Сохраните XLT как TIFF, используя PHP.
description:  Использование Cloud SDK Aspose.Cells для PHP для сохранения файла формата XLT как файла формата TIFF.
kwords: Excel, Save XLT as TIFF, REST, PHP
howto: How to save XLT as TIFF using Aspose.Cells Cloud PHP library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить XLT как TIFF" h2="PHP библиотека для сохранения XLT как TIFF" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в PHP. Это профессиональное решение для сохранения XLT как TIFF и других форматов документов в Интернете с использованием PHP." urlsection="saveas/xlt-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл XLT как TIFF в PHP." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение формата файла из XLT как TIFF — сложная задача. Все переходы формата XLT в TIFF выполняются нашим SDK PHP с сохранением основного структурного и логического содержимого исходной таблицы XLT. Наша библиотека PHP — это профессиональное решение для сохранения файлов XLT в формате TIFF онлайн. Этот Cloud SDK предоставляет разработчикам PHP мощные функциональные возможности и идеальный результат TIFF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Пример кода для сохранения XLT как TIFF с использованием REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xlt';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "tiff";
    $newfilename = "Book1Saveas.tiff";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как сохранить XLT как TIFF, используя библиотеку Cells Cloud PHP." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку PHP и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру PHP.</li>
<li>Используйте метод `PostWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>PHP 7.4 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

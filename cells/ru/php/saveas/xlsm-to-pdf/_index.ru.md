---
title:  Сохраните XLSM как PDF, используя PHP.
description:  Использование Aspose.Cells Cloud SDK для PHP для сохранения файла формата XLSM как файла формата PDF.
kwords: Excel, Save XLSM as PDF, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLSM as PDF using the Cells Cloud PHP library.","description": "How to save XLSM as PDF using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/saveas/xlsm-to-pdf/","step": [{ "@type": "HowToStep","name": "How to save XLSM as PDF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xlsm-to-pdf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLSM as PDF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xlsm-to-pdf/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLSM as PDF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xlsm-to-pdf/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to save XLSM as PDF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/saveas/xlsm-to-pdf/","text": "Use the `PostWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить XLSM как PDF." h2="PHP библиотека для сохранения XLSM как PDF" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в PHP. Это профессиональное решение для сохранения XLSM как PDF и других форматов документов в Интернете с использованием PHP." urlsection="saveas/xlsm-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл XLSM как PDF в PHP." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение формата файла XLSM как PDF — сложная задача. Все переходы формата XLSM в PDF выполняются нашим SDK PHP с сохранением основного структурного и логического содержимого исходной таблицы XLSM. Наша библиотека PHP — это профессиональное решение для сохранения файлов XLSM в формате PDF в Интернете. Этот Cloud SDK предоставляет разработчикам PHP мощные функциональные возможности и идеальный результат PDF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Пример кода для сохранения XLSM как PDF с использованием REST API" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    $apiInstance = new CellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $name ='Book1.xlsm';
    $saveOptions =new \Aspose\Cells\Cloud\Model\SaveOptions();
    $saveOptions->SaveFormat = "pdf";
    $newfilename = "Book1Saveas.pdf";
    $isAutoFitRows= 'true';
    $isAutoFitColumns= 'true';
    $folder = "Temp";
    $result = $apiInstance->cellsSaveAsPostDocumentSaveAs($name, $saveOptions, $newfilename,$isAutoFitRows, $isAutoFitColumns, $folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как сохранить XLSM как PDF, используя библиотеку Cells Cloud PHP." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку PHP и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру PHP.</li>
<li>Используйте метод `PostWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>PHP 7.4 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

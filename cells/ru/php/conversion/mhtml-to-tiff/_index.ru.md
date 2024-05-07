---
title:  Преобразуйте MHTML в TIFF, используя PHP.
description:  Использование Cloud SDK Aspose.Cells для PHP для преобразования файла формата MHTML в файл формата TIFF.
kwords: Excel, Convert MHTML to TIFF, REST, PHP
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert MHTML to TIFF using the Cells Cloud PHP library.","description": "How to convert MHTML to TIFF using the Cells Cloud PHP library.","image": {"@type": "ImageObject"},"url": "/php/conversion/mhtml-to-tiff/","step": [{ "@type": "HowToStep","name": "How to convert MHTML to TIFF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/mhtml-to-tiff/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert MHTML to TIFF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/mhtml-to-tiff/","text": "Install PHP library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert MHTML to TIFF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/mhtml-to-tiff/","text": "Open the source file in PHP.",},{ "@type": "HowToStep","name": "How to convert MHTML to TIFF using the Cells Cloud PHP library. step 1", "image": {"@type": "ImageObject",},"url": "/php/conversion/mhtml-to-tiff/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "phpstorm, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Преобразовать MHTML в TIFF" h2="PHP библиотека для преобразования MHTML в TIFF" p="Используйте преобразование API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах PHP. Это профессиональное решение для онлайн-конвертирования MHTML в TIFF и другие форматы документов с использованием PHP." urlsection="conversion/mhtml-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразуйте MHTML в TIFF с помощью Cloud SDK Cells для PHP." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из MHTML в TIFF может оказаться сложной задачей. Наш SDK PHP обрабатывает все преобразования форматов MHTML в TIFF, сохраняя при этом основное структурное и логическое содержимое исходной электронной таблицы MHTML. Наша библиотека PHP предоставляет профессиональное решение для онлайн-конвертирования файлов MHTML в файлы TIFF. Этот Cloud SDK предоставляет разработчикам PHP мощные функциональные возможности и обеспечивает высококачественный результат TIFF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="PHP Пример кода для преобразования MHTML в TIFF с использованием Cells Cloud SDK" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.mhtml';    
    $format ='tiff';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.tiff", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как преобразовать MHTML в TIFF с помощью библиотеки Cells Cloud PHP." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку PHP и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру PHP.</li>
<li>Используйте метод `putConvertWorkbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>PHP 7.4 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

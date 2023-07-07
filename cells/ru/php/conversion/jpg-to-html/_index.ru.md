---
title: JPG в HTML Конвертировать API в PHP
description:  Использование Aspose.Cells Cloud SDK для PHP для преобразования файла формата JPG в файл формата HTML.
url: /ru/php/conversion/jpg-to-html/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API для преобразования JPG в HTML" h2="библиотека PHP для преобразования JPG в HTML" p="Используйте Cells Преобразование REST API для создания настраиваемых рабочих процессов электронных таблиц в PHP. Это профессиональное решение для преобразования JPG в HTML и другие форматы документов онлайн с использованием PHP." urlsection="conversion/jpg-to-html/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразование файла JPG в HTML в PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из JPG в HTML — сложная задача. Все переходы между форматами JPG и HTML выполняются нашим SDK PHP с сохранением основного структурного и логического содержимого исходной электронной таблицы JPG. Наша библиотека PHP — это профессиональное решение для онлайн-конвертации JPG в файлы HTML. Этот облачный SDK предоставляет PHP разработчикам мощную функциональность и идеальный результат HTML.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в PHP с использованием REST API для преобразования JPG в формат HTML" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.jpg';    
    $format ='html';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.html", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать PHP API для преобразования JPG в HTML" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод cellWorkbookPutConvertWorkBook, чтобы получить результирующий поток</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>PHP 7.4 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

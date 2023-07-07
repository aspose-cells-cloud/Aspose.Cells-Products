---
title: Преобразование GIF в XLS API для PHP
description:  Использование Aspose.Cells Cloud SDK для PHP для преобразования файла формата GIF в файл формата XLS.
url: /ru/php/conversion/gif-to-xls/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API для преобразования GIF в XLS" h2="PHP библиотека для преобразования GIF в XLS" p="Используйте Cells Преобразование REST API для создания настраиваемых рабочих процессов электронных таблиц в PHP. Это профессиональное решение для онлайн-конвертации GIF в XLS и другие форматы документов с использованием PHP." urlsection="conversion/gif-to-xls/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Конвертируйте файл GIF в XLS по номеру PHP." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из GIF в XLS — сложная задача. Все переходы формата GIF в формат XLS выполняются нашим SDK PHP с сохранением основного структурного и логического содержимого исходной электронной таблицы GIF. Наша библиотека PHP — это профессиональное решение для онлайн-конвертации файлов GIF в XLS. Этот облачный SDK предоставляет PHP разработчикам мощные функциональные возможности и идеальный вывод XLS.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в PHP с использованием REST API для преобразования GIF в формат XLS" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.gif';    
    $format ='xls';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.xls", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать PHP API для преобразования GIF в XLS" >}}
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

---
title:  EMF в DIF Преобразование API в PHP
description:  Использование Aspose.Cells Cloud SDK для PHP для преобразования файла формата EMF в файл формата DIF.
url: /ru/php/conversion/emf-to-dif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API для преобразования EMF в DIF" h2="PHP библиотека для преобразования EMF в DIF" p="Используйте Cells Преобразование REST API для создания настраиваемых рабочих процессов электронных таблиц в PHP. Это профессиональное решение для преобразования EMF в DIF и другие форматы документов онлайн с использованием PHP." urlsection="conversion/emf-to-dif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразование файла EMF в DIF в PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из EMF в DIF является сложной задачей. Все переходы формата EMF в формат DIF выполняются нашим SDK PHP, при этом сохраняется основное структурное и логическое содержимое исходной электронной таблицы EMF. Наша библиотека PHP — это профессиональное решение для онлайн-конвертации EMF в файлы DIF. Этот облачный SDK предоставляет PHP разработчикам мощные функциональные возможности и идеальный вывод DIF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в PHP с использованием REST API для преобразования EMF в формат DIF" gistPath="" %}}
 
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\CellsApi;
    $instance = new CellsApi(getenv("ProductClientId"),getenv("ProductClientSecret"));
    $path ='Book1.emf';    
    $format ='dif';
    $password = null;
    $outPath = null;      
    $result = $this->instance->cellsWorkbookPutConvertWorkBook($path ,$format, $password,  $outPath);
    $size = $result->getSize();
    $content  = $result->fread($size);
    $file = fopen("destfile.dif", 'w');
    fwrite($file,$content);
    fclose($file);
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать PHP API для преобразования EMF в DIF" >}}
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

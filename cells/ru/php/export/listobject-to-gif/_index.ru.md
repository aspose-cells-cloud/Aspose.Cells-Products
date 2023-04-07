﻿---
title:  Экспорт LISTOBJECT в GIF из электронной таблицы с помощью PHP API
description: Aspose.Cells Облачный REST API поддерживает экспорт Excel файлов и внутренних объектов в различные форматы файлов. SDK поддерживает различные языки разработки. Среди них Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby и swift.
url: /ru/php/export/listobject-to-gif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API для экспорта LISTOBJECT в файл GIF" h2="PHP библиотека для экспорта LISTOBJECT в файл GIF" p="Используйте Cells Export REST API для экспорта рабочих процессов внутренних объектов электронной таблицы в PHP. Это профессиональное решение для экспорта LISTOBJECT в файл формата GIF из электронной таблицы онлайн с использованием PHP." urlsection="export/listobject-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Экспорт объекта LISTOBJECT в файл формата GIF в PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта LISTOBJECT в файл GIF из электронной таблицы является сложной задачей. Экспорт переходов формата LISTOBJECT в формат GIF выполняется нашим SDK PHP при сохранении основного структурного и логического содержимого исходной электронной таблицы LISTOBJECT. Наша библиотека PHP — это профессиональное решение для онлайн-экспорта объектов LISTOBJECT в файлы формата GIF. Этот облачный SDK предоставляет PHP разработчикам мощные функциональные возможности и идеальный вывод GIF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в PHP с использованием REST API для экспорта LISTOBJECT в формат GIF из электронной таблицы" gistPath="" %}}
  
```php
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-php/
    <?php
    require_once('vendor\autoload.php');
    use \Aspose\Cells\Cloud\Api\LightCellsApi;
    $cells = new LightCellsApi( getenv("ProductClientId"),getenv("ProductClientSecret") );
    $files = array (
        'DataSource' =>  "C:/datasource.xlsx",
        'AssemblyTest' => "C:/assemblytest.xlsx"
    );
    $result = $cells->postExport( $files,'listobject', 'gif' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать PHP API для экспорта LISTOBJECT в GIF" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод postExport, чтобы получить результирующий поток</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>PHP 7.4 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
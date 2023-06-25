---
title:  Экспорт WORKBOOK в PPTX из электронной таблицы с использованием PHP API
description:  Aspose.Cells Cloud REST API поддерживает экспорт {0} в файлы формата {1} с использованием {2}.
url: /ru/php/export/workbook-to-pptx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="PHP API для экспорта WORKBOOK в файл PPTX" h2="PHP библиотека для экспорта WORKBOOK в файл PPTX" p="Используйте Cells Экспорт REST API для экспорта рабочих процессов внутренних объектов электронной таблицы в PHP. Это профессиональное решение для экспорта файла формата WORKBOOK в файл формата PPTX из электронной таблицы онлайн с использованием PHP." urlsection="export/workbook-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Экспорт объекта WORKBOOK в файл формата PPTX в PHP" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта WORKBOOK в файл PPTX из электронной таблицы — сложная задача. Экспорт переходов WORKBOOK в формат PPTX выполняется нашим SDK PHP при сохранении основного структурного и логического содержимого исходной электронной таблицы WORKBOOK. Наша библиотека PHP — это профессиональное решение для онлайн-экспорта объектов WORKBOOK в файлы формата PPTX. Этот облачный SDK предоставляет PHP разработчикам мощную функциональность и идеальный вывод PPTX.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в PHP с использованием REST API для экспорта WORKBOOK в формат PPTX из электронной таблицы" gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'workbook', 'pptx' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать PHP API для экспорта WORKBOOK в PPTX" >}}
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

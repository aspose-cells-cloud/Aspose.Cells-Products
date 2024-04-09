---
title:  Экспортируйте WORKSHEET в PPTX из Excel с помощью Cloud SDK Cells для PHP.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Экспорт РАБОЧЕГО ЛИСТА в PPTX с номера Excel" h2="PHP библиотека для экспорта WORKSHEET в файл PPTX" p="Используйте экспорт API из Cells Cloud для экспорта рабочих процессов внутренних объектов файла Excel в PHP. Это профессиональное решение для экспорта WORKSHEET в файл формата PPTX из электронной таблицы онлайн с использованием PHP." urlsection="export/worksheet-to-pptx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Экспортируйте объект WORKSHEET в файл формата PPTX с помощью Cloud SDK Cells для PHP." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта WORKSHEET в файл PPTX из файла Excel — сложная задача. Экспорт переходов формата WORKSHEET в PPTX выполняется нашим SDK PHP с сохранением основного структурного и логического содержимого исходной электронной таблицы WORKSHEET. Наша библиотека PHP — это профессиональное решение для онлайн-экспорта объектов WORKSHEET в файлы формата PPTX. Этот Cloud SDK предоставляет разработчикам PHP мощные функциональные возможности и идеальный вывод PPTX.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода PHP с использованием REST API для экспорта WORKSHET в формат PPTX из электронной таблицы." gistPath="" %}}
  
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
    $result = $cells->postExport( $files,'worksheet', 'pptx' );
    $filename = $result->getFiles()[0]->getFilename() ;
    $fileData = $result->getFiles()[0]->getFileContent() ;
    $ptr = fopen($filename, 'wb');
    fwrite($ptr, base64_decode($fileData));
    fclose($ptr);
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cloud SDK Cells для PHP для экспорта объектов из Excel WORKSHEET в PPTX" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `postExport` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>PHP 7.4 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

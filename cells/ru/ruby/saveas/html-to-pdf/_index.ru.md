---
title:  Сохранить HTML как PDF API для Ruby
description:  Использование Aspose.Cells Cloud SDK для Ruby для сохранения файла формата HTML как файла формата PDF.
url: /ru/ruby/saveas/html-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API, чтобы сохранить HTML как PDF" h2="Библиотека Ruby для сохранения HTML как PDF" p="Используйте Cells SaveAs REST API для создания настраиваемых рабочих процессов электронных таблиц в Ruby. Это профессиональное решение для сохранения HTML как PDF и других форматов документов в Интернете с использованием Ruby." urlsection="saveas/html-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл HTML как PDF в Ruby." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов с HTML как PDF — сложная задача. Все переходы форматов с HTML на PDF выполняются нашим Ruby SDK при сохранении основного структурного и логического содержимого исходной электронной таблицы HTML. Наша библиотека Ruby — это профессиональное решение для сохранения файлов HTML как PDF онлайн. Этот Cloud SDK предоставляет разработчикам Ruby мощную функциональность и идеальный вывод PDF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Ruby с использованием REST API для сохранения HTML в формате PDF" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.html'
    save_options = nil
    newfilename = 'Book1Saveas.pdf'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Ruby API, чтобы сохранить HTML как PDF" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызов ячеек_сохранять_как_почта_документ_сохранять_как метод получения результирующего потока</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>рубин 2.5 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

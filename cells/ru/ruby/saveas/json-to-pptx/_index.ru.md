---
title:  Сохраните JSON как PPTX API для Ruby
description:  Использование Aspose.Cells Cloud SDK для Ruby для сохранения файла формата JSON в виде файла формата PPTX.
url: /ru/ruby/saveas/json-to-pptx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API для сохранения JSON как PPTX" h2="Библиотека Ruby для сохранения JSON как PPTX" p="Используйте Cells SaveAs REST API для создания настраиваемых рабочих процессов электронных таблиц в Ruby. Это профессиональное решение для сохранения JSON как PPTX и других форматов документов онлайн с использованием Ruby." urlsection="saveas/json-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл JSON как PPTX в Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из JSON в виде PPTX — сложная задача. Все переходы между форматами JSON и PPTX выполняются нашим Ruby SDK при сохранении основного структурного и логического содержимого исходной электронной таблицы JSON. Наша библиотека Ruby — это профессиональное решение для сохранения JSON в виде файлов PPTX онлайн. Этот облачный SDK предоставляет разработчикам Ruby мощные функциональные возможности и идеальный вывод PPTX.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Ruby с использованием REST API для сохранения JSON в формате PPTX" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.json'
    save_options = nil
    newfilename = 'Book1Saveas.pptx'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Ruby API для сохранения JSON как PPTX" >}}
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

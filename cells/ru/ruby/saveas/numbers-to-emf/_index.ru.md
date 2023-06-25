---
title:  Сохранить НОМЕРА как EMF API для Ruby
description:  Использование Aspose.Cells Cloud SDK для Ruby для сохранения файла формата NUMBERS как файла формата EMF.
url: /ru/ruby/saveas/numbers-to-emf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API, чтобы сохранить NUMBERS как EMF" h2="Библиотека Ruby для сохранения NUMBERS как EMF" p="Используйте Cells SaveAs REST API для создания настраиваемых рабочих процессов электронных таблиц в Ruby. Это профессиональное решение для сохранения NUMBERS как EMF и других форматов документов в Интернете с использованием Ruby." urlsection="saveas/numbers-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл NUMBERS как EMF в Ruby." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов из NUMBERS как EMF — сложная задача. Все преобразования форматов NUMBERS в EMF выполняются нашим Ruby SDK, при этом сохраняется основное структурное и логическое содержимое исходной электронной таблицы NUMBERS. Наша библиотека Ruby — это профессиональное решение для сохранения файлов NUMBERS в формате EMF онлайн. Этот Cloud SDK предоставляет разработчикам Ruby мощную функциональность и идеальный вывод EMF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода на Ruby с использованием REST API для сохранения NUMBERS в формате EMF" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.numbers'
    save_options = nil
    newfilename = 'Book1Saveas.emf'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Ruby API для сохранения NUMBERS как EMF" >}}
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

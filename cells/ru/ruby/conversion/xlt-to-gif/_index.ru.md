---
title:  Преобразование XLT в GIF API для Ruby
description:  Использование Aspose.Cells Cloud SDK для Ruby для преобразования файла формата XLT в файл формата GIF.
url: /ru/ruby/conversion/xlt-to-gif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API для преобразования XLT в GIF" h2="Библиотека Ruby для преобразования XLT в GIF" p="Используйте Cells Conversion REST API для создания настраиваемых рабочих процессов электронных таблиц в Ruby. Это профессиональное решение для преобразования XLT в GIF и другие форматы документов онлайн с использованием Ruby." urlsection="conversion/xlt-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразование файла XLT в GIF в Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из XLT в GIF — сложная задача. Все переходы форматов XLT в GIF выполняются нашим Ruby SDK, при этом сохраняется основное структурное и логическое содержимое исходной электронной таблицы XLT. Наша библиотека Ruby — это профессиональное решение для онлайн-конвертации файлов XLT в GIF. Этот облачный SDK предоставляет разработчикам Ruby мощные функциональные возможности и идеальный вывод GIF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода на Ruby с использованием REST API для преобразования XLT в формат GIF" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xlt"
            format = 'gif'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Ruby API для преобразования XLT в GIF" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызов ячеек_рабочая тетрадь_помещать_конвертировать_метод рабочей книги для получения результирующего потока</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>рубин 2.5 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

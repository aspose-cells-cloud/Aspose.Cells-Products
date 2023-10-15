---
title:  Преобразуйте XLTX в SVG с помощью Ruby.
description: Использование Cloud SDK Aspose.Cells для Ruby для преобразования файла формата XLTX в файл формата SVG.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Преобразовать XLTX в SVG" h2="Библиотека Ruby для преобразования XLTX в SVG" p="Используйте преобразование API или Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Ruby. Это профессиональное решение для онлайн-конвертации XLTX в SVG и другие форматы документов с помощью Ruby." urlsection="conversion/xltx-to-svg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразуйте XLTX в SVG с помощью Cloud SDK Cells для Ruby." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из XLTX в SVG может оказаться сложной задачей. Наш Ruby SDK обрабатывает все преобразования формата XLTX в SVG, сохраняя при этом основное структурное и логическое содержимое исходной таблицы XLTX. Наша библиотека Ruby предоставляет профессиональное решение для онлайн-конвертации файлов XLTX в SVG. Этот Cloud SDK предоставляет разработчикам Ruby мощные функциональные возможности и обеспечивает высококачественный вывод SVG.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода Ruby для преобразования XLTX в SVG с использованием Cells Cloud SDK" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.xltx"
            format = 'svg'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK для Ruby для преобразования файлов Excel в другие форматы XLTX в SVG" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `put_convert_workbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>рубин 2.5 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

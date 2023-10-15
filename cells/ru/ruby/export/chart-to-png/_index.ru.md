---
title:  Экспортируйте CHART в PNG из Excel с помощью Cells Cloud SDK для Ruby.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Экспортировать CHART в PNG из Excel" h2="Библиотека Ruby для экспорта CHART в файл PNG." p="Используйте команду «Экспорт API из облака Cells» для экспорта рабочих процессов внутренних объектов файлов Excel в Ruby. Это профессиональное решение для экспорта CHART в файл формата PNG из электронной таблицы онлайн с помощью Ruby." urlsection="export/chart-to-png/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Экспортируйте объект CHART в файл формата PNG с помощью Cloud SDK Cells для Ruby." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта CHART в файл PNG из файла Excel — сложная задача. Экспорт переходов формата CHART в формат PNG выполняется нашим Ruby SDK с сохранением основного структурного и логического содержимого исходной таблицы CHART. Наша библиотека Ruby — это профессиональное решение для онлайн-экспорта объектов CHART в файлы формата PNG. Этот Cloud SDK предоставляет разработчикам Ruby мощные функциональные возможности и идеальный результат PNG.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода на Ruby с использованием REST API для экспорта CHART в формат PNG из электронной таблицы" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::LiteCellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            files = {}      
            name = $DataSourceXlsx
            files[name] = ::File.open(File.expand_path("data/"+name),"r") 
            name =$AssemblyTestXlsx 
            files[name] = ::File.open(File.expand_path("data/"+name),"r")
            format = 'png'
            objectType =  'chart'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK для Ruby для экспорта объектов из Excel CHART в PNG" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Вызовите метод post_export, чтобы получить результирующий поток.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>рубин 2.5 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

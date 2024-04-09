---
title:  Экспортируйте PICTURE в JPG из Excel с помощью Cloud SDK Cells для Ruby.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Экспорт ИЗОБРАЖЕНИЯ в JPG из Excel" h2="Библиотека Ruby для экспорта ИЗОБРАЖЕНИЯ в файл JPG." p="Используйте команду «Экспорт API из облака Cells» для экспорта рабочих процессов внутренних объектов файлов Excel в Ruby. Это профессиональное решение для экспорта ИЗОБРАЖЕНИЯ в файл формата JPG из электронной таблицы онлайн с помощью Ruby." urlsection="export/picture-to-jpg/" >}}

{{< blocks/products/cells/cells-cloud-section title="Экспортируйте объект PICTURE в файл формата JPG с помощью Cloud SDK Cells для Ruby." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта PICTURE в файл JPG из файла Excel — сложная задача. Экспорт переходов формата PICTURE в JPG выполняется нашим Ruby SDK с сохранением основного структурного и логического содержимого исходной таблицы PICTURE. Наша библиотека Ruby — это профессиональное решение для онлайн-экспорта объектов PICTURE в файлы формата JPG. Этот Cloud SDK предоставляет разработчикам Ruby мощные функциональные возможности и идеальный вывод в формате JPG.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода на Ruby с использованием REST API для экспорта PICTURE в формат JPG из электронной таблицы" gistPath="" %}}
  
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
            format = 'jpg'
            objectType =  'picture'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK для Ruby для экспорта объектов из Excel PICTURE в JPG." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Вызовите метод post_export, чтобы получить результирующий поток.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>рубин 2.5 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

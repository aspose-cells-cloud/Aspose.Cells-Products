---
title:  Экспорт ИЗОБРАЖЕНИЯ в WMF из электронной таблицы с использованием Ruby API
description:  Aspose.Cells Cloud REST API поддерживает экспорт {0} в файлы формата {1} с использованием {2}.
url: /ru/ruby/export/picture-to-wmf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Ruby API для экспорта ИЗОБРАЖЕНИЯ в файл WMF" h2="Библиотека Ruby для экспорта ИЗОБРАЖЕНИЯ в файл WMF" p="Используйте Cells Export REST API для экспорта рабочих процессов внутренних объектов электронной таблицы в Ruby. Это профессиональное решение для экспорта ИЗОБРАЖЕНИЯ в файл формата WMF из электронной таблицы онлайн с использованием Ruby." urlsection="export/picture-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Экспорт объекта PICTURE в файл формата WMF в Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта PICTURE в файл WMF из электронной таблицы является сложной задачей. Экспорт переходов формата PICTURE в WMF выполняется нашим Ruby SDK, при этом сохраняется основное структурное и логическое содержимое исходной электронной таблицы PICTURE. Наша библиотека Ruby — это профессиональное решение для онлайн-экспорта объектов PICTURE в файлы формата WMF. Этот облачный SDK предоставляет разработчикам Ruby мощные функциональные возможности и идеальный вывод WMF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода на Ruby с использованием REST API для экспорта ИЗОБРАЖЕНИЯ в формат WMF из электронной таблицы" gistPath="" %}}
  
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
            format = 'wmf'
            objectType =  'picture'
            result = @instance.post_export(files  ,objectType ,format)    
        end
    end
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Ruby API для экспорта ИЗОБРАЖЕНИЯ в WMF" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод post_export, чтобы получить результирующий поток</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>рубин 2.5 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

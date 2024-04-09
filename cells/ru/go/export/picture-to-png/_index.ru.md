---
title:  Экспортируйте PICTURE в PNG из Excel с помощью Cells Cloud SDK для Go.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Экспортировать КАРТИНКУ в PNG из Excel" h2="Библиотека Go для экспорта ИЗОБРАЖЕНИЯ в файл PNG." p="Используйте «Экспорт API из Cells Cloud», чтобы экспортировать рабочие процессы внутренних объектов файлов Excel в Go. Это профессиональное решение для экспорта ИЗОБРАЖЕНИЯ в файл формата PNG из электронной таблицы онлайн с помощью Go." urlsection="export/picture-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="Экспортируйте объект PICTURE в файл формата PNG с помощью Cells Cloud SDK for Go." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта PICTURE в файл PNG из файла Excel — сложная задача. Экспорт PICTURE в переходы формата PNG выполняется нашим Go SDK с сохранением основного структурного и логического содержимого исходной таблицы PICTURE. Наша библиотека Go — это профессиональное решение для онлайн-экспорта объектов PICTURE в файлы формата PNG. Этот Cloud SDK предоставляет разработчикам Go мощные функциональные возможности и идеальный вывод PNG.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода на Go с использованием REST API для экспорта PICTURE в формат PNG из электронной таблицы" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    package main
    import (
	    "encoding/base64"
	    "os"
	    asposecellscloud "github.com/aspose-cells-cloud/aspose-cells-cloud-go/v22"
    )
    func main() {
	    instance := asposecellscloud.NewLightCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
	    var files map[string]string
	    files = make(map[string]string)
	    files["Book1.xlsx"] = "C:/Book1.xlsx"
	    files["myDocument.xlsx"] = "C:/myDocument.xlsx"
	    postExportOpts := new(asposecellscloud.PostExportOpts)
	    postExportOpts.ObjectType = "picture"
	    postExportOpts.Format = "png"
	    filesresult, _, err := instance.PostExport(files, postExportOpts)
	    if err != nil {
		    return
	    }
	    print(filesresult.Files[0].Filename)
	    originalStringBytes, err1 := base64.StdEncoding.DecodeString(filesresult.Files[0].FileContent)
	    if err1 != nil {
		    return
	    }
	    f, err2 := os.Create(filesresult.Files[0].Filename)
	    if err2 != nil {
		    return
	    }
	    _, err3 := f.Write(originalStringBytes)
	    if err3 != nil {
		    return
	    }
	    f.Close()
    }
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK для Go для экспорта объектов из Excel PICTURE в PNG" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `postExport` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>версия go go1.13.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

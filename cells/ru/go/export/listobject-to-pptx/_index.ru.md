---
title: Экспортируйте LISTOBJECT в PPTX из Excel с помощью Cloud SDK Cells для Go.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
kwords:
howto:
---
{{< blocks/products/cells/cells-cloud-banner h1="Экспортировать LISTOBJECT в PPTX с номера Excel." h2="Библиотека Go для экспорта LISTOBJECT в файл PPTX" p="Используйте «Экспорт API из Cells Cloud», чтобы экспортировать рабочие процессы внутренних объектов файлов Excel в Go. Это профессиональное решение для экспорта LISTOBJECT в файл формата PPTX из электронной таблицы онлайн с помощью Go." urlsection="export/listobject-to-pptx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Экспортируйте объект LISTOBJECT в файл формата PPTX с помощью Cells Cloud SDK for Go." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта LISTOBJECT в файл PPTX из файла Excel — сложная задача. Экспорт переходов формата LISTOBJECT в PPTX выполняется нашим Go SDK с сохранением основного структурного и логического содержимого исходной таблицы LISTOBJECT. Наша библиотека Go — это профессиональное решение для онлайн-экспорта объектов LISTOBJECT в файлы формата PPTX. Этот Cloud SDK предоставляет разработчикам Go мощные функциональные возможности и идеальный вывод PPTX.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода на Go с использованием REST API для экспорта LISTOBJECT в формат PPTX из электронной таблицы" gistPath="" %}}
  
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
	    postExportOpts.ObjectType = "listobject"
	    postExportOpts.Format = "pptx"
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK для Go для экспорта объектов из Excel LISTOBJECT в PPTX" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `postExport` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>версия go go1.13.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

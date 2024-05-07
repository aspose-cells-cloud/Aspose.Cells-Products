---
title:  Экспортируйте PICTURE в GIF из Excel с помощью Cells Cloud SDK for Go.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
kwords: Excel, picture, gif, Go
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Go to export objects from Excel PICTURE to GIF","description": "How to use Cells Cloud SDK for Go to export objects from Excel PICTURE to GIF","image": {"@type": "ImageObject"},"url": "/go/export/picture-to-gif/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Go to export objects from Excel PICTURE to GIF step 1", "image": {"@type": "ImageObject",},"url": "/go/export/picture-to-gif/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Go to export objects from Excel PICTURE to GIF step 1", "image": {"@type": "ImageObject",},"url": "/go/export/picture-to-gif/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Go to export objects from Excel PICTURE to GIF step 1", "image": {"@type": "ImageObject",},"url": "/go/export/picture-to-gif/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Goland, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Экспортировать КАРТИНКУ в GIF с номера Excel" h2="Библиотека Go для экспорта КАРТИНКИ в файл GIF." p="Используйте «Экспорт API из Cells Cloud», чтобы экспортировать рабочие процессы внутренних объектов файлов Excel в Go. Это профессиональное решение для экспорта ИЗОБРАЖЕНИЯ в файл формата GIF из электронной таблицы онлайн с помощью Go." urlsection="export/picture-to-gif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Экспортируйте объект PICTURE в файл формата GIF с помощью Cloud SDK Cells for Go." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта PICTURE в файл GIF из файла Excel — сложная задача. Экспорт переходов формата PICTURE в GIF выполняется нашим Go SDK с сохранением основного структурного и логического содержимого исходной таблицы PICTURE. Наша библиотека Go — это профессиональное решение для онлайн-экспорта объектов PICTURE в файлы формата GIF. Этот Cloud SDK предоставляет разработчикам Go мощные функциональные возможности и идеальный вывод GIF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода на Go с использованием REST API для экспорта PICTURE в формат GIF из электронной таблицы" gistPath="" %}}
  
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
	    postExportOpts.Format = "gif"
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK для Go для экспорта объектов из Excel PICTURE в GIF." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `postExport` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>версия go go1.13.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

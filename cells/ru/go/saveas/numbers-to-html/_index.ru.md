---
title:  Сохраните ЧИСЛА как HTML с помощью Go.
description:  Использование Aspose.Cells Cloud SDK для Go для сохранения файла формата NUMBERS как файла формата HTML.
kwords: Excel, Save NUMBERS as HTML, REST, Go
howto: How to save NUMBERS as HTML using Aspose.Cells Cloud Go library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Сохранить ЦИФРЫ как HTML" h2="Библиотека Go для сохранения ЧИСЕЛ как HTML" p="Используйте SaveAs API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в Go. Это профессиональное решение для сохранения ЧИСЕЛ как HTML и других форматов документов онлайн с помощью Go." urlsection="saveas/numbers-to-html/" >}}

{{< blocks/products/cells/cells-cloud-section title="Сохраните файл NUMBERS под номером HTML в Go." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение формата файлов из NUMBERS как HTML — сложная задача. Все переходы формата NUMBERS в HTML выполняются нашим Go SDK, сохраняя при этом основное структурное и логическое содержимое исходной таблицы NUMBERS. Наша библиотека Go — это профессиональное решение для сохранения ЧИСЕЛ в виде файлов HTML онлайн. Этот Cloud SDK предоставляет разработчикам Go мощные функциональные возможности и идеальный вывод HTML.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода Go для сохранения ЧИСЕЛ как HTML с использованием REST API" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.numbers"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.html"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как сохранить ЧИСЛА как HTML, используя библиотеку Cloud Go Cells." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Go и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл в go.</li>
<li>Используйте метод `PostWorkbookSaveAs` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>версия go go1.13.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

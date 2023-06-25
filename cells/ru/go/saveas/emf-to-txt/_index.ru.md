---
title:  Сохранить EMF как TXT API для Go
description:  Использование Aspose.Cells Cloud SDK для Go для сохранения файла формата EMF в формате TXT.
url: /ru/go/saveas/emf-to-txt/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Введите API, чтобы сохранить EMF как TXT." h2="Перейти в библиотеку, чтобы сохранить EMF как TXT" p="Используйте Cells SaveAs REST API для создания настраиваемых рабочих процессов электронных таблиц в Go. Это профессиональное решение для сохранения EMF в формате TXT и других форматах документов в Интернете с помощью Go." urlsection="saveas/emf-to-txt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Сохраните файл EMF как TXT в Go" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Сохранение форматов файлов с EMF как TXT — сложная задача. Все переходы формата EMF в формат TXT выполняются нашим SDK Go при сохранении основного структурного и логического содержимого исходной электронной таблицы EMF. Наша библиотека Go — это профессиональное решение для сохранения EMF в виде файлов TXT онлайн. Этот облачный SDK предоставляет разработчикам Go мощные функциональные возможности и идеальный вывод TXT.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Go с использованием REST API для сохранения EMF в формате TXT" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.emf"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.txt"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Go API, чтобы сохранить EMF как TXT" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод CellsSaveAsPostDocumentSaveAs, чтобы получить результирующий поток.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>версия go go1.13.0 или новее</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

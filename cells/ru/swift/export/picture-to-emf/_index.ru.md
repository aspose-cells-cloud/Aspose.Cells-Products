---
title: Экспорт ИЗОБРАЖЕНИЯ в EMF из электронной таблицы с помощью Swift API
description:  Aspose.Cells Cloud REST API поддерживает экспорт {0} в файлы формата {1} с использованием {2}.
url: /ru/swift/export/picture-to-emf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Swift API для экспорта ИЗОБРАЖЕНИЯ в файл EMF" h2="Библиотека Swift для экспорта ИЗОБРАЖЕНИЯ в файл EMF" p="Используйте Cells Export REST API для экспорта рабочих процессов внутренних объектов электронных таблиц в Swift. Это профессиональное решение для экспорта ИЗОБРАЖЕНИЯ в файл формата EMF из электронной таблицы онлайн с использованием Swift." urlsection="export/picture-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Экспорт объекта PICTURE в файл формата EMF в Swift" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта ИЗОБРАЖЕНИЕ в файл EMF из электронной таблицы является сложной задачей. Экспорт ИЗОБРАЖЕНИЯ в переходы формата EMF выполняется нашим Swift SDK, при этом сохраняется основное структурное и логическое содержимое исходной электронной таблицы ИЗОБРАЖЕНИЕ. Наша библиотека Swift — это профессиональное решение для онлайн-экспорта объектов PICTURE в файлы формата EMF. Этот облачный SDK предоставляет разработчикам Swift мощные функциональные возможности и идеальный вывод EMF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Swift с использованием REST API для экспорта ИЗОБРАЖЕНИЯ в формат EMF из электронной таблицы" gistPath="" %}}
  
```swift
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-swift/
    import AsposeCellsCloud
    let expectation1 = self.expectation(description: "checkAuth")
    AsposeCellsCloudAPI.clientId = "xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx"
    AsposeCellsCloudAPI.clientSecret = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
    AuthAspose.checkAuth()
    {
        (authError) in
        guard authError == nil else {
            XCTFail("error checkAuth")
            return
        }
        expectation1.fulfill()
    }
    self.waitForExpectations(timeout: testTimeout, handler: nil)
    let expectation = self.expectation(description: "testpostExport_Workbook")
    let objectType:String = "picture"
    let format:String = "emf"
    var files = Dictionary<String, URL>()
    files[BOOK1] = getURL(BOOK1)
    files[MYDOC] = getURL(MYDOC)        
    LiteCellsAPI.postExport(files: files, objectType: objectType, format: format)
    {
        (response, error) in
        guard error == nil else {
            XCTFail("error testpostExport_Workbook")
            return
        }        
        if let response = response {
            XCTAssertTrue(response is FilesResult)
            expectation.fulfill()
        }
    }
    self.waitForExpectations(timeout: testTimeout, handler: nil)
```
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Swift API для экспорта ИЗОБРАЖЕНИЯ в EMF" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод postExport, чтобы получить результирующий поток</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

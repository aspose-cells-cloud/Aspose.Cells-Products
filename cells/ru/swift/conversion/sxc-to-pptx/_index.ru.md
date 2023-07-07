---
title:  Преобразование SXC в PPTX API для Swift
description:  Использование Aspose.Cells Cloud SDK для Swift для преобразования файла формата SXC в файл формата PPTX.
url: /ru/swift/conversion/sxc-to-pptx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Swift API для преобразования SXC в PPTX" h2="Библиотека Swift для преобразования SXC в PPTX" p="Используйте Cells Conversion REST API для создания настраиваемых рабочих процессов электронных таблиц в Swift. Это профессиональное решение для онлайн-конвертации SXC в PPTX и другие форматы документов с использованием Swift." urlsection="conversion/sxc-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразование файла SXC в PPTX в Swift" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из SXC в PPTX — сложная задача. Все переходы формата SXC в формат PPTX выполняются нашим Swift SDK, при этом сохраняется основное структурное и логическое содержимое исходной электронной таблицы SXC. Наша библиотека Swift — это профессиональное решение для онлайн-конвертации файлов SXC в PPTX. Этот облачный SDK предоставляет разработчикам Swift мощные функциональные возможности и идеальный вывод PPTX.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Swift с использованием REST API для преобразования SXC в формат PPTX" gistPath="" %}}
 
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
    let expectation = self.expectation(description: "PutConvert")
    let workbook:String = "Book1.sxc"
    let format:String? = "pptx"     
    let url1: URL? = getURL(workbook)
    let filedata = NSData(contentsOfFile: url1!.path)
    let password:String? = nil
    let outPath:String? = nil
    CellsAPI.cellsWorkbookPutConvertWorkbook(file: url1!, format: format, password: password, outPath: outPath)
    {
        (response, error) in
        guard error == nil else {
            let errorinfo = self.GetErrorDataInfo(error: error as! ErrorResponse)
            print("error info: \(errorinfo!)")
            XCTFail("error PutConvert")
            return
        }            
        if let response = response {
            //response is a Data of file, we may write it down and check it.
            let fileName = "dest.pptx"
            let filePath = NSHomeDirectory()
            let fileManager = FileManager.default
            let path = "\(filePath)/tmp/\(fileName)"
            fileManager.createFile(atPath: path, contents:nil, attributes:nil)
            let handle = FileHandle(forWritingAtPath:path)
            handle?.write(response as Data)
            expectation.fulfill()
        }
    }
    self.waitForExpectations(timeout: testTimeout, handler: nil)
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Swift API для преобразования SXC в PPTX" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод CellsWorkbookPutConvertWorkbook, чтобы получить результирующий поток</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>macOS Монтерей 12.4</li>
<li>Свифт 4.2</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

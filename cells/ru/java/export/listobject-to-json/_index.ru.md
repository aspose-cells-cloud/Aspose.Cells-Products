---
title:  Экспортируйте LISTOBJECT в JSON из Excel с помощью Cells Cloud SDK for Java.
description:  Aspose.Cells Cloud REST API поддерживает экспорт файлов формата {0} в {1} с помощью {2}.
kwords: Excel, listobject, json, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Java to export objects from Excel LISTOBJECT to JSON","description": "How to use Cells Cloud SDK for Java to export objects from Excel LISTOBJECT to JSON","image": {"@type": "ImageObject"},"url": "/java/export/listobject-to-json/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel LISTOBJECT to JSON step 1", "image": {"@type": "ImageObject",},"url": "/java/export/listobject-to-json/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel LISTOBJECT to JSON step 1", "image": {"@type": "ImageObject",},"url": "/java/export/listobject-to-json/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel LISTOBJECT to JSON step 1", "image": {"@type": "ImageObject",},"url": "/java/export/listobject-to-json/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="Экспорт LISTOBJECT в JSON из Excel" h2="Java библиотека для экспорта LISTOBJECT в файл JSON" p="Используйте экспорт API из Cells Cloud для экспорта рабочих процессов внутренних объектов файла Excel в Java. Это профессиональное решение для экспорта LISTOBJECT в файл формата JSON из электронной таблицы онлайн с использованием Java." urlsection="export/listobject-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section title="Экспортируйте объект LISTOBJECT в файл формата JSON с помощью Cloud SDK Cells for Java." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта LISTOBJECT в файл JSON из файла Excel — сложная задача. Экспорт переходов формата LISTOBJECT в JSON выполняется нашим SDK Java с сохранением основного структурного и логического содержимого исходной таблицы LISTOBJECT. Наша библиотека Java — это профессиональное решение для онлайн-экспорта объектов LISTOBJECT в файлы формата JSON. Этот Cloud SDK предоставляет разработчикам Java мощные функциональные возможности и идеальный вывод JSON.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода Java с использованием REST API для экспорта LISTOBJECT в формат JSON из электронной таблицы" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.*;
    import java.util.HashMap;
    import java.util.List;
    import java.util.Base64;
    import com.aspose.cloud.cells.api.*;
    import com.aspose.cloud.cells.model.*;
    public class Export {
        public static void main(String[] args) {
            String format = "json";
            String objectType = "listobject";
            HashMap<String,File> fileMap = new HashMap<String,File>();
            fileMap.put("Book1.xlsx" ,new File("C:\Book1.xlsx") );
            fileMap.put("myDocument.xlsx" ,new File("C:\myDocument.xlsx") );
            try {
                LightCellsApi cellsApi = new LightCellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"),"v3.0","https://api.aspose.cloud");
                FilesResult response = cellsApi.postExport(fileMap,objectType, format,null);            
                List<FileInfo> files = response.getFiles();
                String filename = files.get(0).getFilename();
                String fileContent = files.get(0).getFileContent();
                byte[] data = Base64.getDecoder().decode(fileContent);
                OutputStream outputStream = new FileOutputStream(filename);
                outputStream.write(data,0,data.length);
                outputStream.close();
            }catch(Exception exception )
            {
                System.out.print(exception);
            }
        }
    }
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK for Java для экспорта объектов из Excel LISTOBJECT в JSON." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `postExport` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Maven 2.2.0 или новее</li>
<li>Java(TM) Среда выполнения SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

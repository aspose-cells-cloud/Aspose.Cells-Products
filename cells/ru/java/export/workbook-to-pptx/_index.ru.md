---
title:  Экспорт WORKBOOK в PPTX из электронной таблицы с использованием Java API
description:  Aspose.Cells Cloud REST API поддерживает экспорт {0} в файлы формата {1} с использованием {2}.
url: /ru/java/export/workbook-to-pptx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API для экспорта WORKBOOK в файл PPTX" h2="Java библиотека для экспорта WORKBOOK в файл PPTX" p="Используйте Cells Export REST API для экспорта рабочих процессов внутренних объектов электронной таблицы в Java. Это профессиональное решение для экспорта файла формата WORKBOOK в PPTX из электронной таблицы онлайн с использованием Java." urlsection="export/workbook-to-pptx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Экспорт объекта WORKBOOK в файл формата PPTX в Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
Экспорт объекта WORKBOOK в файл PPTX из электронной таблицы — сложная задача. Экспорт переходов WORKBOOK в формат PPTX выполняется нашим SDK Java, при этом сохраняется основное структурное и логическое содержимое исходной электронной таблицы WORKBOOK. Наша библиотека Java — это профессиональное решение для онлайн-экспорта объектов WORKBOOK в файлы формата PPTX. Этот облачный SDK предоставляет Java разработчикам мощную функциональность и идеальный вывод PPTX.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Java с использованием REST API для экспорта WORKBOOK в формат PPTX из электронной таблицы" gistPath="" %}}
  
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
            String format = "pptx";
            String objectType = "workbook";
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
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Java API для экспорта WORKBOOK в PPTX" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод postExport, чтобы получить результирующий поток</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Maven 2.2.0 или новее</li>
<li>Java(TM) Среда выполнения SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

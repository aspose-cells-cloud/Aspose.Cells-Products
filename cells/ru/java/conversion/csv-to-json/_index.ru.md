---
title:  Преобразование CSV в JSON API for Java
description: Использование Aspose.Cells Cloud SDK for Java для преобразования файла формата CSV в файл формата JSON.
url: /ru/java/conversion/csv-to-json/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API для преобразования CSV в JSON" h2="Java библиотека для преобразования CSV в JSON" p="Используйте Cells Преобразование REST API для создания настраиваемых рабочих процессов электронных таблиц в Java. Это профессиональное решение для онлайн-конвертации CSV в JSON и другие форматы документов с использованием Java." urlsection="conversion/csv-to-json/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразование файла CSV в JSON в Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из CSV в JSON — сложная задача. Все переходы между форматами CSV и JSON выполняются нашим SDK Java с сохранением основного структурного и логического содержимого исходной электронной таблицы CSV. Наша библиотека Java — это профессиональное решение для онлайн-конвертации файлов CSV в JSON. Этот Cloud SDK предоставляет Java разработчикам мощные функциональные возможности и превосходный вывод в формате JSON.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Java с использованием REST API для преобразования CSV в формат JSON" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.csv";
            String format = "json";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.json";
            try {
                CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
                File response = cellsApi.cellsWorkbookPutConvertWorkbook(new File(name), format, password, outPath, null,null);            
                if(response.canRead())
                {
                    if(response.exists()){
                        response.renameTo(new File(destFile));
                    }                
                }
            }
            catch(Exception exception )
            {
                System.out.print(exception);
            }
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Java API для преобразования CSV в JSON" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод CellsWorkbookPutConvertWorkbook, чтобы получить результирующий поток</li>
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

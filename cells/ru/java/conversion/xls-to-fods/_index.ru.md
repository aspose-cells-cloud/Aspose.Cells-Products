﻿---
title:  Преобразование XLS в FODS API for Java
description:  Облачные API и SDK для Microsoft Excel и OpenOffice Calc. Преобразование электронной таблицы в файл другого формата.
url: /ru/java/conversion/xls-to-fods/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API для преобразования XLS в FODS" h2="Java библиотека для преобразования XLS в FODS" p="Используйте Cells Conversion REST API для создания настраиваемых рабочих процессов электронных таблиц в Java. Это профессиональное решение для онлайн-конвертации XLS в FODS и другие форматы документов с использованием Java." urlsection="conversion/xls-to-fods/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразуйте файл XLS в FODS по номеру Java." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из XLS в FODS — сложная задача. Все переходы между форматами XLS и FODS выполняются нашим SDK Java при сохранении основного структурного и логического содержимого исходной электронной таблицы XLS. Наша библиотека Java — это профессиональное решение для онлайн-конвертации файлов XLS в FODS. Этот облачный SDK предоставляет разработчикам Java мощную функциональность и идеальный результат FODS.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Java с использованием REST API для преобразования XLS в формат FODS" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xls";
            String format = "fods";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.fods";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Java API для преобразования XLS в FODS" >}}
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
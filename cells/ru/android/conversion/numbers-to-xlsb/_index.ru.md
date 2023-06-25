---
title:  Конвертировать NUMBERS в XLSB API для Android
description:  Использование Aspose.Cells Cloud SDK для Android для преобразования файла формата NUMBERS в файл формата XLSB.
url: /ru/android/conversion/numbers-to-xlsb/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API для преобразования NUMBERS в XLSB" h2="Библиотека Android для преобразования NUMBERS в XLSB" p="Используйте Cells Conversion REST API для создания настраиваемых рабочих процессов электронных таблиц в Android. Это профессиональное решение для преобразования NUMBERS в XLSB и другие форматы документов онлайн с помощью Android." urlsection="conversion/numbers-to-xlsb/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразование файла NUMBERS в XLSB на Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из NUMBERS в XLSB — сложная задача. Все преобразования формата NUMBERS в формат XLSB выполняются нашим Android SDK с сохранением основного структурного и логического содержимого исходной электронной таблицы NUMBERS. Наша библиотека Android — это профессиональное решение для онлайн-конвертации файлов NUMBERS в XLSB. Этот облачный SDK предоставляет разработчикам Android мощную функциональность и идеальный вывод XLSB.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода в Android с использованием REST API для преобразования NUMBERS в формат XLSB" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.numbers";
                String format = "xlsb";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.xlsb";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Java API для преобразования NUMBERS в XLSB" >}}
<li> Создайте учетную запись на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы получить бесплатную информацию о квоте и авторизации API</li>
<li>Инициализировать CellsApi с идентификатором клиента, секретом клиента, базовым URL-адресом и версией API.</li>
<li>Вызовите метод CellsWorkbookPutConvertWorkbook, чтобы получить результирующий поток</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Андроид 7 или новее</li>
<li>Java(TM) Среда выполнения SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

---
title:  Конвертируйте MHTML в XLT с помощью Android
description: Использование Cloud SDK Aspose.Cells для Android для преобразования файла формата MHTML в файл формата XLT.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Конвертировать MHTML в XLT" h2="Библиотека Android для преобразования MHTML в XLT" p="Используйте преобразование API или Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Android. Это профессиональное решение для онлайн-конвертирования MHTML в XLT и другие форматы документов с помощью Android." urlsection="conversion/mhtml-to-xlt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразование MHTML в XLT с помощью Cloud SDK Cells для Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из MHTML в XLT может оказаться сложной задачей. Наш Android SDK обрабатывает все преобразования формата MHTML в XLT, сохраняя при этом основное структурное и логическое содержимое исходной электронной таблицы MHTML. Наша библиотека Android предоставляет профессиональное решение для онлайн-конвертирования файлов MHTML в XLT. Этот Cloud SDK предоставляет разработчикам Android мощные функциональные возможности и обеспечивает высококачественный вывод XLT.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Пример кода Android для преобразования MHTML в XLT с использованием Cloud SDK Cells" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.mhtml";
                String format = "xlt";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.xlt";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK для Android для преобразования файлов Excel в другие форматы MHTML в XLT" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `putConvertWorkbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Android 7 или новее</li>
<li>Java(TM) Среда выполнения SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

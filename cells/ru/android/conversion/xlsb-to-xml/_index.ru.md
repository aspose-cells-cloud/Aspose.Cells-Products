---
title:  Конвертируйте XLSB в XML с помощью Android
description:  Использование Cloud SDK Aspose.Cells для Android для преобразования файла формата XLSB в файл формата XML.
kwords: Excel, Convert XLSB to XML, REST, Android
howto: How to convert XLSB to XML using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Конвертировать XLSB в XML" h2="Библиотека Android для преобразования XLSB в XML" p="Используйте преобразование API или Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Android. Это профессиональное решение для онлайн-конвертирования XLSB в XML и другие форматы документов с помощью Android." urlsection="conversion/xlsb-to-xml/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразование XLSB в XML с помощью Cloud SDK Cells для Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из XLSB в XML может оказаться сложной задачей. Наш Android SDK обрабатывает все преобразования формата XLSB в XML, сохраняя при этом основное структурное и логическое содержимое исходной электронной таблицы XLSB. Наша библиотека Android предоставляет профессиональное решение для онлайн-конвертирования файлов XLSB в XML. Этот Cloud SDK предоставляет разработчикам Android мощные функциональные возможности и обеспечивает высококачественный вывод XML.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода Android для преобразования XLSB в XML с помощью Cloud SDK Cells" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xlsb";
                String format = "xml";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.xml";
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
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK для Android для преобразования файлов Excel в другие форматы" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `putConvertWorkbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Android 7 или новее</li>
<li>Java(TM) Среда выполнения SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

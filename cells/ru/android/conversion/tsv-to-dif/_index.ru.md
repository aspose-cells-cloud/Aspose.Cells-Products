---
title:  Конвертируйте TSV в DIF с помощью Android
description:  Использование Cloud SDK Aspose.Cells для Android для преобразования файла формата TSV в файл формата DIF.
kwords: Excel, Convert TSV to DIF, REST, Android
howto: How to convert TSV to DIF using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Конвертировать TSV в DIF" h2="Библиотека Android для преобразования TSV в DIF" p="Используйте преобразование API или Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Android. Это профессиональное решение для конвертации TSV в DIF и другие форматы документов онлайн с помощью Android." urlsection="conversion/tsv-to-dif/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразование TSV в DIF с помощью Cells Cloud SDK для Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из TSV в DIF может оказаться сложной задачей. Наш Android SDK обрабатывает все преобразования формата TSV в DIF, сохраняя при этом основное структурное и логическое содержимое исходной таблицы TSV. Наша библиотека Android предоставляет профессиональное решение для онлайн-конвертирования файлов TSV в DIF. Этот Cloud SDK предоставляет разработчикам Android мощные функциональные возможности и обеспечивает высококачественный вывод DIF.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода Android для преобразования TSV в DIF с использованием Cloud SDK Cells" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.tsv";
                String format = "dif";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.dif";
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

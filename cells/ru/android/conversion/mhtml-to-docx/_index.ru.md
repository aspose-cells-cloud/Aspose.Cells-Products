---
title:  Конвертируйте MHTML в DOCX с помощью Android
description: Использование Cloud SDK Aspose.Cells для Android для преобразования файла формата MHTML в файл формата DOCX.
kwords: Excel, Convert MHTML to DOCX, REST, Android
howto: How to convert MHTML to DOCX using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Конвертировать MHTML в DOCX" h2="Библиотека Android для преобразования MHTML в DOCX" p="Используйте преобразование API или Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Android. Это профессиональное решение для онлайн-конвертирования MHTML в DOCX и другие форматы документов с помощью Android." urlsection="conversion/mhtml-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразование MHTML в DOCX с помощью Cloud SDK Cells для Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из MHTML в DOCX может оказаться сложной задачей. Наш Android SDK обрабатывает все преобразования форматов MHTML в DOCX, сохраняя при этом основное структурное и логическое содержимое исходной электронной таблицы MHTML. Наша библиотека Android предоставляет профессиональное решение для онлайн-конвертирования файлов MHTML в DOCX. Этот Cloud SDK предоставляет разработчикам Android мощные функциональные возможности и обеспечивает высококачественный вывод в формате DOCX.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Пример кода Android для преобразования MHTML в DOCX с использованием Cloud SDK Cells" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.mhtml";
                String format = "docx";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.docx";
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

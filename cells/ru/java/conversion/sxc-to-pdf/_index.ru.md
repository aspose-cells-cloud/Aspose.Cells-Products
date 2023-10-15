---
title:  Преобразуйте SXC в PDF, используя Java.
description:  Использование Cloud SDK Aspose.Cells for Java для преобразования файла формата SXC в файл формата PDF.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Преобразовать SXC в PDF" h2="Java библиотека для конвертации SXC в PDF" p="Используйте преобразование API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Java. Это профессиональное решение для онлайн-конвертирования SXC в PDF и другие форматы документов с использованием Java." urlsection="conversion/sxc-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Преобразуйте SXC в PDF с помощью Cells Cloud SDK for Java." >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из SXC в PDF может оказаться сложной задачей. Наш SDK Java обрабатывает все преобразования формата SXC в PDF, сохраняя при этом основное структурное и логическое содержимое исходной электронной таблицы SXC. Наша библиотека Java предоставляет профессиональное решение для онлайн-конвертации файлов SXC в PDF. Этот Cloud SDK предоставляет разработчикам Java мощные функциональные возможности и обеспечивает высококачественный результат PDF.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java Пример кода для преобразования SXC в PDF с использованием Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.sxc";
            String format = "pdf";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.pdf";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Как использовать Cells Cloud SDK for Java для преобразования файлов Excel в другие форматы SXC в PDF" >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Инициализируйте Cells API, указав свой идентификатор клиента, секрет клиента, базовый URL-адрес и версию API.</li>
<li>Используйте метод `putConvertWorkbook` для получения результирующего потока.</li>
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

---
title:  Конвертируйте TXT в XLSX, используя Java.
description:  Использование Cloud SDK Aspose.Cells for Java для преобразования файла формата TXT в файл формата XLSX.
kwords: Excel, Convert TXT to XLSX, REST, Java
howto: How to convert TXT to XLSX using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Конвертировать TXT в XLSX" h2="Java библиотека для конвертации TXT в XLSX" p="Используйте преобразование API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Java. Это профессиональное решение для онлайн-конвертации TXT в XLSX и другие форматы документов с использованием номера Java." urlsection="conversion/txt-to-xlsx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразование TXT в XLSX с помощью Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из TXT в XLSX может оказаться сложной задачей. Наш SDK Java обрабатывает все преобразования форматов TXT в XLSX, сохраняя при этом основное структурное и логическое содержимое исходной таблицы TXT. Наша библиотека Java предоставляет профессиональное решение для онлайн-конвертирования файлов TXT в XLSX. Этот Cloud SDK предоставляет разработчикам Java мощные функциональные возможности и обеспечивает высококачественный вывод в формате XLSX.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Пример кода для преобразования TXT в XLSX с помощью Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.txt";
            String format = "xlsx";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.xlsx";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как конвертировать TXT в XLSX с помощью библиотеки Cells Cloud Java." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Java и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру Java.</li>
<li>Используйте метод `putConvertWorkbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Maven 2.2.0 или новее</li>
<li>Java(TM) Среда выполнения SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

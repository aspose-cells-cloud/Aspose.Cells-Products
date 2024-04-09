---
title:  Конвертируйте XLSX в MD, используя Java.
description:  Использование Cloud SDK Aspose.Cells for Java для преобразования файла формата XLSX в файл формата MD.
kwords: Excel, Convert XLSX to MD, REST, Java
howto: How to convert XLSX to MD using Aspose.Cells Cloud Java library.
---
{{< blocks/products/cells/cells-cloud-banner h1="Конвертировать XLSX в MD" h2="Java библиотека для конвертации XLSX в MD" p="Используйте преобразование API из Cells Cloud для создания настраиваемых рабочих процессов с электронными таблицами в проектах Java. Это профессиональное решение для онлайн-конвертации XLSX в MD и другие форматы документов с помощью номера Java." urlsection="conversion/xlsx-to-md/" >}}

{{< blocks/products/cells/cells-cloud-section title="Преобразование XLSX в MD с помощью Cloud SDK Cells for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Преобразование форматов файлов из XLSX в MD может оказаться сложной задачей. Наш SDK Java обрабатывает все преобразования форматов XLSX в MD, сохраняя при этом основное структурное и логическое содержимое исходной электронной таблицы XLSX. Наша библиотека Java предоставляет профессиональное решение для онлайн-конвертации файлов XLSX в MD. Этот Cloud SDK предоставляет разработчикам Java мощные функциональные возможности и обеспечивает высококачественный вывод MD.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java Пример кода для преобразования XLSX в MD с помощью Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.xlsx";
            String format = "md";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.md";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Узнайте, как конвертировать XLSX в MD с помощью библиотеки Cells Cloud Java." >}}
<li> Зарегистрируйте аккаунт на<a href="https://dashboard.aspose.cloud/">Панель приборов</a> чтобы бесплатно получить информацию о квоте и авторизации по номеру API</li>
<li>Установите библиотеку Java и добавьте ссылку (импортируйте библиотеку) в свой проект.</li>
<li>Откройте исходный файл по номеру Java.</li>
<li>Используйте метод `putConvertWorkbook` для получения результирующего потока.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Системные Требования" >}}
<li>Maven 2.2.0 или новее</li>
<li>Java(TM) Среда выполнения SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

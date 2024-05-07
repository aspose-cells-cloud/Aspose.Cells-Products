---
title:  تحويل HTML إلى TSV باستخدام Java
description:  استخدام Aspose.Cells Cloud SDK for Java لتحويل ملف بتنسيق HTML إلى ملف بتنسيق TSV.
kwords: Excel, Convert HTML to TSV, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert HTML to TSV using the Cells Cloud Java library.","description": "How to convert HTML to TSV using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/conversion/html-to-tsv/","step": [{ "@type": "HowToStep","name": "How to convert HTML to TSV using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/html-to-tsv/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert HTML to TSV using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/html-to-tsv/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert HTML to TSV using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/html-to-tsv/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to convert HTML to TSV using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/conversion/html-to-tsv/","text": "Use the `putConvertWorkbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل HTML إلى TSV" h2="مكتبة Java لتحويل HTML إلى TSV" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Java. يعد هذا حلاً احترافيًا لتحويل HTML إلى TSV وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Java." urlsection="conversion/html-to-tsv/" >}}

{{< blocks/products/cells/cells-cloud-section title="تحويل HTML إلى TSV باستخدام Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من HTML إلى TSV مهمة معقدة. يتعامل Java SDK الخاص بنا مع جميع تحويلات تنسيق HTML إلى TSV مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات HTML المصدر. توفر مكتبتنا Java حلاً احترافيًا لتحويل HTML إلى ملفات TSV عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Java من خلال وظائف قوية ويضمن إخراج TSV عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java مثال على الكود لتحويل HTML إلى TSV باستخدام Cells Cloud SDK" gistPath="" %}}
 
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.File;
    import com.aspose.cloud.cells.api.*;
    public class Conversion {
        public static void main(String[] args) {
            String name =  "Book1.html";
            String format = "tsv";
            String password = null;
            String outPath = null;
            String destFile = "DestFile.tsv";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية تحويل HTML إلى TSV باستخدام مكتبة Cells Cloud Java." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة Java وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في Java.</li>
<li>استخدم طريقة `putConvertWorkbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Maven 2.2.0 أو أحدث</li>
<li>Java(TM) بيئة التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

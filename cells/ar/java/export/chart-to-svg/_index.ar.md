---
title:  تصدير الرسم البياني إلى SVG من Excel باستخدام Cells Cloud SDK for Java
description:  Aspose.Cells Cloud REST API يدعم تصدير الملفات بتنسيق {0} إلى {1} باستخدام {2}.
kwords: Excel, chart, svg, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Java to export objects from Excel CHART to SVG","description": "How to use Cells Cloud SDK for Java to export objects from Excel CHART to SVG","image": {"@type": "ImageObject"},"url": "/java/export/chart-to-svg/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel CHART to SVG step 1", "image": {"@type": "ImageObject",},"url": "/java/export/chart-to-svg/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel CHART to SVG step 1", "image": {"@type": "ImageObject",},"url": "/java/export/chart-to-svg/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Java to export objects from Excel CHART to SVG step 1", "image": {"@type": "ImageObject",},"url": "/java/export/chart-to-svg/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="تصدير الرسم البياني إلى SVG من Excel" h2="مكتبة Java لتصدير الرسم البياني إلى ملف SVG" p="استخدم تصدير API من Cells Cloud لتصدير سير عمل الكائن الداخلي للملف Excel في Java. يعد هذا حلاً احترافيًا لتصدير CHART إلى ملف بتنسيق SVG من جدول البيانات عبر الإنترنت باستخدام Java." urlsection="export/chart-to-svg/" >}}

{{< blocks/products/cells/cells-cloud-section title="تصدير كائن CHART إلى ملف بتنسيق SVG باستخدام Cells Cloud SDK for Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن CHART إلى ملف SVG من ملف Excel مهمة معقدة. يتم تنفيذ انتقالات تنسيق تصدير CHART إلى تنسيق SVG بواسطة Java SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات CHART المصدر. تعد مكتبتنا Java حلاً احترافيًا لتصدير كائنات CHART إلى ملفات بتنسيق SVG عبر الإنترنت. يمنح Cloud SDK هذا مطوري Java وظائف قوية وإخراج SVG مثاليًا.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="مثال على الكود في Java باستخدام REST API لتصدير CHART إلى تنسيق SVG من جدول البيانات" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    import java.io.*;
    import java.util.HashMap;
    import java.util.List;
    import java.util.Base64;
    import com.aspose.cloud.cells.api.*;
    import com.aspose.cloud.cells.model.*;
    public class Export {
        public static void main(String[] args) {
            String format = "svg";
            String objectType = "chart";
            HashMap<String,File> fileMap = new HashMap<String,File>();
            fileMap.put("Book1.xlsx" ,new File("C:\Book1.xlsx") );
            fileMap.put("myDocument.xlsx" ,new File("C:\myDocument.xlsx") );
            try {
                LightCellsApi cellsApi = new LightCellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"),"v3.0","https://api.aspose.cloud");
                FilesResult response = cellsApi.postExport(fileMap,objectType, format,null);            
                List<FileInfo> files = response.getFiles();
                String filename = files.get(0).getFilename();
                String fileContent = files.get(0).getFileContent();
                byte[] data = Base64.getDecoder().decode(fileContent);
                OutputStream outputStream = new FileOutputStream(filename);
                outputStream.write(data,0,data.length);
                outputStream.close();
            }catch(Exception exception )
            {
                System.out.print(exception);
            }
        }
    }
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK for Java لتصدير الكائنات من Excel CHART إلى SVG" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `postExport` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Maven 2.2.0 أو أحدث</li>
<li>Java(TM) بيئة التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

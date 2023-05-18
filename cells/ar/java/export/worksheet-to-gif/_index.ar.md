﻿---
title:  قم بتصدير ورقة العمل إلى GIF من جدول البيانات باستخدام Java API
description:  Aspose.Cells Cloud REST API يدعم تصدير ملف Excel وكائنات داخلية لأنواع ملفات النسق. SDK يدعم أنواع لغات التطوير. وهي تشمل Android و C# و Go و Java و NodeJS و Perl و PHP و Python و Ruby و swift.
url: /ar/java/export/worksheet-to-gif/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Java API لتصدير ورقة العمل إلى ملف GIF" h2="مكتبة Java لتصدير ورقة العمل إلى ملف GIF" p="استخدم Cells Export REST API لتصدير مهام سير عمل الكائنات الداخلية لجدول البيانات في Java. هذا حل احترافي لتصدير WORKSHEET إلى ملف بتنسيق GIF من جدول بيانات عبر الإنترنت باستخدام Java." urlsection="export/worksheet-to-gif/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تصدير كائن WORKSHEET إلى ملف بتنسيق GIF في Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن WORKSHEET إلى ملف GIF من جدول البيانات مهمة معقدة. يتم تنفيذ انتقالات تصدير ورقة العمل إلى تنسيق GIF بواسطة Java SDK مع الحفاظ على المحتوى الإنشائي والمنطقي الرئيسي لجدول بيانات WORKSHEET المصدر. تعتبر مكتبة Java الخاصة بنا حلاً احترافيًا لتصدير كائنات WORKSHEET إلى ملفات بتنسيق GIF عبر الإنترنت. يوفر Cloud SDK للمطورين Java وظائف قوية وإخراج GIF مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Java باستخدام REST API لتصدير WORKSHEET إلى تنسيق GIF من جدول البيانات" gistPath="" %}}
  
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
            String format = "gif";
            String objectType = "worksheet";
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
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Java API لتصدير ورقة العمل إلى GIF" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>استدعاء طريقة postExport للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Maven 2.2.0 أو أحدث</li>
<li>Java (TM) بيئة وقت التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
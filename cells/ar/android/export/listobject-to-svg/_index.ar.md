---
title:  تصدير LISTOBJECT إلى SVG من Excel باستخدام Cells Cloud SDK لنظام Android
description:  Aspose.Cells Cloud REST API يدعم تصدير الملفات بتنسيق {0} إلى {1} باستخدام {2}.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تصدير LISTOBJECT إلى SVG من Excel" h2="مكتبة Android لتصدير LISTOBJECT إلى ملف SVG" p="استخدم تصدير API من Cells Cloud لتصدير سير عمل الكائن الداخلي للملف Excel في Android. يعد هذا حلاً احترافيًا لتصدير ملف LISTOBJECT إلى ملف بتنسيق SVG من جدول البيانات عبر الإنترنت باستخدام Android." urlsection="export/listobject-to-svg/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="تصدير كائن LISTOBJECT إلى ملف بتنسيق SVG باستخدام Cells Cloud SDK لنظام Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
يعد تصدير كائن LISTOBJECT إلى ملف SVG من ملف Excel مهمة معقدة. يتم تنفيذ انتقالات تنسيق تصدير LISTOBJECT إلى SVG بواسطة Android SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات LISTOBJECT المصدر. تعد مكتبة Android الخاصة بنا حلاً احترافيًا لتصدير كائنات LISTOBJECT إلى ملفات بتنسيق SVG عبر الإنترنت. يوفر Cloud SDK لمطوري Android وظائف قوية وإخراجًا مثاليًا SVG.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال على التعليمات البرمجية في Android باستخدام REST API لتصدير LISTOBJECT إلى تنسيق SVG من جدول البيانات" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    import java.io.*;
    import java.util.HashMap;
    import java.util.List;
    import java.util.Base64;
    import com.aspose.cloud.cells.api.*;
    import com.aspose.cloud.cells.model.*;
    public class Export {
        public static void main(String[] args) {
            String format = "svg";
            String objectType = "listobject";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Cells Cloud SDK لنظام Android لتصدير الكائنات من Excel LISTOBJECT إلى SVG" >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتهيئة Cells API باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API.</li>
<li>استخدم طريقة `postExport` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>أندرويد 7 أو الأحدث</li>
<li>Java(TM) بيئة التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

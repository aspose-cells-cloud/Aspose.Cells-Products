---
title:  XML إلى PDF تحويل API لنظام Android
description:  استخدام Aspose.Cells Cloud SDK لنظام Android لتحويل ملف تنسيق XML إلى ملف بتنسيق PDF.
url: /ar/android/conversion/xml-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Android API لتحويل XML إلى PDF" h2="مكتبة Android لتحويل XML إلى PDF" p="استخدم Cells Conversion REST API لإنشاء مسارات عمل جداول بيانات مخصصة في Android. هذا حل احترافي لتحويل XML إلى PDF وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Android." urlsection="conversion/xml-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="قم بتحويل ملف XML إلى PDF في Android" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يعد تحويل تنسيقات الملفات من XML إلى PDF مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق XML إلى PDF بواسطة Android SDK مع الحفاظ على المحتوى البنيوي والمنطقي الرئيسي لجدول بيانات XML المصدر. تعد مكتبة Android الخاصة بنا حلاً احترافيًا لتحويل XML إلى ملفات PDF عبر الإنترنت. يوفر Cloud SDK لمطوري Android وظائف قوية وإخراج PDF مثالي.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="مثال رمز في Android باستخدام REST API لتحويل XML إلى تنسيق PDF" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xml";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية استخدام Java API لتحويل XML إلى PDF" >}}
<li> قم بإنشاء حساب على<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والتفويض API المجانية</li>
<li>تهيئة CellsApi باستخدام معرف العميل وسر العميل وعنوان URL الأساسي وإصدار API</li>
<li>استدعاء طريقة cellWorkbookPutConvertWorkbook للحصول على الدفق الناتج</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Android 7 أو أحدث</li>
<li>Java (TM) بيئة وقت التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

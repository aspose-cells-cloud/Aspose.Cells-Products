---
title:  احفظ XLSM كـ PNG باستخدام Java
description:  استخدام Aspose.Cells Cloud SDK for Java لحفظ ملف بتنسيق XLSM كملف بتنسيق PNG.
kwords: Excel, Save XLSM as PNG, REST, Java
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLSM as PNG using the Cells Cloud Java library.","description": "How to save XLSM as PNG using the Cells Cloud Java library.","image": {"@type": "ImageObject"},"url": "/java/saveas/xlsm-to-png/","step": [{ "@type": "HowToStep","name": "How to save XLSM as PNG using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/xlsm-to-png/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLSM as PNG using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/xlsm-to-png/","text": "Install Java library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLSM as PNG using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/xlsm-to-png/","text": "Open the source file in Java.",},{ "@type": "HowToStep","name": "How to save XLSM as PNG using the Cells Cloud Java library. step 1", "image": {"@type": "ImageObject",},"url": "/java/saveas/xlsm-to-png/","text": "Use the `postWorkbookSaveAs` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "IntelliJ IDEA, Visual Studio Code, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="احفظ XLSM كـ PNG" h2="مكتبة Java لحفظ XLSM كـ PNG" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جداول بيانات مخصصة في Java. يعد هذا حلاً احترافيًا لحفظ XLSM كـ PNG وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Java." urlsection="saveas/xlsm-to-png/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف XLSM باسم PNG في Java" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من XLSM كـ PNG مهمة معقدة. يتم تنفيذ جميع انتقالات تنسيق XLSM إلى PNG بواسطة Java SDK مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات XLSM المصدر. تعد مكتبتنا Java حلاً احترافيًا لحفظ XLSM كملفات PNG عبر الإنترنت. يمنح Cloud SDK هذا مطوري Java وظائف قوية وإخراج PNG مثاليًا.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Java مثال على الكود لحفظ XLSM كـ PNG باستخدام REST API" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.xlsm";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.png";
    String folder ="CellsTests";
    try 
    {
        CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
        cellsApi.cellsSaveAsPostDocumentSaveAs(name , saveOptions,newfilename,false,false,folder,null,null,null,true);                       
    }
    catch(Exception exception )
    {
        System.out.print(exception);
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية حفظ XLSM كـ PNG باستخدام مكتبة Cells Cloud Java." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة Java وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في Java.</li>
<li>استخدم طريقة `postWorkbookSaveAs` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>Maven 2.2.0 أو أحدث</li>
<li>Java(TM) بيئة التشغيل SE</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

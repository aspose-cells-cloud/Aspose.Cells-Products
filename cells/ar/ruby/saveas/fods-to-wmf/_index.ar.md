---
title:  احفظ FODS كـ WMF باستخدام Ruby
description:  استخدام Aspose.Cells Cloud SDK لـ Ruby لحفظ ملف بتنسيق FODS كملف بتنسيق WMF.
kwords: Excel, Save FODS as WMF, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save FODS as WMF using the Cells Cloud Ruby library.","description": "How to save FODS as WMF using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/saveas/fods-to-wmf/","step": [{ "@type": "HowToStep","name": "How to save FODS as WMF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/fods-to-wmf/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save FODS as WMF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/fods-to-wmf/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save FODS as WMF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/fods-to-wmf/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to save FODS as WMF using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/fods-to-wmf/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="احفظ FODS بصيغة WMF" h2="مكتبة روبي لحفظ FODS بصيغة WMF" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في Ruby. يعد هذا حلاً احترافيًا لحفظ FODS بتنسيق WMF وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Ruby." urlsection="saveas/fods-to-wmf/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف FODS بتنسيق WMF في Ruby" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من FODS بتنسيق WMF مهمة معقدة. يتم تنفيذ جميع عمليات النقل من تنسيق FODS إلى WMF بواسطة Ruby SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات FODS المصدر. تعد مكتبة Ruby الخاصة بنا حلاً احترافيًا لحفظ FODS كملفات WMF عبر الإنترنت. يوفر Cloud SDK لمطوري Ruby وظائف قوية ومخرجات WMF مثالية.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="مثال على كود روبي لحفظ FODS كـ WMF باستخدام REST API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.fods'
    save_options = nil
    newfilename = 'Book1Saveas.wmf'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية حفظ FODS كـ WMF باستخدام مكتبة Cloud Ruby Cells." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة روبي وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في روبي.</li>
<li>استخدم طريقة `post_workbook_save_as` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>روبي 2.5 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

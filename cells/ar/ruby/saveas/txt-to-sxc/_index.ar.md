---
title:  احفظ TXT كـ SXC باستخدام Ruby
description:  استخدام Aspose.Cells Cloud SDK لـ Ruby لحفظ ملف بتنسيق TXT كملف بتنسيق SXC.
kwords: Excel, Save TXT as SXC, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save TXT as SXC using the Cells Cloud Ruby library.","description": "How to save TXT as SXC using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/saveas/txt-to-sxc/","step": [{ "@type": "HowToStep","name": "How to save TXT as SXC using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/txt-to-sxc/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save TXT as SXC using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/txt-to-sxc/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save TXT as SXC using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/txt-to-sxc/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to save TXT as SXC using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/saveas/txt-to-sxc/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="احفظ TXT باسم SXC" h2="مكتبة روبي لحفظ TXT بصيغة SXC" p="استخدم SaveAs API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في Ruby. يعد هذا حلاً احترافيًا لحفظ TXT بتنسيق SXC وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Ruby." urlsection="saveas/txt-to-sxc/" >}}

{{< blocks/products/cells/cells-cloud-section title="احفظ ملف TXT باسم SXC في روبي" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
يعد حفظ تنسيقات الملفات من TXT كـ SXC مهمة معقدة. يتم تنفيذ جميع عمليات النقل من تنسيق TXT إلى SXC بواسطة Ruby SDK الخاص بنا مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول بيانات TXT المصدر. تعد مكتبة Ruby الخاصة بنا حلاً احترافيًا لحفظ TXT كملفات SXC عبر الإنترنت. يوفر Cloud SDK لمطوري Ruby وظائف قوية ومخرجات SXC مثالية.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="مثال على كود روبي لحفظ TXT كـ SXC باستخدام REST API" gistPath="" %}}
  
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    require 'openssl'
    require 'bundler'
    require 'aspose_cells_cloud'
    @instance = AsposeCellsCloud::CellsApi.new(ENV['ProductClientId'],ENV['ProductClientSecret'])
    name = 'Book1.txt'
    save_options = nil
    newfilename = 'Book1Saveas.sxc'
    is_auto_fit_rows = true
    is_auto_fit_columns = true
    folder = 'Temp'
    result = @instance.cells_save_as_post_document_save_as(name, { :save_options=>save_options, :newfilename=>(folder+"/"+newfilename), :is_auto_fit_rows=>is_auto_fit_rows, :is_auto_fit_columns=>is_auto_fit_columns, :folder=>folder})
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية حفظ TXT كـ SXC باستخدام مكتبة Cloud Ruby Cells." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة روبي وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في روبي.</li>
<li>استخدم طريقة `post_workbook_save_as` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>روبي 2.5 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

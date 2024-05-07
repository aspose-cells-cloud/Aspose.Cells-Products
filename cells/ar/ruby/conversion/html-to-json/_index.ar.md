---
title:  تحويل HTML إلى JSON باستخدام روبي
description: استخدام Aspose.Cells Cloud SDK لـ Ruby لتحويل ملف بتنسيق HTML إلى ملف بتنسيق JSON.
kwords: Excel, Convert HTML to JSON, REST, Ruby
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to convert HTML to JSON using the Cells Cloud Ruby library.","description": "How to convert HTML to JSON using the Cells Cloud Ruby library.","image": {"@type": "ImageObject"},"url": "/ruby/conversion/html-to-json/","step": [{ "@type": "HowToStep","name": "How to convert HTML to JSON using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/html-to-json/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to convert HTML to JSON using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/html-to-json/","text": "Install Ruby library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to convert HTML to JSON using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/html-to-json/","text": "Open the source file in Ruby.",},{ "@type": "HowToStep","name": "How to convert HTML to JSON using the Cells Cloud Ruby library. step 1", "image": {"@type": "ImageObject",},"url": "/ruby/conversion/html-to-json/","text": "Use the `put_convert_workbook` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "RubyMine, Visual Studio Code, Aptana Studio, NetBeans"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why convert file formats in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just convert them to appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PutConvertWorkbookRequest() method, passing an output filename with required extension.</li><li>Get the result of conversion as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I convert with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="تحويل HTML إلى JSON" h2="مكتبة روبي لتحويل HTML إلى JSON" p="استخدم التحويل API من Cells Cloud لإنشاء سير عمل جدول بيانات مخصص في مشاريع Ruby. يعد هذا حلاً احترافيًا لتحويل HTML إلى JSON وتنسيقات المستندات الأخرى عبر الإنترنت باستخدام Ruby." urlsection="conversion/html-to-json/" >}}

{{< blocks/products/cells/cells-cloud-section title="تحويل HTML إلى JSON باستخدام Cells Cloud SDK لروبي" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
يمكن أن يكون تحويل تنسيقات الملفات من HTML إلى JSON مهمة معقدة. يتعامل Ruby SDK الخاص بنا مع جميع تحويلات تنسيق HTML إلى JSON مع الحفاظ على المحتوى الهيكلي والمنطقي الرئيسي لجدول البيانات HTML المصدر. توفر مكتبة Ruby الخاصة بنا حلاً احترافيًا لتحويل HTML إلى ملفات JSON عبر الإنترنت. يعمل Cloud SDK على تمكين مطوري Ruby من خلال وظائف قوية ويضمن إخراج JSON عالي الجودة.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="مثال على كود روبي لتحويل HTML إلى JSON باستخدام Cells Cloud SDK" gistPath="" %}}
 
```ruby
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-ruby/
    describe 'cells_save_as_post_document_save_as test' do
        it "should work" do
            @instance = AsposeCellsCloud::CellsApi.new($client_id,$client_secret,"v3.0","https://api.aspose.cloud/")
            name = "BOOK1.html"
            format = 'json'
            @instance.cells_workbook_put_convert_workbook( ::File.open(File.expand_path("data/"+name),"r")  {|io| io.read(io.size) },{:format=>format})     
        end
    end
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="كيفية تحويل HTML إلى JSON باستخدام مكتبة Cells Cloud Ruby." >}}
<li> تسجيل حساب في<a href="https://dashboard.aspose.cloud/">لوحة القيادة</a> للحصول على تفاصيل الحصص والترخيص API مجانًا</li>
<li>قم بتثبيت مكتبة روبي وأضف المرجع (استيراد المكتبة) إلى مشروعك.</li>
<li>افتح الملف المصدر في روبي.</li>
<li>استخدم طريقة `put_convert_workbook` لاسترداد الدفق الناتج.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="متطلبات النظام" >}}
<li>روبي 2.5 أو أحدث</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

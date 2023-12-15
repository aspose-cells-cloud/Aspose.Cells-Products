---
title:  دمج الملفات Excel باستخدام C#
description:  Aspose.Cells Cloud REST API يدعم دمج ملفات Excel المتعددة في ملف Excel واحد باستخدام C#، ويقدم SDKs لمختلف لغات البرمجة.
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="دمج الملفات Excel باستخدام C#" h2="يدعم Aspose.Cells Cloud SDK دمج ملفات Excel المتعددة في ملف Excel واحد." p="Aspose.Cells Cloud REST API يدعم دمج ملفات Excel المتعددة في ملف Excel واحد باستخدام C#، ويقدم SDKs لمختلف لغات البرمجة." urlsection="merge/" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}
{{% blocks/products/cells/cells-cloud-api-http-method apiname="POST" apiurl="https://api.aspose.cloud/v3.0/cells/merge" %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/cells/cells-cloud-api-template btName="Merge" OutResultType="Variable" OutResultDataType="Class" ResultPosition="FileInfo" apireferenceurl="https://reference.aspose.cloud/cells/#/LightCells/PostMerge" >}}  
{{< blocks/products/cells/cells-cloud-upload >}}  
 
	{{< blocks/products/cells/cells-cloud-parameters itName="format" required="true" prompt="The format to convert(CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)." >}}
	{{< blocks/products/cells/cells-cloud-parameters itName="mergeToOneSheet" required="true" prompt="mergeToOneSheet" >}} 
                        
{{% blocks/products/cells/cells-cloud-showcode %}}         
 
                                    
```cs

	using Aspose.Cells.Cloud.SDK.Api;
	using Aspose.Cells.Cloud.SDK.Request;
	using System;
	using System.IO;
	using System.Collections.Generic;
	CellsApi cellsApi = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
	string filePath = "test.txt";
	PostMergeRequest  request = new PostMergeRequest();
	request.File = new Dictionary<string, Stream>();
	Stream fileStream = File.OpenRead(filePath);
	request.File.Add(filePath1, fileStream1);
	request.File.Add(filePath2, fileStream2);
	request.format = "xps";
	request.mergeToOneSheet = false;


	Aspose.Cells.Cloud.SDK.Model.FileInfo fileInfo = cellsApi.PostMerge(request);
	fileStream.Close();
	      
```  
{{% /blocks/products/cells/cells-cloud-showcode %}}   
{{< /blocks/products/cells/cells-cloud-api-template >}}     

{{< blocks/products/cells/cells-cloud-language-card title="تنسيقات الملفات المدعومة" >}}
    {{< blocks/products/cells/cells-cloud-language-cardlist title="نمط الإدخال" >}}
        <li><b>Microsoft Excel:</b> XLS، XLSX، XLSB، XLSM، XLT، XLTX، XLTM</li>
	<li><b>مكتب مفتوح:</b> أود، فودز، أوتس</li>
	<li><b>إكس إم إل:</b>جدول البيانات، XML</li>
	<li><b>نص:</b> Csv، Tsv، Txt (TabDelimited)</li>
	<li><b>الويب:</b> أتش تي أم أل، أتش تي أم أل</li>
	<li><b>الصور:</b> بابوا نيو غينيا، جبغ، جيف، إي إم إف</li>
	<li><b>آخر:</b> قوات الدفاع الشعبي، Json، تخفيض السعر</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}   

    

     {{< blocks/products/cells/cells-cloud-language-cardlist title="تنسيق الإخراج" >}}
        <li><b>Microsoft Excel:</b> XLS، XLSX، XLSB، XLSM، XLT، XLTX، XLTM</li>
	<li><b>Microsoft كلمة/PowerPoint:</b> دوكإكس، بي تي إكس</li>
	<li><b>مكتب مفتوح:</b> أود، فودز، أوتس</li>
	<li><b>إكس إم إل:</b>جدول البيانات، XML</li>
	<li><b>نص:</b> Csv، Tsv، Txt (TabDelimited)</li>
	<li><b>الويب:</b> أتش تي أم أل، أتش تي أم أل</li>
	<li><b>الصور:</b> PNG، Jpg، Gif، Emf، Svg، Tiff</li>
	<li><b>آخر:</b> PDF، Xps، Dif، Json، Markdown، Sql</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}    

{{< /blocks/products/cells/cells-cloud-language-card >}}

{{< blocks/products/cells/product-card-row title="العمليات الشعبية" >}}
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="دمج ملفات Excel متعددة" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/merge/multi-files/" >}}
{{< /blocks/products/cells/product-card-row >}}

{{< blocks/products/cells/product-card-row title="دعم تطوير اللغات" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK لنظام Android" imgSrc="/cells/sdk/aspose_cells-for-android.png" productLink="/cells/android/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK للذهاب" imgSrc="/cells/sdk/aspose_cells-for-go.png" productLink="/cells/go/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="اس دي كيه for Java" imgSrc="/cells/sdk/aspose_cells-for-java.png" productLink="/cells/java/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK للشبكة" imgSrc="/cells/sdk/aspose_cells-for-net.png" productLink="/cells/net/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK للعقدة" imgSrc="/cells/sdk/aspose_cells-for-node.png" productLink="/cells/node/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK لـ Perl" imgSrc="/cells/sdk/aspose_cells-for-perl.png" productLink="/cells/perl/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK لـ PHP" imgSrc="/cells/sdk/aspose_cells-for-php.png" productLink="/cells/php/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK لـ Python" imgSrc="/cells/sdk/aspose_cells-for-python.png" productLink="/cells/python/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK لروبي" imgSrc="/cells/sdk/aspose_cells-for-ruby.png" productLink="/cells/ruby/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK لسويفت" imgSrc="/cells/sdk/aspose_cells-for-swift.png" productLink="/cells/swift/" >}}
{{< /blocks/products/cells/product-card-row >}}
{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/i18n/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="مصادر التعلم" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="توثيق" href="https://docs.aspose.cloud/cells" >}}
{{< blocks/products/pf/slr-element name="مصدر الرمز" href="https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet" >}}
{{< blocks/products/pf/slr-element name="API المراجع" href="https://apireference.aspose.cloud/cells/" >}}
{{< blocks/products/pf/slr-element name="فيديوهات تعليمية" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="دعم المنتج" tabId="support" >}}
{{< blocks/products/pf/slr-element name="دعم مجاني" href="https://forum.aspose.cloud/c/cells" >}}
{{< blocks/products/pf/slr-element name="الدعم المدفوع" href="https://helpdesk.aspose.cloud" >}}
{{< blocks/products/pf/slr-element name="مدونة" href="https://blog.aspose.cloud/category/cells/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="لماذا Aspose.Cells Cloud SDK for .NET؟" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="قائمة العملاء" href="https://company.aspose.cloud/customers" >}}
{{< blocks/products/pf/slr-element name="حماية" href="https://company.aspose.cloud/legal/security" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/i18n/support-learning-resources >}}

{{< blocks/products/pf/i18n/download-section downloadFreeTrialLink="" pricingInformationLink="https://purchase.aspose.cloud/pricing" >}}

{{< /blocks/products/pf/main-wrap-class >}}

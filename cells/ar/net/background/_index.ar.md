---
title: أضف علامة مائية نصية إلى ملفات Excel وقم بإنشاء ملفات الإخراج بتنسيقات مختلفة.
description: في الواقع، يوفر Aspose.Cells Cloud دعمًا قويًا لإضافة علامة مائية نصية إلى ملفات Excel وإنشاء ملفات الإخراج بتنسيقات مختلفة.
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="أضف علامة مائية نصية إلى ملفات Excel وقم بإنشاء ملفات الإخراج بتنسيقات مختلفة." h2="في الواقع، يوفر Aspose.Cells Cloud دعمًا قويًا لإضافة علامة مائية نصية إلى ملفات Excel وإنشاء ملفات الإخراج بتنسيقات مختلفة." p="توفر السحابة Aspose.Cells REST API الذي يدعم إضافة علامة مائية نصية إلى ملفات Excel وإنشاء ملفات الإخراج بتنسيقات مختلفة وتوفر SDKs للغات برمجة متعددة. تتضمن لغات البرمجة هذه Net وJava وGo وNodeJS وPython وما إلى ذلك." urlsection="" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="POST" apiurl="https://api.aspose.cloud/v3.0/cells/watermark" %}}

{{< blocks/products/cells/cells-cloud-api-template btName="RunCode" OutResultType="Variable" OutResultDataType="Class" ResponseType="FilesResult" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/#/LightCells/PostWatermark" >}}
{{< blocks/products/cells/cells-cloud-upload >}}

{{< blocks/products/cells/cells-cloud-parameters itName="text" required="True" prompt="background text." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="color" required="True" prompt="e.g. #1032ff" >}}
{{< blocks/products/cells/cells-cloud-parameters itName="outFormat" required="False" prompt="The output data file format.(CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)" >}}
{{< blocks/products/cells/cells-cloud-parameters itName="password" required="False" prompt="The password needed to open an Excel file." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="checkExcelRestriction" required="False" prompt="Whether check restriction of excel file when user modify cells related objects." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="region" required="False" prompt="The regional settings for workbook." >}}
{{< blocks/products/cells/cells-cloud-showparameters >}}
{{% blocks/products/cells/cells-cloud-showcode request="text,color,outFormat,password,checkExcelRestriction,region" requestvalue=",,,,true," %}}

```cs
	using Aspose.Cells.Cloud.SDK.Api;
	using Aspose.Cells.Cloud.SDK.Model;
	using Aspose.Cells.Cloud.SDK.Request;
	using Newtonsoft.Json;
	using System;
	using System.IO;
	using System.Collections.Generic;
	CellsApi cellsApi = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
	var request = new PostWatermarkRequest();
	request.File = new Dictionary<string, Stream>();
	string filePath = "Book1.xlsx";
	Stream fileStream = File.OpenRead(filePath);
	request.File.Add(filePath, fileStream);
	request.text = "";
	request.color = "";
	request.outFormat = "";
	request.password = "";
	request.checkExcelRestriction = true;
	request.region = "";
	var result = cellsApi.PostWatermark(request);
	fileStream.Close();






```
{{% /blocks/products/cells/cells-cloud-showcode %}}
{{< /blocks/products/cells/cells-cloud-api-template >}}

{{< blocks/products/pf/product-card-row title="تنسيقات الملفات المدعومة" >}}
<div class="diagram1 d2  d1-cloud">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-mail-forward"> </i> نمط الإدخال</header><ul>
<li><b>Microsoft Excel:</b> XLS، XLSX، XLSB، XLSM، XLT، XLTX، XLTM</li>
<li><b>مكتب مفتوح:</b> أود، فودز، أوتس</li>
<li><b>إكس إم إل:</b>جدول البيانات، XML</li>
<li><b>نص:</b> Csv، Tsv، Txt (TabDelimited)</li>
<li><b>الويب:</b> أتش تي أم أل، أتش تي أم أل</li>
<li><b>الصور:</b> بابوا نيو غينيا، جبغ، جيف، إي إم إف</li>
<li><b>آخر:</b> قوات الدفاع الشعبي، Json، تخفيض السعر</li>
</ul></div>
<div class="d1-col d1-right"><header><i class="fa fa-mail-forward"> </i> تنسيق الإخراج</header><ul>
<li><b>Microsoft Excel:</b> XLS، XLSX، XLSB، XLSM، XLT، XLTX، XLTM</li>
<li><b>Microsoft كلمة/PowerPoint:</b> دوكإكس، بي تي إكس</li>
<li><b>مكتب مفتوح:</b> أود، فودز، أوتس</li>
<li><b>إكس إم إل:</b>جدول البيانات، XML</li>
<li><b>نص:</b> Csv، Tsv، Txt (TabDelimited)</li>
<li><b>الويب:</b> أتش تي أم أل، أتش تي أم أل</li>
<li><b>الصور:</b> PNG، Jpg، Gif، Emf، Svg، Tiff</li>
<li><b>آخر:</b> PDF، Xps، Dif، Json، Markdown، Sql</li>
</ul></div>
</div>
<div class="d1-logo"><img src="/product-logos/aspose_cells-for-cloud.svg" alt="Conversion SDK"><header>Aspose.Cells</header><footer>سحابة SDK</footer></div>
</div>
{{< /blocks/products/pf/product-card-row >}}

{{< blocks/products/cells/cells-language-cloud-card-row title="دعم تطوير اللغات" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK للذهاب" imgSrc="/cells/sdk/aspose_cells-for-go.png" productLink="/cells/go/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="اس دي كيه for Java" imgSrc="/cells/sdk/aspose_cells-for-java.png" productLink="/cells/java/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK للشبكة" imgSrc="/cells/sdk/aspose_cells-for-net.png" productLink="/cells/net/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK للعقدة" imgSrc="/cells/sdk/aspose_cells-for-node.png" productLink="/cells/node/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK لـ Perl" imgSrc="/cells/sdk/aspose_cells-for-perl.png" productLink="/cells/perl/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK لـ PHP" imgSrc="/cells/sdk/aspose_cells-for-php.png" productLink="/cells/php/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK لـ Python" imgSrc="/cells/sdk/aspose_cells-for-python.png" productLink="/cells/python/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK لروبي" imgSrc="/cells/sdk/aspose_cells-for-ruby.png" productLink="/cells/ruby/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK لسويفت" imgSrc="/cells/sdk/aspose_cells-for-swift.png" productLink="/cells/swift/" >}}
{{< /blocks/products/cells/cells-language-cloud-card-row >}}


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

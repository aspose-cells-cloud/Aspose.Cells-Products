---
title:  تعيين الخلفية في ملف Excel
description:  Aspose.Cells Cloud REST API يدعم تعيين الخلفيات لملفات Excel ويوفر SDKs لمختلف لغات البرمجة، بما في ذلك Android وC# وGo وJava وNodeJS وPerl وPHP وPython وRuby وSwift.
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="تعيين الخلفية في ملف Excel" h2="Aspose.Cells يدعم Cloud SDK إعداد الخلفيات أو العلامات المائية لملفات Excel." p="Aspose.Cells Cloud REST API يدعم تعيين الخلفيات لملفات Excel ويوفر SDKs لمختلف لغات البرمجة، بما في ذلك Android وC# وGo وJava وNodeJS وPerl وPHP وPython وRuby وSwift." urlsection="" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}
{{% blocks/products/cells/cells-cloud-api-http-method apiname="POST" apiurl="https://api.aspose.cloud/v3.0/cells/watermark" %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/cells/cells-cloud-api-template btName="Background" OutResultType="Variable" OutResultDataType="Class" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/#/LightCells/PostWatermark" >}}

	{{< blocks/products/cells/cells-cloud-upload >}}
	{{< blocks/products/cells/cells-cloud-parameters itName="color" required="true" prompt="color" >}}
	{{< blocks/products/cells/cells-cloud-parameters itName="text" required="true" prompt="text" >}}
{{% blocks/products/cells/cells-cloud-showcode %}}
```cs

	using Aspose.Cells.Cloud.SDK.Api;
	using Aspose.Cells.Cloud.SDK.Request;
	using System;
	using System.IO;
	using System.Collections.Generic;
	CellsApi cellsApi = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
	string filePath = "test.txt";
	PostWatermarkRequest request = new PostWatermarkRequest();
	request.File = new Dictionary<string, Stream>();
	Stream fileStream = File.OpenRead(filePath);
	request.File.Add(filePath, fileStream);
    request.color = "#ccc";
    request.text = "Aspose.Cells Cloud";
	Aspose.Cells.Cloud.SDK.Model.FilesResult result = cellsApi.PostWatermark(request);
	fileStream.Close();

```
{{% /blocks/products/cells/cells-cloud-showcode %}}
{{< /blocks/products/cells/cells-cloud-api-template >}}


{{< blocks/products/pf/product-card-row title="العمليات الشعبية" >}}
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="إضافة علامة مائية لملفات متعددة Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/background/add-watermark/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Java" title="إضافة علامة مائية لملفات متعددة Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/java/background/add-watermark/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Go" title="إضافة علامة مائية لملفات متعددة Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/go/background/add-watermark/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for PHP" title="إضافة علامة مائية لملفات متعددة Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/php/background/add-watermark/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Node" title="إضافة علامة مائية لملفات متعددة Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/nodejs/background/add-watermark/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="إضافة علامة مائية لملفات متعددة Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/background/add-watermark/" >}}
{{< /blocks/products/pf/product-card-row >}}

{{< blocks/products/pf/product-card-row title="دعم تطوير اللغات" >}}
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
{{< /blocks/products/pf/product-card-row >}}


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

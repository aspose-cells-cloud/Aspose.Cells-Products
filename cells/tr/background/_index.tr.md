---
title:  Excel dosyasındaki arka planı ayarlayın
description:  Aspose.Cells Cloud REST API, Excel dosyaları için arka plan ayarlamayı destekler ve Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby ve Swift dahil olmak üzere çeşitli programlama dilleri için SDK'lar sağlar.
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Excel dosyasındaki arka planı ayarlayın" h2="Aspose.Cells Cloud SDK, Excel dosyaları için arka plan veya filigran ayarlamayı destekler." p="Aspose.Cells Cloud REST API, Excel dosyaları için arka plan ayarlamayı destekler ve Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby ve Swift dahil olmak üzere çeşitli programlama dilleri için SDK\'lar sağlar." urlsection="" >}}

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


{{< blocks/products/pf/product-card-row title="Popüler İşlemler" >}}
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Birden fazla Excel dosyası için filigran ekleyin" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/background/add-watermark/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Java" title="Birden fazla Excel dosyası için filigran ekleyin" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/java/background/add-watermark/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Go" title="Birden fazla Excel dosyası için filigran ekleyin" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/go/background/add-watermark/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for PHP" title="Birden fazla Excel dosyası için filigran ekleyin" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/php/background/add-watermark/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Node" title="Birden fazla Excel dosyası için filigran ekleyin" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/node/background/add-watermark/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Birden fazla Excel dosyası için filigran ekleyin" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/background/add-watermark/" >}}
{{< /blocks/products/pf/product-card-row >}}

{{< blocks/products/pf/product-card-row title="Desteklenen Geliştirme Dilleri" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="Android için SDK" imgSrc="/cells/sdk/aspose_cells-for-android.png" productLink="/cells/android/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="Go için SDK" imgSrc="/cells/sdk/aspose_cells-for-go.png" productLink="/cells/go/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Java" imgSrc="/cells/sdk/aspose_cells-for-java.png" productLink="/cells/java/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="Net için SDK" imgSrc="/cells/sdk/aspose_cells-for-net.png" productLink="/cells/net/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="Düğüm için SDK" imgSrc="/cells/sdk/aspose_cells-for-node.png" productLink="/cells/node/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="Perl için SDK" imgSrc="/cells/sdk/aspose_cells-for-perl.png" productLink="/cells/perl/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="PHP için SDK" imgSrc="/cells/sdk/aspose_cells-for-php.png" productLink="/cells/php/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="Python için SDK" imgSrc="/cells/sdk/aspose_cells-for-python.png" productLink="/cells/python/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="Ruby için SDK" imgSrc="/cells/sdk/aspose_cells-for-ruby.png" productLink="/cells/ruby/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="Swift için SDK" imgSrc="/cells/sdk/aspose_cells-for-swift.png" productLink="/cells/swift/" >}}
{{< /blocks/products/pf/product-card-row >}}


{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/i18n/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Öğrenme Kaynakları" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Dokümantasyon" href="https://docs.aspose.cloud/cells" >}}
{{< blocks/products/pf/slr-element name="Kaynak kodu" href="https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet" >}}
{{< blocks/products/pf/slr-element name="API Referanslar" href="https://apireference.aspose.cloud/cells/" >}}
{{< blocks/products/pf/slr-element name="Eğitim Videoları" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Ürün desteği" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Ücretsiz Destek" href="https://forum.aspose.cloud/c/cells" >}}
{{< blocks/products/pf/slr-element name="Ücretli Destek" href="https://helpdesk.aspose.cloud" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.cloud/category/cells/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Neden Aspose.Cells Bulut SDK for .NET?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Müşteri Listesi" href="https://company.aspose.cloud/customers" >}}
{{< blocks/products/pf/slr-element name="Güvenlik" href="https://company.aspose.cloud/legal/security" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/i18n/support-learning-resources >}}

{{< blocks/products/pf/i18n/download-section downloadFreeTrialLink="" pricingInformationLink="https://purchase.aspose.cloud/pricing" >}}

{{< /blocks/products/pf/main-wrap-class >}}

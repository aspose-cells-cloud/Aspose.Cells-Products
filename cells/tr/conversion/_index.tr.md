---
title:  Dönüştürmek
description:  Aspose.Cells Cloud REST API, excel dosyalarının farklı türdeki format dosyalarına dönüştürülmesini destekler. SDK geliştirme dillerini destekler. Bunlar arasında Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby ve Swift bulunur.
url: /tr/conversion/      
---
{{< blocks/products/pf/main-wrap-class >}}  
{{< blocks/products/cells/i18n/upper-banner h1="Dönüştürmek" h2="Aspose.Cells Bulut SDK\'sı dosya biçimi dönüştürmeyi destekler. Desteklenen dosya formatı 30\'dan fazla dosya formatına sahiptir." uploadmsg="Choose file or drop file" options="HTML,jpg,XML" logoImageSrc="/cells/app-logos/aspose_cells-for-cloud.svg" pfName="Aspose.Cells Cloud" downloadUrl="" tryOnlineUrl="" >}}   

{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

<!-- {{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertWorkbook  apimethod=PUT  apiname="Conversion" %}}  -->

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT" apiurl="https://api.aspose.cloud/v3.0/cells/convert" %}}
   
{{< /blocks/products/pf/agp/feature-section >}}  

{{< blocks/products/cells/cells-cloud-api-template btName="Convert" OutResultType="File" OutResultDataType="Stream" ResultPosition="stream" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertWorkbook" >}}  

{{< blocks/products/cells/cells-cloud-upload >}}  
{{< blocks/products/cells/cells-cloud-parameters itName="format" required="true" prompt="format" >}}
{{< blocks/products/cells/cells-cloud-parameters itName="streamformat" required="true" prompt="stream Format" >}}
                           
{{% blocks/products/cells/cells-cloud-showcode %}}  

                     
```cs

	using Aspose.Cells.Cloud.SDK.Api;
	using Aspose.Cells.Cloud.SDK.Request;
	using System;
	using System.IO;
	using System.Collections.Generic;
	CellsApi cellsApi = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
	string filePath = "test.txt";
	PutConvertWorkbookRequest request = new PutConvertWorkbookRequest();
	request.File = new Dictionary<string, Stream>();
	Stream fileStream = File.OpenRead(filePath);
	request.File.Add(filePath, fileStream);
	request.format = "xps";
	request.streamFormat = "html";
	Stream stream = cellsApi.PutConvertWorkbook(request);
	fileStream.Close();    
	      
``` 
{{% /blocks/products/cells/cells-cloud-showcode %}}      
 {{< /blocks/products/cells/cells-cloud-api-template >}}  
<!-- </div> -->
	{{< blocks/products/cells/product-card-row title="Desteklenen Dosya Formatları" >}}
	<div class="diagram1 d2  d1-cloud">
	<div class="d1-row">
	<div class="d1-col d1-left"><header><i class="fa fa-mail-forward"> </i> Giriş Formatı</header><ul>
	<li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>Açık ofis:</b> Oranlar, Fodlar, Otlar</li>
	<li><b>XML:</b>Elektronik TabloML, Xml</li>
	<li><b>Metin:</b> Csv, Tsv, Txt (Sekmeyle Ayrılmış)</li>
	<li><b>Ağ:</b> Html, Mhtml</li>
	<li><b>Görüntüler:</b> Png, Jpg, Gif, Emf</li>
	<li><b>Diğer:</b> Pdf, Json, Markdown</li>
	</ul></div>
	<div class="d1-col d1-right"><header><i class="fa fa-mail-forward"> </i> Çıkış biçimi</header><ul>
	<li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>Microsoft Kelime/PowerPoint:</b> Docx, Pptx</li>
	<li><b>Açık ofis:</b> Oranlar, Fodlar, Otlar</li>
	<li><b>XML:</b>Elektronik TabloML, Xml</li>
	<li><b>Metin:</b> Csv, Tsv, Txt (Sekmeyle Ayrılmış)</li>
	<li><b>Ağ:</b> Html, Mhtml</li>
	<li><b>Görüntüler:</b> Png, Jpg, Gif, Emf, Svg, Tiff</li>
	<li><b>Diğer:</b> Pdf, Xps, Dif, Json, Markdown, Sql</li>
	</ul></div>
	</div>
	<div class="d1-logo"><img src="/product-logos/aspose_cells-for-cloud.svg" alt="Conversion SDK"><header>Aspose.Cells</header><footer>Bulut SDK'sı</footer></div>
	</div>
	{{< /blocks/products/cells/product-card-row >}}
{{< blocks/products/cells/product-card-row title="Popüler İşlemler" >}}
    
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Xlsx\'i PDF\'ye dönüştürme" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/conversion/xlsx-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Xlsx\'i Json\'a dönüştürme" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/conversion/xlsx-to-json/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Xlsx\'i Csv\'ye dönüştürme" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/conversion/xlsx-to-csv/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Xlsx\'i PDF\'ye dönüştürme" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/conversion/xlsx-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Xlsx\'i Json\'a dönüştürme" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/conversion/xlsx-to-json/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Xlsx\'i Csv\'ye dönüştürme" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/conversion/xlsx-to-csv/" >}}
{{< /blocks/products/cells/product-card-row >}}
 
{{< blocks/products/cells/product-card-row title="Desteklenen Geliştirme Dilleri" >}}
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
{{< /blocks/products/cells/product-card-row >}}


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

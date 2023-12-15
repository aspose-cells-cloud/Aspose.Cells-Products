---
title:  Konvertierung
description:  Aspose.Cells Cloud REST API unterstützt die Konvertierung von Excel-Dateien in verschiedene Arten von Formatdateien. SDK unterstützt Entwicklungssprachen. Dazu gehören Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby und Swift.
url: /de/conversion/      
---
{{< blocks/products/pf/main-wrap-class >}}  
{{< blocks/products/cells/i18n/upper-banner h1="Konvertierung" h2="Aspose.Cells Cloud SDK unterstützt die Konvertierung von Dateiformaten. Das unterstützte Dateiformat umfasst mehr als 30 Dateiformate." uploadmsg="Choose file or drop file" options="HTML,jpg,XML" logoImageSrc="/cells/app-logos/aspose_cells-for-cloud.svg" pfName="Aspose.Cells Cloud" downloadUrl="" tryOnlineUrl="" >}}   

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
	{{< blocks/products/cells/product-card-row title="Unterstützte Dateiformate" >}}
	<div class="diagram1 d2  d1-cloud">
	<div class="d1-row">
	<div class="d1-col d1-left"><header><i class="fa fa-mail-forward"> </i> Eingabeformat</header><ul>
	<li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>OpenOffice:</b> Odds, Fods, Ots</li>
	<li><b>XML:</b>TabellenkalkulationML, XML</li>
	<li><b>Text:</b> Csv, Tsv, Txt (TabDelimited)</li>
	<li><b>Netz:</b> HTML, Mhtml</li>
	<li><b>Bilder:</b> Png, Jpg, Gif, EMF</li>
	<li><b>Andere:</b> PDF, Json, Markdown</li>
	</ul></div>
	<div class="d1-col d1-right"><header><i class="fa fa-mail-forward"> </i> Ausgabeformat</header><ul>
	<li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>Microsoft Wort/PowerPoint:</b> Docx, Pptx</li>
	<li><b>OpenOffice:</b> Odds, Fods, Ots</li>
	<li><b>XML:</b>TabellenkalkulationML, XML</li>
	<li><b>Text:</b> Csv, Tsv, Txt (TabDelimited)</li>
	<li><b>Netz:</b> HTML, Mhtml</li>
	<li><b>Bilder:</b> Png, Jpg, Gif, EMF, Svg, Tiff</li>
	<li><b>Andere:</b> PDF, XPS, Dif, Json, Markdown, SQL</li>
	</ul></div>
	</div>
	<div class="d1-logo"><img src="/product-logos/aspose_cells-for-cloud.svg" alt="Conversion SDK"><header>Aspose.Cells</header><footer>Cloud-SDK</footer></div>
	</div>
	{{< /blocks/products/cells/product-card-row >}}
{{< blocks/products/cells/product-card-row title="Beliebte Operationen" >}}
    
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Konvertierung von Xlsx in PDF" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/conversion/xlsx-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Konvertierung von Xlsx in Json" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/conversion/xlsx-to-json/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Konvertierung von Xlsx in Csv" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/conversion/xlsx-to-csv/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Konvertierung von Xlsx in PDF" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/conversion/xlsx-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Konvertierung von Xlsx in Json" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/conversion/xlsx-to-json/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Konvertierung von Xlsx in Csv" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/conversion/xlsx-to-csv/" >}}
{{< /blocks/products/cells/product-card-row >}}
 
{{< blocks/products/cells/product-card-row title="Unterstützte Entwicklungssprachen" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK für Android" imgSrc="/cells/sdk/aspose_cells-for-android.png" productLink="/cells/android/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK für Go" imgSrc="/cells/sdk/aspose_cells-for-go.png" productLink="/cells/go/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Java" imgSrc="/cells/sdk/aspose_cells-for-java.png" productLink="/cells/java/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK für Net" imgSrc="/cells/sdk/aspose_cells-for-net.png" productLink="/cells/net/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK für Node" imgSrc="/cells/sdk/aspose_cells-for-node.png" productLink="/cells/node/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK für Perl" imgSrc="/cells/sdk/aspose_cells-for-perl.png" productLink="/cells/perl/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK für PHP" imgSrc="/cells/sdk/aspose_cells-for-php.png" productLink="/cells/php/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK für Python" imgSrc="/cells/sdk/aspose_cells-for-python.png" productLink="/cells/python/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK für Ruby" imgSrc="/cells/sdk/aspose_cells-for-ruby.png" productLink="/cells/ruby/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK für Swift" imgSrc="/cells/sdk/aspose_cells-for-swift.png" productLink="/cells/swift/" >}}
{{< /blocks/products/cells/product-card-row >}}


{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/i18n/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Lernmittel" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Dokumentation" href="https://docs.aspose.cloud/cells" >}}
{{< blocks/products/pf/slr-element name="Quellcode" href="https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet" >}}
{{< blocks/products/pf/slr-element name="API Referenzen" href="https://apireference.aspose.cloud/cells/" >}}
{{< blocks/products/pf/slr-element name="Tutorial-Videos" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Produkt Support" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Kostenloser Support" href="https://forum.aspose.cloud/c/cells" >}}
{{< blocks/products/pf/slr-element name="Bezahlter Support" href="https://helpdesk.aspose.cloud" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.cloud/category/cells/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Warum Aspose.Cells Cloud SDK for .NET?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Kundenliste" href="https://company.aspose.cloud/customers" >}}
{{< blocks/products/pf/slr-element name="Sicherheit" href="https://company.aspose.cloud/legal/security" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/i18n/support-learning-resources >}}

{{< blocks/products/pf/i18n/download-section downloadFreeTrialLink="" pricingInformationLink="https://purchase.aspose.cloud/pricing" >}}

{{< /blocks/products/pf/main-wrap-class >}}

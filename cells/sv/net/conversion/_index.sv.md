---
title: Konvertera Excel filformat med C#
description: " Aspose.Cells Cloud REST API stöder Excel filformatkonvertering med C# och erbjuder SDK:er för flera programmeringsspråk."
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Konvertera Excel filformat med C#" h2="Aspose.Cells Cloud SDK stöder konvertering mellan 30+ filformat." p="Aspose.Cells Cloud REST API stöder Excel filformatkonvertering med C# och erbjuder SDK:er för flera programmeringsspråk." urlsection="conversion/" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}
{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT" apiurl="https://api.aspose.cloud/v3.0/cells/convert" %}}
   
{{< /blocks/products/pf/agp/feature-section >}}  

{{< blocks/products/cells/cells-cloud-api-template btName="Convert" OutResultType="File" OutResultDataType="Stream" ResultPosition="stream" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertWorkbook" >}}  
{{< blocks/products/cells/cells-cloud-upload >}}                 
{{< blocks/products/cells/cells-cloud-parameters itName="format" required="true" prompt="The format to convert(CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="streamFormat" required="true" prompt="The format of the input file stream." >}}

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




{{< blocks/products/cells/cells-cloud-language-card title="Filformat som stöds" >}}
    {{< blocks/products/cells/cells-cloud-language-cardlist title="Inmatningsformat" >}}
        <li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>Öppet kontor:</b> Ods, Fods, Ots</li>
	<li><b>XML:</b>SpreadsheetML, XML</li>
	<li><b>Text:</b> Csv, Tsv, Txt (TabDelimited)</li>
	<li><b>Webb:</b> Html, Mhtml</li>
	<li><b>Bilder:</b> Png, Jpg, Gif, Emf</li>
	<li><b>Övrig:</b> Pdf, Json, Markdown</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}   

    

     {{< blocks/products/cells/cells-cloud-language-cardlist title="Utmatningsformat" >}}
        <li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>Microsoft Word/PowerPoint:</b> Docx, Pptx</li>
	<li><b>Öppet kontor:</b> Ods, Fods, Ots</li>
	<li><b>XML:</b>SpreadsheetML, XML</li>
	<li><b>Text:</b> Csv, Tsv, Txt (TabDelimited)</li>
	<li><b>Webb:</b> Html, Mhtml</li>
	<li><b>Bilder:</b> Png, Jpg, Gif, Emf, Svg, Tiff</li>
	<li><b>Övrig:</b> Pdf, Xps, Dif, Json, Markdown, Sql</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}    


     

{{< /blocks/products/cells/cells-cloud-language-card >}}




	{{< blocks/products/cells/product-card-row title="Populära fungerar" >}}
    
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Konvertering av Xlsx till pdf" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/conversion/xlsx-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Konvertering Xlsx till Json" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/conversion/xlsx-to-json/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Konvertering Xlsx till Csv" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/conversion/xlsx-to-csv/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Konvertering av Xlsx till pdf" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/conversion/xlsx-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Konvertering Xlsx till Json" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/conversion/xlsx-to-json/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Konvertering Xlsx till Csv" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/conversion/xlsx-to-csv/" >}}
{{< /blocks/products/cells/product-card-row >}}

{{< blocks/products/cells/product-card-row title="Stöds utveckla språk" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för Android" imgSrc="/cells/sdk/aspose_cells-for-android.png" productLink="/cells/android/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för Go" imgSrc="/cells/sdk/aspose_cells-for-go.png" productLink="/cells/go/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Java" imgSrc="/cells/sdk/aspose_cells-for-java.png" productLink="/cells/java/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för Net" imgSrc="/cells/sdk/aspose_cells-for-net.png" productLink="/cells/net/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för Node" imgSrc="/cells/sdk/aspose_cells-for-node.png" productLink="/cells/node/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för Perl" imgSrc="/cells/sdk/aspose_cells-for-perl.png" productLink="/cells/perl/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för PHP" imgSrc="/cells/sdk/aspose_cells-for-php.png" productLink="/cells/php/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för Python" imgSrc="/cells/sdk/aspose_cells-for-python.png" productLink="/cells/python/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för Ruby" imgSrc="/cells/sdk/aspose_cells-for-ruby.png" productLink="/cells/ruby/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK för Swift" imgSrc="/cells/sdk/aspose_cells-for-swift.png" productLink="/cells/swift/" >}}
{{< /blocks/products/cells/product-card-row >}}


{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/i18n/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Lärresurser" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Dokumentation" href="https://docs.aspose.cloud/cells" >}}
{{< blocks/products/pf/slr-element name="Källkod" href="https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet" >}}
{{< blocks/products/pf/slr-element name="API Referenser" href="https://apireference.aspose.cloud/cells/" >}}
{{< blocks/products/pf/slr-element name="Handledningsvideor" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Produktsupport" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Gratis support" href="https://forum.aspose.cloud/c/cells" >}}
{{< blocks/products/pf/slr-element name="Betald support" href="https://helpdesk.aspose.cloud" >}}
{{< blocks/products/pf/slr-element name="Blogg" href="https://blog.aspose.cloud/category/cells/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Varför Aspose.Cells Cloud SDK for .NET?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Kundlista" href="https://company.aspose.cloud/customers" >}}
{{< blocks/products/pf/slr-element name="säkerhet" href="https://company.aspose.cloud/legal/security" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/i18n/support-learning-resources >}}

{{< blocks/products/pf/i18n/download-section downloadFreeTrialLink="" pricingInformationLink="https://purchase.aspose.cloud/pricing" >}}

{{< /blocks/products/pf/main-wrap-class >}}

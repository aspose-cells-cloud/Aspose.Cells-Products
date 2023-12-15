---
title:  Excel-Dateien mit C# zusammenführen
description:  Aspose.Cells Cloud REST API unterstützt das Zusammenführen mehrerer Excel-Dateien zu einer einzigen Excel-Datei mithilfe von C# und bietet SDKs für verschiedene Programmiersprachen.
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Excel-Dateien mit C# zusammenführen" h2="Aspose.Cells Cloud SDK unterstützt das Zusammenführen mehrerer Excel-Dateien zu einer einzigen Excel-Datei." p="Aspose.Cells Cloud REST API unterstützt das Zusammenführen mehrerer Excel-Dateien zu einer einzigen Excel-Datei mithilfe von C# und bietet SDKs für verschiedene Programmiersprachen." urlsection="merge/" >}}

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

{{< blocks/products/cells/cells-cloud-language-card title="Unterstützte Dateiformate" >}}
    {{< blocks/products/cells/cells-cloud-language-cardlist title="Eingabeformat" >}}
        <li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>OpenOffice:</b> Odds, Fods, Ots</li>
	<li><b>XML:</b>TabellenkalkulationML, XML</li>
	<li><b>Text:</b> Csv, Tsv, Txt (TabDelimited)</li>
	<li><b>Netz:</b> HTML, Mhtml</li>
	<li><b>Bilder:</b> Png, Jpg, Gif, EMF</li>
	<li><b>Andere:</b> PDF, Json, Markdown</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}   

    

     {{< blocks/products/cells/cells-cloud-language-cardlist title="Ausgabeformat" >}}
        <li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>Microsoft Wort/PowerPoint:</b> Docx, Pptx</li>
	<li><b>OpenOffice:</b> Odds, Fods, Ots</li>
	<li><b>XML:</b>TabellenkalkulationML, XML</li>
	<li><b>Text:</b> Csv, Tsv, Txt (TabDelimited)</li>
	<li><b>Netz:</b> HTML, Mhtml</li>
	<li><b>Bilder:</b> Png, Jpg, Gif, EMF, Svg, Tiff</li>
	<li><b>Andere:</b> PDF, XPS, Dif, Json, Markdown, SQL</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}    

{{< /blocks/products/cells/cells-cloud-language-card >}}

{{< blocks/products/cells/product-card-row title="Beliebte Operationen" >}}
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Mehrere Excel-Dateien zusammenführen" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/merge/multi-files/" >}}
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

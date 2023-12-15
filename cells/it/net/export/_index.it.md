---
title:  Esporta gli oggetti Excel utilizzando C#
description:  Aspose.Cells Cloud REST API supporta l'esportazione di cartelle di lavoro e oggetti interni in tutti i tipi di formati utilizzando C#. L'SDK supporta i linguaggi di sviluppo. Includono Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby e swift.
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Esporta gli oggetti Excel utilizzando C#" h2="Aspose.Cells Cloud SDK supporta l\'esportazione di cartelle di lavoro e oggetti interni in oltre 30 formati di file." p="Aspose.Cells Cloud REST API supporta l\'esportazione di cartelle di lavoro e oggetti interni in tutti i tipi di formati utilizzando C#. L\'SDK supporta i linguaggi di sviluppo. Includono Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby e swift." urlsection="export/" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}
{{% blocks/products/cells/cells-cloud-api-http-method apiname="POST" apiurl="https://api.aspose.cloud/v3.0/cells/export" %}}
{{< /blocks/products/pf/agp/feature-section >}} 
{{< blocks/products/cells/cells-cloud-api-template btName="Export" OutResultType="Variable" OutResultDataType="Class" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/#/DataProcessing/PostExport" >}}  
{{< blocks/products/cells/cells-cloud-upload >}}  
	{{< blocks/products/cells/cells-cloud-parameters itName="format" required="true" prompt="The format to convert(CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)." >}}
	{{< blocks/products/cells/cells-cloud-parameters itName="objectType" required="true" prompt="workbook/worksheet/chart/comment/picture/shape/listobject/oleobject" >}}  
{{% blocks/products/cells/cells-cloud-showcode %}}  
               
```cs

	using Aspose.Cells.Cloud.SDK.Api;
	using Aspose.Cells.Cloud.SDK.Request;
	using System;
	using System.IO;
	using System.Collections.Generic;
	CellsApi cellsApi = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
	string filePath = "test.txt";
	PostExportRequest request = new PostExportRequest();
	request.File = new Dictionary<string, Stream>();
	Stream fileStream = File.OpenRead(filePath);
	request.File.Add(filePath, fileStream);
    request.format = "xps";
	request.objectType = "Background";
	Aspose.Cells.Cloud.SDK.Model.FilesResult result = cellsApi.PostExport(request);
	fileStream.Close();    
	    
```     
{{% /blocks/products/cells/cells-cloud-showcode %}}   
{{< /blocks/products/cells/cells-cloud-api-template >}}      

{{< blocks/products/cells/cells-cloud-language-card title="Formati di file supportati" >}}
    {{< blocks/products/cells/cells-cloud-language-cardlist title="Formato di input" >}}
       <li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>Ufficio aperto:</b> Ods, Fods, Ots</li>
	<li><b>XML:</b>Foglio di calcoloML, Xml</li>
	<li><b>Testo:</b> Csv, Tsv, Txt (delimitato da tabulazioni)</li>
	<li><b>Ragnatela:</b> Html, Mhtml</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}   

    

     {{< blocks/products/cells/cells-cloud-language-cardlist title="Formato di output" >}}
        <li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>Microsoft Parola/PowerPoint:</b> Docx, Pptx</li>
	<li><b>Ufficio aperto:</b> Ods, Fods, Ots</li>
	<li><b>XML:</b>Foglio di calcoloML, Xml</li>
	<li><b>Testo:</b> Csv, Tsv, Txt (delimitato da tabulazioni)</li>
	<li><b>Ragnatela:</b> Html, Mhtml</li>
	<li><b>Immagini:</b> Png, Jpg, Gif, Emf, Svg, Tiff</li>
	<li><b>Altro:</b> Pdf, Xps, Dif, Json, Markdown, Sql</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}    


     

{{< /blocks/products/cells/cells-cloud-language-card >}}

{{< blocks/products/cells/product-card-row title="Operazioni popolari" >}}
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Esporta la cartella di lavoro in PDF" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/export/workbook-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Go" title="Esporta la cartella di lavoro in Json" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/go/export/workbook-to-json/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Java" title="Esporta oggetto elenco in Csv" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/java/export/listobject-to-csv/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for PHP" title="Esporta grafico in Png" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/php/export/chart-to-png/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Esporta la cartella di lavoro su MD" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/export/workbook-to-md/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Swift" title="Esporta foglio in pdf" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/swift/export/worksheet-to-pdf/" >}}
{{< /blocks/products/cells/product-card-row >}}
{{< blocks/products/cells/product-card-row title="Lingue di sviluppo supportate" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per Android" imgSrc="/cells/sdk/aspose_cells-for-android.png" productLink="/cells/android/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per Go" imgSrc="/cells/sdk/aspose_cells-for-go.png" productLink="/cells/go/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDKfor Java" imgSrc="/cells/sdk/aspose_cells-for-java.png" productLink="/cells/java/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per la rete" imgSrc="/cells/sdk/aspose_cells-for-net.png" productLink="/cells/net/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per Node" imgSrc="/cells/sdk/aspose_cells-for-node.png" productLink="/cells/node/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per Perl" imgSrc="/cells/sdk/aspose_cells-for-perl.png" productLink="/cells/perl/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per PHP" imgSrc="/cells/sdk/aspose_cells-for-php.png" productLink="/cells/php/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per Python" imgSrc="/cells/sdk/aspose_cells-for-python.png" productLink="/cells/python/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per Ruby" imgSrc="/cells/sdk/aspose_cells-for-ruby.png" productLink="/cells/ruby/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per Swift" imgSrc="/cells/sdk/aspose_cells-for-swift.png" productLink="/cells/swift/" >}}
{{< /blocks/products/cells/product-card-row >}}

{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/i18n/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Risorse di apprendimento" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Documentazione" href="https://docs.aspose.cloud/cells" >}}
{{< blocks/products/pf/slr-element name="Codice sorgente" href="https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet" >}}
{{< blocks/products/pf/slr-element name="API Riferimenti" href="https://apireference.aspose.cloud/cells/" >}}
{{< blocks/products/pf/slr-element name="Video tutorial" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Supporto al prodotto" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Supporto gratuito" href="https://forum.aspose.cloud/c/cells" >}}
{{< blocks/products/pf/slr-element name="Supporto a pagamento" href="https://helpdesk.aspose.cloud" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.cloud/category/cells/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Perché Aspose.Cells Cloud SDK for .NET?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Elenco clienti" href="https://company.aspose.cloud/customers" >}}
{{< blocks/products/pf/slr-element name="Sicurezza" href="https://company.aspose.cloud/legal/security" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/i18n/support-learning-resources >}}

{{< blocks/products/pf/i18n/download-section downloadFreeTrialLink="" pricingInformationLink="https://purchase.aspose.cloud/pricing" >}}

{{< /blocks/products/pf/main-wrap-class >}}

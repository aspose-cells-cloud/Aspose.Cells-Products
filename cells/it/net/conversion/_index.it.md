---
title: Converti file Excel in altri formati.
description: Aspose.Cells Cloud fornisce un solido supporto per la conversione del formato file Excel, un processo noto per la sua complessità. Aspose.Cells Cloud supporta oltre 30 formati di file, tra cui Excel, Pdf, Markdown, Json, XML, Csv, Html e così via.
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-ai-assistant >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Converti file Excel in altri formati." h2="Aspose.Cells Cloud fornisce un solido supporto per la conversione del formato file Excel, un processo noto per la sua complessità. Aspose.Cells Cloud supporta oltre 30 formati di file, tra cui Excel, Pdf, Markdown, Json, XML, Csv, Html e così via." p="Aspose.Cells Cloud fornisce REST API che supporta la conversione dei file Excel in vari formati e offre SDK per più linguaggi di programmazione. Questi linguaggi di programmazione includono Net, Java, Go, NodeJS, Python e così via. ." urlsection="" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}

{{% blocks/products/cells/cells-cloud-api-http-method apiname="PUT" apiurl="https://api.aspose.cloud/v3.0/cells/convert" %}}

{{< blocks/products/cells/cells-cloud-api-template btName="RunCode" OutResultType="Variable" OutResultDataType="Stream" ResponseType="Stream" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/#/Conversion/PutConvertWorkbook" >}}
{{< blocks/products/cells/cells-cloud-upload >}}

{{< blocks/products/cells/cells-cloud-parameters itName="format" required="False" prompt="The format to convert(CSV/XLS/HTML/MHTML/ODS/PDF/XML/TXT/TIFF/XLSB/XLSM/XLSX/XLTM/XLTX/XPS/PNG/JPG/JPEG/GIF/EMF/BMP/MD[Markdown]/Numbers)." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="password" required="False" prompt="The password needed to open an Excel file." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="outPath" required="False" prompt="Path to save the result. If it\'s a single file, the `outPath` should encompass both the filename and extension. In the case of multiple files, the `outPath` should only include the folder." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="storageName" required="False" prompt="The storage name where the file is situated." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="checkExcelRestriction" required="False" prompt="Whether check restriction of excel file when user modify cells related objects." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="streamFormat" required="False" prompt="The format of the input file stream. " >}}
{{< blocks/products/cells/cells-cloud-parameters itName="region" required="False" prompt="The regional settings for workbook." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="pageWideFitOnPerSheet" required="False" prompt="The page wide fit on worksheet." >}}
{{< blocks/products/cells/cells-cloud-parameters itName="pageTallFitOnPerSheet" required="False" prompt="The page tall fit on worksheet." >}}
{{< blocks/products/cells/cells-cloud-showparameters >}}
{{% blocks/products/cells/cells-cloud-showcode request="format,password,outPath,storageName,checkExcelRestriction,streamFormat,region,pageWideFitOnPerSheet,pageTallFitOnPerSheet" requestvalue="pdf,,,,true,,,true,true" %}}

```cs
	using Aspose.Cells.Cloud.SDK.Api;
	using Aspose.Cells.Cloud.SDK.Model;
	using Aspose.Cells.Cloud.SDK.Request;
	using Newtonsoft.Json;
	using System;
	using System.IO;
	using System.Collections.Generic;
	CellsApi cellsApi = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
	var request = new PutConvertWorkbookRequest();
	request.File = new Dictionary<string, Stream>();
	string filePath = "Book1.xlsx";
	Stream fileStream = File.OpenRead(filePath);
	request.File.Add(filePath, fileStream);
	request.format = "pdf";
	request.password = "";
	request.outPath = "";
	request.storageName = "";
	request.checkExcelRestriction = true;
	request.streamFormat = "";
	request.region = "";
	request.pageWideFitOnPerSheet = true;
	request.pageTallFitOnPerSheet = true;
	var result = cellsApi.PutConvertWorkbook(request);
	fileStream.Close();









```
{{% /blocks/products/cells/cells-cloud-showcode %}}
{{< /blocks/products/cells/cells-cloud-api-template >}}

{{< blocks/products/pf/product-card-row title="Formati di file supportati" >}}
<div class="diagram1 d2  d1-cloud">
<div class="d1-row">
<div class="d1-col d1-left"><header><i class="fa fa-mail-forward"> </i> Formato di input</header><ul>
<li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
<li><b>Ufficio aperto:</b> Ods, Fods, Ots</li>
<li><b>XML:</b>Foglio di calcoloML, Xml</li>
<li><b>Testo:</b> Csv, Tsv, Txt (delimitato da tabulazioni)</li>
<li><b>Ragnatela:</b> Html, Mhtml</li>
<li><b>Immagini:</b> Png, Jpg, Gif, Emf</li>
<li><b>Altro:</b> Pdf, Json, Markdown</li>
</ul></div>
<div class="d1-col d1-right"><header><i class="fa fa-mail-forward"> </i> Formato di output</header><ul>
<li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
<li><b>Microsoft Parola/PowerPoint:</b> Docx, Pptx</li>
<li><b>Ufficio aperto:</b> Ods, Fods, Ots</li>
<li><b>XML:</b>Foglio di calcoloML, Xml</li>
<li><b>Testo:</b> Csv, Tsv, Txt (delimitato da tabulazioni)</li>
<li><b>Ragnatela:</b> Html, Mhtml</li>
<li><b>Immagini:</b> Png, Jpg, Gif, Emf, Svg, Tiff</li>
<li><b>Altro:</b> Pdf, Xps, Dif, Json, Markdown, Sql</li>
</ul></div>
</div>
<div class="d1-logo"><img src="/product-logos/aspose_cells-for-cloud.svg" alt="Conversion SDK"><header>Aspose.Cells</header><footer>SDK cloud</footer></div>
</div>
{{< /blocks/products/pf/product-card-row >}}

{{< blocks/products/cells/cells-language-cloud-card-row title="Lingue di sviluppo supportate" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per Go" imgSrc="/cells/sdk/aspose_cells-for-go.png" productLink="/cells/go/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDKfor Java" imgSrc="/cells/sdk/aspose_cells-for-java.png" productLink="/cells/java/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per la rete" imgSrc="/cells/sdk/aspose_cells-for-net.png" productLink="/cells/net/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per Node" imgSrc="/cells/sdk/aspose_cells-for-node.png" productLink="/cells/node/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per Perl" imgSrc="/cells/sdk/aspose_cells-for-perl.png" productLink="/cells/perl/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per PHP" imgSrc="/cells/sdk/aspose_cells-for-php.png" productLink="/cells/php/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per Python" imgSrc="/cells/sdk/aspose_cells-for-python.png" productLink="/cells/python/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per Ruby" imgSrc="/cells/sdk/aspose_cells-for-ruby.png" productLink="/cells/ruby/" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK per Swift" imgSrc="/cells/sdk/aspose_cells-for-swift.png" productLink="/cells/swift/" >}}
{{< /blocks/products/cells/cells-language-cloud-card-row >}}


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

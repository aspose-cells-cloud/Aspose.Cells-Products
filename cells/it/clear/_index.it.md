---
title:  Cancella oggetti allo Excel
description:  Aspose.Cells Cloud REST API Supporta la cancellazione di oggetti interni in un file Excel e fornisce SDK per vari linguaggi di programmazione, tra cui Android, C#, GO, Java, NODEJS, Perl, 07616481, 07617341, ruby, ruby, ruby, ruby, ruby, ruby, ruby.
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Cancella oggetti allo Excel" h2="Aspose.Cells Cloud SDK supporta la cancellazione di contenuto, stile, grafici, tabelle, sfondi e altro nei file Excel." p="Aspose.Cells Cloud REST API supporta la cancellazione degli oggetti interni in un file Excel e fornisce SDK per vari linguaggi di programmazione, tra cui Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby e Swift." urlsection="" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}
{{% blocks/products/cells/cells-cloud-api-http-method apiname="POST" apiurl="https://api.aspose.cloud/v3.0/cells/clearobjects" %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/cells/cells-cloud-api-template btName="Clear" OutResultType="Variable" OutResultDataType="Class" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/#/LightCells/PostClearObjects" >}}  
{{< blocks/products/cells/cells-cloud-upload >}}  
 
	{{< blocks/products/cells/cells-cloud-parameters itName="objecttype" required="true" prompt="Please enter objecttype" >}}
 
{{% blocks/products/cells/cells-cloud-showcode itName="streamformat" ptName="stream Format:" prompt="Please enter stream Format" %}}  
               
```cs

	using Aspose.Cells.Cloud.SDK.Api;
	using Aspose.Cells.Cloud.SDK.Request;
	using System;
	using System.IO;
	using System.Collections.Generic;
	CellsApi cellsApi = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
	string filePath = "test.txt";
	PostClearObjectsRequest request = new PostClearObjectsRequest();
	request.File = new Dictionary<string, Stream>();
	Stream fileStream = File.OpenRead(filePath);
	request.File.Add(filePath, fileStream);
    request.objecttype = "Background";
	Aspose.Cells.Cloud.SDK.Model.FilesResult result = cellsApi.PostClearObjects(request);
	fileStream.Close();    
	    
```     
{{% /blocks/products/cells/cells-cloud-showcode %}}      
{{< /blocks/products/cells/cells-cloud-api-template >}}  

{{< blocks/products/pf/product-card-row title="Operazioni popolari" >}}
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Cancella contenuto in più file Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/clear/content/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Java" title="Cancella grafici in più file Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/java/clear/charts/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Go" title="Cancella stili in più file Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/go/clear/styles/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Cancella collegamenti ipertestuali in più file Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/go/clear/hyperlinks/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for PHP" title="Cancella righe duplicate in più file Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/php/clear/duplicaterows/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Node" title="Cancella righe vuote in più file Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/node/clear/blankrows/" >}}
{{< /blocks/products/pf/product-card-row >}}

{{< blocks/products/pf/product-card-row title="Lingue di sviluppo supportate" >}}
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
{{< /blocks/products/pf/product-card-row >}}


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

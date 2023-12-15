---
title:  Proteggi i file Excel
description:  Aspose.Cells Cloud REST API supporta la decrittografia, la crittografia e le firme digitali delle cartelle di lavoro e fornisce SDK per vari linguaggi di programmazione, tra cui Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby e Swift.
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Proteggi i file Excel" h2="Aspose.Cells Cloud SDK supporta la decrittografia, la crittografia e le firme digitali delle cartelle di lavoro." p="Aspose.Cells Cloud REST API supporta la decrittografia, la crittografia e le firme digitali delle cartelle di lavoro e fornisce SDK per vari linguaggi di programmazione, tra cui Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby e Swift." urlsection="" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Cells Cloud" subTitlepfName="Cells Cloud Feature" >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}
{{% blocks/products/cells/cells-cloud-api-http-method apiname="POST" apiurl="https://api.aspose.cloud/v3.0/cells/protect" %}}

{{< /blocks/products/pf/agp/feature-section >}}


{{< blocks/products/cells/cells-cloud-api-template btName="Protect" OutResultType="Variable" OutResultDataType="Class" ResultPosition="result" apireferenceurl="https://reference.aspose.cloud/cells/#/Protection/PostProtect" >}} 
{{< blocks/products/cells/cells-cloud-upload >}}  
 
	{{< blocks/products/cells/cells-cloud-parameters itName="password" required="true" prompt="Please enter password" >}} 
{{% blocks/products/cells/cells-cloud-showcode itName="streamformat" ptName="stream Format:" prompt="Please enter stream Format" %}}  
               
```cs

	using Aspose.Cells.Cloud.SDK.Api;
    using Aspose.Cells.Cloud.SDK.Model;
	using Aspose.Cells.Cloud.SDK.Request;
	using System;
	using System.IO;
	using System.Collections.Generic;
	CellsApi cellsApi = new CellsApi("xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx", "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx");
	string filePath = "test.txt";
	PostProtectRequest request = new PostProtectRequest();
	request.File = new Dictionary<string, Stream>();
	Stream fileStream = File.OpenRead(filePath);
	request.File.Add(filePath, fileStream);
    request.protectWorkbookRequest = new Model.ProtectWorkbookRequest{};
    request.password = "asposelock";
	Aspose.Cells.Cloud.SDK.Model.FilesResult result = cellsApi.PostProtect(request);
	fileStream.Close();    
	    
```     
{{% /blocks/products/cells/cells-cloud-showcode %}}      
{{< /blocks/products/cells/cells-cloud-api-template >}}       

{{< blocks/products/pf/product-card-row title="Operazioni popolari" >}}
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Decifra con password" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/protect/decrypt-with-password/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Go" title="Firma digitale" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/go/protect/digital-signature/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Java" title="Decriptare il file cloud" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/java/protect/decrypt-cloud-file-with-password/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for PHP" title="Crittografa il file cloud" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/php/protect/encrypt-cloud-file-with-password/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Crittografare con password" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/protect/encrypt-with-password/" >}}
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

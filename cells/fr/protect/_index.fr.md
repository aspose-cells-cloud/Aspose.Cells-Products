---
title:  Protéger les fichiers Excel
description:  Aspose.Cells Cloud REST API prend en charge le déchiffrement, le chiffrement et les signatures numériques des classeurs, et fournit des SDK pour divers langages de programmation, notamment Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby et Swift.
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Protéger les fichiers Excel" h2="Aspose.Cells Cloud SDK prend en charge le déchiffrement, le chiffrement et les signatures numériques des classeurs." p="Aspose.Cells Cloud REST API prend en charge le déchiffrement, le chiffrement et les signatures numériques des classeurs, et fournit des SDK pour divers langages de programmation, notamment Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby et Swift." urlsection="" >}}

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

{{< blocks/products/pf/product-card-row title="Fonctionne populaires" >}}
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Décrypter avec mot de passe" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/protect/decrypt-with-password/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Go" title="Signature numérique" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/go/protect/digital-signature/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Java" title="Décrypter le fichier cloud" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/java/protect/decrypt-cloud-file-with-password/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for PHP" title="Chiffrer le fichier cloud" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/php/protect/encrypt-cloud-file-with-password/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Chiffrer avec mot de passe" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/protect/encrypt-with-password/" >}}
{{< /blocks/products/pf/product-card-row >}}

{{< blocks/products/pf/product-card-row title="Langues de développement prises en charge" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK pour Android" imgSrc="/cells/sdk/aspose_cells-for-android.png" productLink="/cells/android/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK pour Go" imgSrc="/cells/sdk/aspose_cells-for-go.png" productLink="/cells/go/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Java" imgSrc="/cells/sdk/aspose_cells-for-java.png" productLink="/cells/java/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK pour Net" imgSrc="/cells/sdk/aspose_cells-for-net.png" productLink="/cells/net/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK pour nœud" imgSrc="/cells/sdk/aspose_cells-for-node.png" productLink="/cells/node/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK pour Perl" imgSrc="/cells/sdk/aspose_cells-for-perl.png" productLink="/cells/perl/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK pour PHP" imgSrc="/cells/sdk/aspose_cells-for-php.png" productLink="/cells/php/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK pour Python" imgSrc="/cells/sdk/aspose_cells-for-python.png" productLink="/cells/python/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK pour Ruby" imgSrc="/cells/sdk/aspose_cells-for-ruby.png" productLink="/cells/ruby/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK pour Swift" imgSrc="/cells/sdk/aspose_cells-for-swift.png" productLink="/cells/swift/" >}}
{{< /blocks/products/pf/product-card-row >}}


{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/i18n/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Ressources d\'apprentissage" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.cloud/cells" >}}
{{< blocks/products/pf/slr-element name="Code source" href="https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet" >}}
{{< blocks/products/pf/slr-element name="API Références" href="https://apireference.aspose.cloud/cells/" >}}
{{< blocks/products/pf/slr-element name="Vidéos tutorielles" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Support produit" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Assistance gratuite" href="https://forum.aspose.cloud/c/cells" >}}
{{< blocks/products/pf/slr-element name="Assistance payante" href="https://helpdesk.aspose.cloud" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.cloud/category/cells/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Pourquoi Aspose.Cells SDK Cloud for .NET ?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Liste des clients" href="https://company.aspose.cloud/customers" >}}
{{< blocks/products/pf/slr-element name="Sécurité" href="https://company.aspose.cloud/legal/security" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/i18n/support-learning-resources >}}

{{< blocks/products/pf/i18n/download-section downloadFreeTrialLink="" pricingInformationLink="https://purchase.aspose.cloud/pricing" >}}

{{< /blocks/products/pf/main-wrap-class >}}

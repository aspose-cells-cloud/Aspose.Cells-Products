---
title:  Définir l'arrière-plan dans le fichier Excel
description:  Aspose.Cells Cloud REST API prend en charge la définition d'arrière-plans pour les fichiers Excel et fournit des SDK pour divers langages de programmation, notamment Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby et Swift.
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Définir l\'arrière-plan dans le fichier Excel" h2="Aspose.Cells Cloud SDK prend en charge la définition d\'arrière-plans ou de filigranes pour les fichiers Excel." p="Aspose.Cells Cloud REST API prend en charge la définition d\'arrière-plans pour les fichiers Excel et fournit des SDK pour divers langages de programmation, notamment Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby et Swift." urlsection="" >}}

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


{{< blocks/products/pf/product-card-row title="Fonctionne populaires" >}}
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Ajouter un filigrane pour plusieurs fichiers Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/background/add-watermark/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Java" title="Ajouter un filigrane pour plusieurs fichiers Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/java/background/add-watermark/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Go" title="Ajouter un filigrane pour plusieurs fichiers Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/go/background/add-watermark/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for PHP" title="Ajouter un filigrane pour plusieurs fichiers Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/php/background/add-watermark/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Node" title="Ajouter un filigrane pour plusieurs fichiers Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/nodejs/background/add-watermark/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Ajouter un filigrane pour plusieurs fichiers Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/background/add-watermark/" >}}
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

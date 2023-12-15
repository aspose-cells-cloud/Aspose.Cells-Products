---
title:  Fusionner les fichiers Excel en utilisant C#
description:  Aspose.Cells Cloud REST API prend en charge la fusion de plusieurs fichiers Excel en un seul fichier Excel à l'aide de C# et propose des SDK pour différents langages de programmation.
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Fusionner les fichiers Excel en utilisant C#" h2="Aspose.Cells Cloud SDK prend en charge la fusion de plusieurs fichiers Excel en un seul fichier Excel." p="Aspose.Cells Cloud REST API prend en charge la fusion de plusieurs fichiers Excel en un seul fichier Excel à l\'aide de C# et propose des SDK pour différents langages de programmation." urlsection="merge/" >}}

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

{{< blocks/products/cells/cells-cloud-language-card title="Formats de fichiers pris en charge" >}}
    {{< blocks/products/cells/cells-cloud-language-cardlist title="Format d\'entrée" >}}
        <li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>Bureau ouvert:</b> Ods, Fods, Ots</li>
	<li><b>XML :</b>Feuille de calculML, XML</li>
	<li><b>Texte:</b> Csv, Tsv, Txt (TabDelimited)</li>
	<li><b>La toile:</b> HTML, HTML</li>
	<li><b>Images:</b> Png, Jpg, Gif, EMF</li>
	<li><b>Autre:</b> Pdf, Json, Markdown</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}   

    

     {{< blocks/products/cells/cells-cloud-language-cardlist title="Format de sortie" >}}
        <li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>Microsoft Mot/PowerPoint :</b> Docx, PPTX</li>
	<li><b>Bureau ouvert:</b> Ods, Fods, Ots</li>
	<li><b>XML :</b>Feuille de calculML, XML</li>
	<li><b>Texte:</b> Csv, Tsv, Txt (TabDelimited)</li>
	<li><b>La toile:</b> HTML, HTML</li>
	<li><b>Images:</b> Png, Jpg, Gif, Emf, Svg, Tiff</li>
	<li><b>Autre:</b> Pdf, Xps, Dif, Json, Markdown, SQL</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}    

{{< /blocks/products/cells/cells-cloud-language-card >}}

{{< blocks/products/cells/product-card-row title="Fonctionne populaires" >}}
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Fusionner plusieurs fichiers Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/merge/multi-files/" >}}
{{< /blocks/products/cells/product-card-row >}}

{{< blocks/products/cells/product-card-row title="Langues de développement prises en charge" >}}
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
{{< /blocks/products/cells/product-card-row >}}
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

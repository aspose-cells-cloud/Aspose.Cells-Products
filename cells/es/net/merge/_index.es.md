---
title:  Fusionar archivos Excel usando C#
description:  Aspose.Cells Cloud REST API admite la combinación de varios archivos Excel en un único archivo Excel utilizando C# y ofrece SDK para varios lenguajes de programación.
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Fusionar archivos Excel usando C#" h2="Aspose.Cells Cloud SDK admite la combinación de varios archivos Excel en un solo archivo Excel." p="Aspose.Cells Cloud REST API admite la combinación de varios archivos Excel en un único archivo Excel utilizando C# y ofrece SDK para varios lenguajes de programación." urlsection="merge/" >}}

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

{{< blocks/products/cells/cells-cloud-language-card title="Formatos de archivo admitidos" >}}
    {{< blocks/products/cells/cells-cloud-language-cardlist title="Formato de entrada" >}}
        <li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>Oficina abierta:</b> Ods, Fods, Ots</li>
	<li><b>XML:</b>Hoja de cálculoML, XML</li>
	<li><b>Texto:</b> Csv, Tsv, Txt (delimitado por tabuladores)</li>
	<li><b>Web:</b> HTML, HTML</li>
	<li><b>Imágenes:</b> Png, Jpg, Gif, Emf</li>
	<li><b>Otro:</b> Pdf, Json, rebajas</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}   

    

     {{< blocks/products/cells/cells-cloud-language-cardlist title="Formato de salida" >}}
        <li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>Microsoft Palabra/PowerPoint:</b> Docx, Pptx</li>
	<li><b>Oficina abierta:</b> Ods, Fods, Ots</li>
	<li><b>XML:</b>Hoja de cálculoML, XML</li>
	<li><b>Texto:</b> Csv, Tsv, Txt (delimitado por tabuladores)</li>
	<li><b>Web:</b> HTML, HTML</li>
	<li><b>Imágenes:</b> Png, Jpg, Gif, Emf, Svg, Tiff</li>
	<li><b>Otro:</b> Pdf, Xps, Dif, Json, Rebaja, Sql</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}    

{{< /blocks/products/cells/cells-cloud-language-card >}}

{{< blocks/products/cells/product-card-row title="Operaciones populares" >}}
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Fusionar varios archivos Excel" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/merge/multi-files/" >}}
{{< /blocks/products/cells/product-card-row >}}

{{< blocks/products/cells/product-card-row title="Idiomas de desarrollo compatibles" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK para Android" imgSrc="/cells/sdk/aspose_cells-for-android.png" productLink="/cells/android/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK para ir" imgSrc="/cells/sdk/aspose_cells-for-go.png" productLink="/cells/go/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK for Java" imgSrc="/cells/sdk/aspose_cells-for-java.png" productLink="/cells/java/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK para red" imgSrc="/cells/sdk/aspose_cells-for-net.png" productLink="/cells/net/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK para nodo" imgSrc="/cells/sdk/aspose_cells-for-node.png" productLink="/cells/node/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK para Perl" imgSrc="/cells/sdk/aspose_cells-for-perl.png" productLink="/cells/perl/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK para PHP" imgSrc="/cells/sdk/aspose_cells-for-php.png" productLink="/cells/php/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK para Python" imgSrc="/cells/sdk/aspose_cells-for-python.png" productLink="/cells/python/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK para Rubí" imgSrc="/cells/sdk/aspose_cells-for-ruby.png" productLink="/cells/ruby/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK para Swift" imgSrc="/cells/sdk/aspose_cells-for-swift.png" productLink="/cells/swift/" >}}
{{< /blocks/products/cells/product-card-row >}}
{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/i18n/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Recursos de aprendizaje" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Documentación" href="https://docs.aspose.cloud/cells" >}}
{{< blocks/products/pf/slr-element name="Código fuente" href="https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet" >}}
{{< blocks/products/pf/slr-element name="API Referencias" href="https://apireference.aspose.cloud/cells/" >}}
{{< blocks/products/pf/slr-element name="Vídeos tutoriales" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Soporte de producto" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Soporte gratuito" href="https://forum.aspose.cloud/c/cells" >}}
{{< blocks/products/pf/slr-element name="Soporte pagado" href="https://helpdesk.aspose.cloud" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.cloud/category/cells/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="¿Por qué Aspose.Cells SDK de nube for .NET?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Lista de clientes" href="https://company.aspose.cloud/customers" >}}
{{< blocks/products/pf/slr-element name="Seguridad" href="https://company.aspose.cloud/legal/security" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/i18n/support-learning-resources >}}

{{< blocks/products/pf/i18n/download-section downloadFreeTrialLink="" pricingInformationLink="https://purchase.aspose.cloud/pricing" >}}

{{< /blocks/products/pf/main-wrap-class >}}

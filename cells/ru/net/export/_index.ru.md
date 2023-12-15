---
title:  Экспортируйте объекты Excel, используя C#.
description:  Aspose.Cells Cloud REST API поддерживает экспорт книг и внутренних объектов во все виды форматов с помощью C#. SDK поддерживает языки разработки. К ним относятся Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby и Swift.
---
{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Экспортируйте объекты Excel, используя C#." h2="Aspose.Cells Cloud SDK поддерживает экспорт книг и внутренних объектов в более чем 30 форматов файлов." p="Aspose.Cells Cloud REST API поддерживает экспорт книг и внутренних объектов во все виды форматов с помощью C#. SDK поддерживает языки разработки. К ним относятся Android, C#, Go, Java, NodeJS, Perl, PHP, Python, Ruby и Swift." urlsection="export/" >}}

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

{{< blocks/products/cells/cells-cloud-language-card title="Поддерживаемые форматы файлов" >}}
    {{< blocks/products/cells/cells-cloud-language-cardlist title="Формат ввода" >}}
       <li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>ОпенОфис:</b> Одс, Фодс, Отс</li>
	<li><b>XML:</b>Электронная таблицаML, Xml</li>
	<li><b>Текст:</b> Csv, Tsv, Txt (TabDelimited)</li>
	<li><b>Интернет:</b> HTML, Мhtml</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}   

    

     {{< blocks/products/cells/cells-cloud-language-cardlist title="Выходной формат" >}}
        <li><b>Microsoft Excel:</b> Xls, Xlsx, Xlsb, Xlsm, Xlt, Xltx, Xltm</li>
	<li><b>Microsoft Слово/PowerPoint:</b> Документ, Pptx</li>
	<li><b>ОпенОфис:</b> Одс, Фодс, Отс</li>
	<li><b>XML:</b>Электронная таблицаML, Xml</li>
	<li><b>Текст:</b> Csv, Tsv, Txt (TabDelimited)</li>
	<li><b>Интернет:</b> HTML, Мhtml</li>
	<li><b>Изображений:</b> PNG, Jpg, Gif, Emf, Svg, Tiff</li>
	<li><b>Другой:</b> PDF, Xps, Dif, Json, Markdown, Sql</li>
     {{< /blocks/products/cells/cells-cloud-language-cardlist >}}    


     

{{< /blocks/products/cells/cells-cloud-language-card >}}

{{< blocks/products/cells/product-card-row title="Популярные операции" >}}
{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Net" title="Экспорт книги в PDF" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/net/export/workbook-to-pdf/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Go" title="Экспорт книги в Json" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/go/export/workbook-to-json/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Java" title="Экспортировать объект списка в Csv" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/java/export/listobject-to-csv/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for PHP" title="Экспорт диаграммы в Png" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/php/export/chart-to-png/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Python" title="Экспорт книги в MD" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/python/export/workbook-to-md/" >}}

{{< blocks/products/cells/cells-cloud-card-popular pfName="Aspose.Cells Cloud SDK for Swift" title="Экспортировать лист в PDF" imgSrc="/cells/app-logos/cells_cloud_conversion.svg" productLink="/cells/swift/export/worksheet-to-pdf/" >}}
{{< /blocks/products/cells/product-card-row >}}
{{< blocks/products/cells/product-card-row title="Поддерживаемые языки разработки" >}}
{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK для Android" imgSrc="/cells/sdk/aspose_cells-for-android.png" productLink="/cells/android/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK для Go" imgSrc="/cells/sdk/aspose_cells-for-go.png" productLink="/cells/go/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="СДК for Java" imgSrc="/cells/sdk/aspose_cells-for-java.png" productLink="/cells/java/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK для сети" imgSrc="/cells/sdk/aspose_cells-for-net.png" productLink="/cells/net/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK для узла" imgSrc="/cells/sdk/aspose_cells-for-node.png" productLink="/cells/node/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK для Perl" imgSrc="/cells/sdk/aspose_cells-for-perl.png" productLink="/cells/perl/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK для PHP" imgSrc="/cells/sdk/aspose_cells-for-php.png" productLink="/cells/php/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK для Python" imgSrc="/cells/sdk/aspose_cells-for-python.png" productLink="/cells/python/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK для Руби" imgSrc="/cells/sdk/aspose_cells-for-ruby.png" productLink="/cells/ruby/" >}}

{{< blocks/products/cells/cells-cloud-card-support pfName="Aspose.Cells Cloud" title="SDK для Swift" imgSrc="/cells/sdk/aspose_cells-for-swift.png" productLink="/cells/swift/" >}}
{{< /blocks/products/cells/product-card-row >}}

{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/i18n/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Образовательные ресурсы" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Документация" href="https://docs.aspose.cloud/cells" >}}
{{< blocks/products/pf/slr-element name="Исходный код" href="https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet" >}}
{{< blocks/products/pf/slr-element name="API Рекомендации" href="https://apireference.aspose.cloud/cells/" >}}
{{< blocks/products/pf/slr-element name="Обучающие видео" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Поддержка продукта" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Бесплатная поддержка" href="https://forum.aspose.cloud/c/cells" >}}
{{< blocks/products/pf/slr-element name="Платная поддержка" href="https://helpdesk.aspose.cloud" >}}
{{< blocks/products/pf/slr-element name="Блог" href="https://blog.aspose.cloud/category/cells/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Почему Aspose.Cells Cloud SDK for .NET?" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Список клиентов" href="https://company.aspose.cloud/customers" >}}
{{< blocks/products/pf/slr-element name="Безопасность" href="https://company.aspose.cloud/legal/security" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/i18n/support-learning-resources >}}

{{< blocks/products/pf/i18n/download-section downloadFreeTrialLink="" pricingInformationLink="https://purchase.aspose.cloud/pricing" >}}

{{< /blocks/products/pf/main-wrap-class >}}

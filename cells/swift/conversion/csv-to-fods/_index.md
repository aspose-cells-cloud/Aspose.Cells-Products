---
title: Convert CSV to FODS via Swift 
description: Create, Edit or Convert Excel files with REST API & Open Source Swift SDK
url: /swift/conversion/csv-to-fods/
family: cells
platformtag: swift
feature: conversion
informat: CSV
outformat: FODS
platform: Swift
otherformats: MD XPS SXC TIFF XLTX FODS XLS XLSM TSV XLTM HTML DIF MHTML SVG XLSB TXT 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert CSV to FODS with Swift" h2="Read, Edit & Export Excel data to other formats like FODS with Open Source Cloud SDK for Swift">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="CSV to FODS Conversion in the Cloud" %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```SaveOptions``` as per desired output format
1. Upload CSV file to default Cloud Storage with ```uploadFile``` method
1. Call ```CellsAPI.cellsSaveAsPostDocumentSaveAs``` method to get the resultant FODS file
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel API & Swift SDK" %}}
Get Excel Cloud SDK for Swift source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-swift) to compile the SDK yourself or head to the [Releases](https://releases.aspose.cloud/) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Swift Code for CSV to FODS Conversion" gistPath="" %}}
```swift
// For complete examples and data files, please go https://github.com/aspose-cells-cloud/aspose-cells-cloud-swift
let expectation = self.expectation(description: "cellsSaveAsPostDocumentSaveAs")
let name:String = "template.csv"
let saveOptions:SaveOptions? = FodsSaveOptions(enableHTTPCompression: nil, saveFormat: "fods", clearData: nil, cachedFileFolder: nil, validateMergedAreas: nil, refreshChartCache: nil, createDirectory: nil, sortNames: nil, calculateFormula: nil, checkFontCompatibility: nil, onePagePerSheet: nil, compliance: nil, defaultFont: nil, printingPageType: nil, imageType: nil, desiredPPI: nil, jpegQuality: nil, securityOptions: nil)
let newfilename:String = "output.fods"
let isAutoFitRows:Bool? = true
let isAutoFitColumns:Bool? = true
let folder:String = "Temp"
let storage:String? = nil
uploadFile(name: name) 
{
	CellsAPI.cellsSaveAsPostDocumentSaveAs(name: name, saveOptions: saveOptions, newfilename: newfilename, isAutoFitRows: isAutoFitRows, isAutoFitColumns: isAutoFitColumns, folder: folder, storage: storage)
	{
		(response, error) in
		guard error == nil else 
		{
			let errorinfo = self.GetErrorDataInfo(error: error as! ErrorResponse)
			print("error info: \(errorinfo!)")
			XCTFail("error cellsSaveAsPostDocumentSaveAs")
			return
		}
		if let response = response 
		{
			XCTAssertEqual(response.code, 200)
			expectation.fulfill()
		}
	}
}
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
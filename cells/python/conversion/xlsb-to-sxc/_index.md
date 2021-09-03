---
title: Convert from Excel XLSB to SXC via Python 
description: Create, Edit or Convert Excel files with REST API & Open Source Python SDK
url: /python/conversion/xlsb-to-sxc/
family: cells
platformtag: python
feature: conversion
informat: XLSB
outformat: SXC
platform: Python
otherformats: XLTX HTML TXT MHTML ODS XLSX DIF CSV MD TSV PDF SXC SVG FODS XLTM XML 
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert XLSB to SXC with Python" h2="Read, Edit & Export Excel data to other formats with open source Cloud SDK for Python">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLSB to SXC Conversion with Python" %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```CellsApi``` with Client Id, Client Secret, Base URL & API version
1. Upload XLSB file to default Cloud Storage with ```CellsApi.upload_file``` method
1. Call ```CellsApi.cells_save_as_post_document_save_as``` method to get the resultant SXC file
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel API & Python SDK" %}}
Get Excel Cloud SDK for Python source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-python) to compile the SDK yourself or head to the [Releases](https://releases.aspose.cloud/) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Python Code for XLSB to SXC Conversion" gistPath="" %}}
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python
import os
import sys
import asposecellscloud
from asposecellscloud.apis.cells_api import CellsApi
api  = asposecellscloud.apis.cells_api.CellsApi(os.getenv('CellsCloudClientId'), os.getenv('CellsCloudClientSecret'), "v3.0" ,os.getenv('CellsCloudApiBaseUrl'))

name ='template.xlsb'    
saveOptions = None
newfilename = "output.sxc"
isAutoFitRows= True
isAutoFitColumns= True
folder = "temp"
result = api.upload_file(folder + '/' + name,  "c:/TestData/" + name)
 
result = api.cells_save_as_post_document_save_as(name, save_options=saveOptions, newfilename=(folder +'/' + newfilename), is_auto_fit_rows=isAutoFitRows, is_auto_fit_columns=isAutoFitColumns, folder=folder)
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
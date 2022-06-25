---
title: Export Listobject to PPTX file via Python
description: Cloud APIs & SDKs for Microsoft Excel & OpenOffice Calc. Export workbok or interanl object to kinds of format file in the Cloud.
url: /python/export/listobject-to-pptx/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Export Listobject to PPTX file in the Cloud" h2="Excel & OpenOffice spreadsheet export with open source Cloud SDK for Python">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Export Listobject to PPTX file in Cloud SDK for Python " %}}
1. Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details
1. Initialize ```LightCellsAPI``` with Client Id, Client Secret, Base URL & API version
1. Call ```post_export``` method to get the resultant PPTX stream
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with Excel REST API" %}}
Get Excel Cloud SDK for .NET source code from [GitHub](https://github.com/aspose-cells-cloud/aspose-cells-cloud-python) to compile the SDK yourself or head to the [Releases](https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/releases) for alternative download options. 

Also have a look at Swagger-based [API Reference](https://apireference.aspose.cloud/cells/#/LightCells/PostExport) to know more about the [Excel REST API](https://products.aspose.cloud/cells/curl/).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Python Code for LISTOBJECT to PPTX Conversion" gistPath="" %}}
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
import os
import base64
from asposecellscloud.apis.light_cells_api import LightCellsApi
cells_api = LightCellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
files ={ 
    "myDocument.xlsx" :  "c:/myDocument.xlsx",
    "Book1.xlsx" :  "c:/Book1.xlsx" 
    }
result = cells_api.post_export(files ,"listobject","pptx")
base64_string  = result.files[0].file_content
base64_bytes = base64_string.encode("ascii")
sample_string_bytes = base64.b64decode(base64_bytes)
f = open(result.files[0].filename, 'w+b')
f.write(sample_string_bytes)
f.close()    
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{% blocks/products/cells/cells-cloud-api-run-export  InputFormat="xlsx,*.xls,*.csv,*.txt,*.ods"  OutputFormat=pptx  ExportObjectType=listobject %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/faq-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

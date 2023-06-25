---
title: TSV to WMF Convert API for Python 
description: Using Aspose.Cells Cloud SDK for Python to convert TSV format file to WMF format file. 
url: /python/conversion/tsv-to-wmf/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API to convert TSV to WMF" h2="Python library to convert TSV to WMF" p="Use Cells Conversion REST API to create customized spreadsheet workflows in Python. This is a professional solution to convert TSV to WMF and other document formats online using Python." urlsection="conversion/tsv-to-wmf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Convert a TSV file to WMF in Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from TSV to WMF is a complex task. All TSV to WMF format transitions is performed by our Python SDK while maintaining the source TSV spreadsheet's main structural and logical content. Our Python library is a professional solution to convert TSV to WMF files online. This Cloud SDK gives Python developers powerful functionality and perfect WMF output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in Python using REST API to convert TSV to WMF format" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.tsv",format="wmf")
    shutil.move(file1, "destFile.wmf")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Python API to convert  TSV to WMF" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call cells_workbook_put_convert_workbook method to get the resultant stream</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Python 2.7 or newer</li>
<li>Python 3.10 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

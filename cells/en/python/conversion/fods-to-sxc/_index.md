---
title: Convert FODS to SXC using Python 
description: Utilizing the Aspose.Cells Cloud SDK for Python to convert a FODS format file to a SXC format file. 
kwords: Excel, Convert FODS to SXC, REST, Python
howto: How to convert FODS to SXC using Aspose.Cells Cloud Python library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Convert FODS to SXC" h2="Python library for converting FODS to SXC" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Python projects. This is a professional solution to convert FODS to SXC and other document formats online using Python." urlsection="conversion/fods-to-sxc/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Convert FODS to SXC using Cells Cloud SDK for Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from FODS to SXC can be a complex task. Our Python SDK handles all FODS to SXC format conversions while preserving the main structural and logical content of the source FODS spreadsheet. Our Python library provides a professional solution for converting FODS to SXC files online. This Cloud SDK empowers Python developers with powerful functionality and ensures high-quality SXC output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Code Example for converting FODS to SXC using Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.fods",format="sxc")
    shutil.move(file1, "destFile.sxc")     
```
 
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to convert FODS to SXC using the Cells Cloud Python library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Python library and add the reference (import the library) to your project.</li>
<li>Open the source file in Python.</li>
<li>Use the `put_convert_workbook` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Python 2.7 or newer</li>
<li>Python 3.10 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

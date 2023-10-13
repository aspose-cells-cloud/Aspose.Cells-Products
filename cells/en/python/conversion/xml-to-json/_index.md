---
title: Convert XML to JSON using Python 
description: Utilizing the Aspose.Cells Cloud SDK for Python to convert a XML format file to a JSON format file. 

---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Convert XML to JSON" h2="Python library for converting XML to JSON" p="Use the Conversion API of of Cells Cloud to create customized spreadsheet workflows in Python projects. This is a professional solution to convert XML to JSON and other document formats online using Python." urlsection="conversion/xml-to-json/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Convert XML to JSON using Cells Cloud SDK for Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/convert  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel  apimethod=PUT %}}
<br/>
Converting file formats from XML to JSON can be a complex task. Our Python SDK handles all XML to JSON format conversions while preserving the main structural and logical content of the source XML spreadsheet. Our Python library provides a professional solution for converting XML to JSON files online. This Cloud SDK empowers Python developers with powerful functionality and ensures high-quality JSON output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Python Code Example for converting XML to JSON using Cells Cloud SDK" gistPath="" %}}
 
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    import os
    import shutil
    from asposecellscloud.apis.cells_api import CellsApi
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    file1 = cells_api.cells_workbook_put_convert_workbook("Book1.xml",format="json")
    shutil.move(file1, "destFile.json")     
```
 
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Cells Cloud SDK for Python to convert Excel files to other formats XML to JSON" >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.</li>
<li>Use the `put_convert_workbook` method to retrieve the resulting stream.</li>
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

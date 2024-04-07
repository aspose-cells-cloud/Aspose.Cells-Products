---
title: Save XLSX as XLSB using Python 
description: Utilizing Aspose.Cells Cloud SDK for Python to save XLSX format file as XLSB format file. 
kwords: Excel, Save XLSX as XLSB, REST, Python
howto: How to save XLSX as XLSB using Aspose.Cells Cloud Python library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save XLSX as XLSB" h2="Python library for saving XLSX as XLSB" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Python. This is a professional solution to save XLSX as XLSB and other document formats online using Python." urlsection="saveas/xlsx-to-xlsb/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a XLSX file as XLSB in Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from XLSX as XLSB is a complex task. All XLSX to XLSB format transitions is performed by our Python SDK while maintaining the source XLSX spreadsheet's main structural and logical content. Our Python library is a professional solution to save XLSX as XLSB files online. This Cloud SDK gives Python developers powerful functionality and perfect XLSB output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Code Example for saving XLSX as XLSB using REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xlsx'    
    saveOptions = None
    newfilename = "Book1Saveas.xlsb"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to save XLSX as XLSB using the Cells Cloud Python library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Python library and add the reference (import the library) to your project.</li>
<li>Open the source file in Python.</li>
<li>Use the `post_workbook_save_as` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Python 2.7 or newer</li>
<li>Python 3.10 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

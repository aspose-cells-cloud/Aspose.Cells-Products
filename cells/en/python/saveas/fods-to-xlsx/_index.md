---
title: Save FODS as XLSX using Python 
description: Utilizing Aspose.Cells Cloud SDK for Python to save FODS format file as XLSX format file. 
kwords: Excel, Save FODS as XLSX, REST, Python
howto: How to save FODS as XLSX using Aspose.Cells Cloud Python library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save FODS as XLSX" h2="Python library for saving FODS as XLSX" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Python. This is a professional solution to save FODS as XLSX and other document formats online using Python." urlsection="saveas/fods-to-xlsx/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a FODS file as XLSX in Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from FODS as XLSX is a complex task. All FODS to XLSX format transitions is performed by our Python SDK while maintaining the source FODS spreadsheet's main structural and logical content. Our Python library is a professional solution to save FODS as XLSX files online. This Cloud SDK gives Python developers powerful functionality and perfect XLSX output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Code Example for saving FODS as XLSX using REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.fods'    
    saveOptions = None
    newfilename = "Book1Saveas.xlsx"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to save FODS as XLSX using the Cells Cloud Python library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Python library and add the reference (import the library) to your project.</li>
<li>Open the source file in Python.</li>
<li>Use the `post_workbook_save_as` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Python 2.7 or newer</li>
<li>Python 3.10 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

---
title: Save XLT as TIFF API for Python 
description: Using Aspose.Cells Cloud SDK for Python to save XLT format file as TIFF format file. 
url: /python/saveas/xlt-to-tiff/
---


{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="Python API to save XLT as TIFF" h2="Python library to save XLT as TIFF" p="Use Cells SaveAs REST API to create customized spreadsheet workflows in Python. This is a professional solution to save XLT as TIFF and other document formats online using Python." urlsection="saveas/xlt-to-tiff/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true"  title="Save a XLT file as TIFF in Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from XLT as TIFF is a complex task. All XLT to TIFF format transitions is performed by our Python SDK while maintaining the source XLT spreadsheet's main structural and logical content. Our Python library is a professional solution to save XLT as TIFF files online. This Cloud SDK gives Python developers powerful functionality and perfect TIFF output.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Code example in Python using REST API to save XLT as TIFF format" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xlt'    
    saveOptions = None
    newfilename = "Book1Saveas.tiff"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-code-div  %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to use Python API to save  XLT as TIFF" >}}
<li>Create an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Initialize CellsApi with Client Id, Client Secret, Base URL & API version</li>
<li>Call cells_save_as_post_document_save_as method to get the resultant stream</li>
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

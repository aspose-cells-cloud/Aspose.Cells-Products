---
title: Save FODS as HTML using Python 
description: Utilizing Aspose.Cells Cloud SDK for Python to save FODS format file as HTML format file. 
kwords: Excel, Save FODS as HTML, REST, Python
howto: How to save FODS as HTML using Aspose.Cells Cloud Python library.
---


{{< blocks/products/cells/cells-cloud-banner h1="Save FODS as HTML" h2="Python library for saving FODS as HTML" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Python. This is a professional solution to save FODS as HTML and other document formats online using Python." urlsection="saveas/fods-to-html/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a FODS file as HTML in Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from FODS as HTML is a complex task. All FODS to HTML format transitions is performed by our Python SDK while maintaining the source FODS spreadsheet's main structural and logical content. Our Python library is a professional solution to save FODS as HTML files online. This Cloud SDK gives Python developers powerful functionality and perfect HTML output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Code Example for saving FODS as HTML using REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.fods'    
    saveOptions = None
    newfilename = "Book1Saveas.html"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="Learn how to save FODS as HTML using the Cells Cloud Python library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Python library and add the reference (import the library) to your project.</li>
<li>Open the source file in Python.</li>
<li>Use the `post_workbook_save_as` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Python 2.7 or newer</li>
<li>Python 3.10 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

---
title: Save XLTX as XLSM using Python 
description: Utilizing Aspose.Cells Cloud SDK for Python to save XLTX format file as XLSM format file. 
kwords: Excel, Save XLTX as XLSM, REST, Python
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to save XLTX as XLSM using the Cells Cloud Python library.","description": "How to save XLTX as XLSM using the Cells Cloud Python library.","image": {"@type": "ImageObject"},"url": "/python/saveas/xltx-to-xlsm/","step": [{ "@type": "HowToStep","name": "How to save XLTX as XLSM using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xltx-to-xlsm/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to save XLTX as XLSM using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xltx-to-xlsm/","text": "Install Python library and add the reference (import the library) to your project.",},{ "@type": "HowToStep","name": "How to save XLTX as XLSM using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xltx-to-xlsm/","text": "Open the source file in Python.",},{ "@type": "HowToStep","name": "How to save XLTX as XLSM using the Cells Cloud Python library. step 1", "image": {"@type": "ImageObject",},"url": "/python/saveas/xltx-to-xlsm/","text": "Use the `post_workbook_save_as` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "PyCharm, Visual Studio Code, Sublime, Eclipse"},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"Why save file as other formats file in C# using REST API?","acceptedAnswer":{"@type":"Answer","text":"Documents are encoded in many ways, and some files may be incompatible with the software you use. To open and read such files, just save them as appropriate file formats.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your project.</li><li>Open the source file in C# using REST API.</li><li>Call the PostWorkbookSaveAsRequest() method, passing an output filename with required extension.</li><li>Get the result of save as a separate file.</li></ol>"}},{"@type":"Question","name":"What file formats can I save as with your C# library?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of file formats for conversion using .NET library, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more."}},{"@type":"Question","name":"What is the maximum allowed file size for conversion using this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---


{{< blocks/products/cells/cells-cloud-banner h1="Save XLTX as XLSM" h2="Python library for saving XLTX as XLSM" p="Use SaveAs API of Cells Cloud to create customized spreadsheet workflows in Python. This is a professional solution to save XLTX as XLSM and other document formats online using Python." urlsection="saveas/xltx-to-xlsm/" >}}

{{< blocks/products/cells/cells-cloud-section  title="Save a XLTX file as XLSM in Python" >}}
{{% blocks/products/cells/cells-cloud-api-reference  apiurl=https://api.aspose.cloud/v3.0/cells/{name}/SaveAs  apireferenceurl=https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs  apimethod=POST %}}
<br/>
Saving file formats from XLTX as XLSM is a complex task. All XLTX to XLSM format transitions is performed by our Python SDK while maintaining the source XLTX spreadsheet's main structural and logical content. Our Python library is a professional solution to save XLTX as XLSM files online. This Cloud SDK gives Python developers powerful functionality and perfect XLSM output.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Python Code Example for saving XLTX as XLSM using REST API" gistPath="" %}}
  
```python
# For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-python/
    cells_api = CellsApi(os.getenv('ProductClientId'),os.getenv('ProductClientSecret'))
    name ='Book1.xltx'    
    saveOptions = None
    newfilename = "Book1Saveas.xlsm"
    isAutoFitRows= True
    isAutoFitColumns= True
    folder = "PythonTest"
    saveResponse = cells_api.cells_save_as_post_document_save_as(name,save_options=saveOptions, newfilename=(folder +'/' + newfilename),folder=folder)
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode  %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="How to save XLTX as XLSM using the Cells Cloud Python library." >}}
<li>Register an account at <a href="https://dashboard.aspose.cloud/">Dashboard</a> to get free API quota & authorization details</li>
<li>Install Python library and add the reference (import the library) to your project.</li>
<li>Open the source file in Python.</li>
<li>Use the `post_workbook_save_as` method to retrieve the resulting stream.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true"  title="System Requirements" >}}
<li>Python 2.7 or newer</li>
<li>Python 3.10 or newer</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

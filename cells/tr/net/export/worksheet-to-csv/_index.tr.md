---
title:  C# için Cells Cloud SDK'yı kullanarak ÇALIŞMA SAYFASI'nı Excel'den CSV'ye aktarın
description:  Aspose.Cells Cloud REST API, {2} kullanılarak {0} dosyasının {1} biçimindeki dosyaların dışa aktarılmasını destekler.
kwords: Excel, worksheet, csv, Net
howto: {"@context": "https://schema.org","@type": "HowTo","name": "How to use Cells Cloud SDK for Net to export objects from Excel WORKSHEET to CSV","description": "How to use Cells Cloud SDK for Net to export objects from Excel WORKSHEET to CSV","image": {"@type": "ImageObject"},"url": "/net/export/worksheet-to-csv/","step": [{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Net to export objects from Excel WORKSHEET to CSV step 1", "image": {"@type": "ImageObject",},"url": "/net/export/worksheet-to-csv/","text": "Register an account at <a href='https://dashboard.aspose.cloud/'>Dashboard</a> to get free API quota & authorization details",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Net to export objects from Excel WORKSHEET to CSV step 1", "image": {"@type": "ImageObject",},"url": "/net/export/worksheet-to-csv/","text": "Initialize the Cells API with your Client ID, Client Secret, Base URL, and API version.",},{ "@type": "HowToStep","name": "How to use Cells Cloud SDK for Net to export objects from Excel WORKSHEET to CSV step 1", "image": {"@type": "ImageObject",},"url": "/net/export/worksheet-to-csv/","text": "Use the `postExport` method to retrieve the resulting stream.",}, ],"supply": {"@type": "HowToSupply","name": "document"},"tool": [{"@type": "HowToTool","name": "Visual Studio, Visual Studio Code, Rider "},{"@type": "HowToTool","name": "Aspose Cells"}],"totalTime": "PT6M"}
fqa: {"@context":"https://schema.org","@type":"FAQPage","mainEntity":[{"@type":"Question","name":"What file formats can excel or its internal elements be converted into?","acceptedAnswer":{"@type":"Answer","text":"We support a variety of output file formats, including XLSX, Excel, xls , PDF, CSV, HTML, Markdown, XML, PNG, JPG, TIFF, Json, TXT and many more.<br/><ol><li>Install .NET SDK and add the reference (import the library) to your .NET project.</li><li>Open the source file in C# using REST API.</li><li>Load the content or the excel file itself to be exported to other formats.</li><li>Call the PostExport() method, passing the output filename with the required extension.</li><li>Get the build results as a single file.</li></ol>"}},{"@type":"Question","name":"What is the maximum file size supported by this .NET library?","acceptedAnswer":{"@type":"Answer","text":"There are no file size limits for format conversions using .NET library."}}]}
---
{{< blocks/products/cells/cells-cloud-banner h1="ÇALIŞMA SAYFASINI Excel\'den CSV\'ye aktar" h2="C# ÇALIŞMA SAYFASI\'nı CSV dosyasına aktarmak için kütüphane" p="Net\'te Excel dosya dahili nesne iş akışlarını dışa aktarmak için Cells Bulut\'un API\'ini Dışa Aktar\'ı kullanın. Bu, C# numaralı telefonu kullanarak ÇALIŞMA SAYFASINI çevrimiçi elektronik tablodan CSV formatındaki dosyaya aktarmak için profesyonel bir çözümdür." urlsection="export/worksheet-to-csv/" >}}

{{< blocks/products/cells/cells-cloud-section title="C# için Cells Cloud SDK\'yı kullanarak WORKSHEET nesnesini CSV formatındaki dosyaya aktarın" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
WORKSHEET nesnesini Excel dosyasından CSV dosyasına aktarmak karmaşık bir iştir. WORKSHEET'i CSV formatına aktarma geçişleri C# SDK'mız tarafından gerçekleştirilir ve kaynak WORKSHEET e-tablosunun ana yapısal ve mantıksal içeriği korunur. C# kitaplığımız, ÇALIŞMA SAYFASI nesnelerini çevrimiçi olarak CSV formatındaki dosyalara aktarmak için profesyonel bir çözümdür. Bu Bulut SDK'sı, C# geliştiriciye güçlü işlevsellik ve mükemmel CSV çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="WORKSHEET\'i elektronik tablodan CSV formatına aktarmak için REST API\'i kullanan C#\'deki kod örneği" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string format = "csv";
    string objectType ="worksheet";
    LightCellsApi lightCellsApi =
        new LightCellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    IDictionary<string ,Stream> files = new  Dictionary<string ,Stream>();
    files.Add("Book1.xlsx" , File.OpenRead("Book1.xlsx"));
    files.Add("myDocument.xlsx", File.OpenRead("myDocument.xlsx"));
    var filesResult = lightCellsApi.PostExport(files, objectType, format);
    foreach (var file in filesResult.Files)
    {
        string v = file.FileContent;
        string filename = file.Filename;
        byte[] workbookData = System.Convert.FromBase64String(v);
        MemoryStream memoryStream = new MemoryStream(workbookData, 0, workbookData.Length);
        memoryStream.Seek(0, SeekOrigin.Begin);
        using (FileStream fileStream = File.Create( filename))
        {
            fileStream.Position = 0;
            memoryStream.CopyTo(fileStream);
            fileStream.Close();
        }
    }
```
   
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Nesneleri Excel WORKSHEET\'ten CSV\'ye aktarmak için Cells Cloud SDK for Net nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için `postExport` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>NET Framework 4.5.2 veya daha yenisi</li>
<li>Net Standardı 2.0 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

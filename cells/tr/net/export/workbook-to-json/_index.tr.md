---
title:  C# için Cells Cloud SDK'yı kullanarak ÇALIŞMA KİTABI'nı Excel'den JSON'a aktarın
description:  Aspose.Cells Cloud REST API, {2} kullanılarak {0} dosyasının {1} biçimindeki dosyaların dışa aktarılmasını destekler.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="ÇALIŞMA KİTABI\'nı Excel\'den JSON\'a aktar" h2="ÇALIŞMA KİTABI\'nı JSON dosyasına aktarmak için C# kitaplığı" p="Net\'te Excel dosya dahili nesne iş akışlarını dışa aktarmak için Cells Bulut\'un API\'ini Dışa Aktar\'ı kullanın. Bu, C# numaralı telefonu kullanarak çevrimiçi elektronik tablodan ÇALIŞMA KİTABI\'nı JSON formatındaki dosyaya aktarmak için profesyonel bir çözümdür." urlsection="export/workbook-to-json/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="C# için Cells Cloud SDK\'yı kullanarak WORKBOOK nesnesini JSON formatındaki dosyaya aktarın" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/export" apireferenceurl="https://apireference.aspose.cloud/cells/#/LightCells/PostExport" apimethod="POST" %}}
<br/>
ÇALIŞMA KİTABI nesnesini Excel dosyasından JSON dosyasına aktarmak karmaşık bir iştir. ÇALIŞMA KİTABI'nı JSON'a aktarma format geçişleri C# SDK'mız tarafından gerçekleştirilir ve aynı zamanda kaynak ÇALIŞMA KİTABI e-tablosunun ana yapısal ve mantıksal içeriği korunur. C# kitaplığımız, ÇALIŞMA KİTABI nesnelerini çevrimiçi olarak JSON formatındaki dosyalara aktarmak için profesyonel bir çözümdür. Bu Bulut SDK'sı, C# geliştiriciye güçlü işlevsellik ve mükemmel JSON çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="ÇALIŞMA KİTABI\'nı e-tablodan JSON biçimine aktarmak için REST API\'i kullanan C#\'deki kod örneği" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string format = "json";
    string objectType ="workbook";
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
   
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Nesneleri Excel WORKBOOK\'tan JSON\'a aktarmak için Cells Cloud SDK for Net nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için `postExport` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>NET Framework 4.5.2 veya daha yenisi</li>
<li>Net Standardı 2.0 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

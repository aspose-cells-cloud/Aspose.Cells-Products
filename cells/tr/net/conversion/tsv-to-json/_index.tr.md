﻿---
title: TSV'den JSON'a Dönüştürme API için C#
description:  TSV formatındaki dosyayı JSON formatındaki dosyaya dönüştürmek için Aspose.Cells Cloud SDK for C#'i kullanma.
url: /tr/net/conversion/tsv-to-json/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="TSV\'yi JSON\'a dönüştürmek için C# API" h2="TSV\'yi JSON\'a dönüştürmek için C# kitaplığı" p="Net\'te özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Conversion REST API\'i kullanın. Bu, TSV\'yi C# kullanarak çevrimiçi olarak JSON\'a ve diğer belge biçimlerine dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/tsv-to-json/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="C#\'de bir TSV dosyasını JSON\'a dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını TSV'den JSON'a dönüştürmek karmaşık bir iştir. Tüm TSV'den JSON formatına geçişler, kaynak TSV e-tablosunun ana yapısal ve mantıksal içeriği korunurken C# SDK'mız tarafından gerçekleştirilir. C# kitaplığımız, TSV'yi çevrimiçi olarak JSON dosyalarına dönüştürmek için profesyonel bir çözümdür. Bu Cloud SDK, C# geliştiricilerine güçlü işlevsellik ve mükemmel JSON çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="TSV\'yi JSON formatına dönüştürmek için REST API kullanan C#\'deki kod örneği" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.tsv";
    string format = "json";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.json";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    using (Stream stream = cellsApi.CellsWorkbookPutConvertWorkbook(File.OpenRead(name), format, password, outPath, storageName))
    {
        using (Stream outStream = File.OpenWrite(destFile))
        {
            stream.CopyTo(outStream);
        }
    }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="TSV\'yi JSON\'a dönüştürmek için C# API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için CellsWorkbookPutConvertWorkbook yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>NET Framework 4.5.2 veya daha yenisi</li>
<li>Net Standard 2.0 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
﻿---
title:  HTML'i C# için API'i CSV'ye dönüştür
description:  HTML biçimindeki dosyayı CSV biçimindeki dosyaya dönüştürmek için C# için Aspose.Cells Cloud SDK'yı kullanma.
url: /tr/net/conversion/html-to-csv/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="HTML\'i CSV\'ye dönüştürmek için C# API" h2="HTML\'i CSV\'ye dönüştürmek için C# kitaplığı" p="Net\'te özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Conversion REST API\'i kullanın. Bu, HTML\'i C# kullanarak çevrimiçi olarak CSV\'ye ve diğer belge biçimlerine dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/html-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir HTML dosyasını C#\'de CSV\'ye dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını HTML'den CSV'ye dönüştürmek karmaşık bir iştir. HTML'den CSV formatına tüm geçişler, C# SDK'mız tarafından gerçekleştirilir ve kaynak HTML elektronik tablosunun ana yapısal ve mantıksal içeriği korunur. C# kitaplığımız, HTML'i çevrimiçi CSV dosyalarına dönüştürmek için profesyonel bir çözümdür. Bu Cloud SDK, C# geliştiricilerine güçlü işlevsellik ve mükemmel CSV çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="HTML\'i CSV formatına dönüştürmek için REST API kullanan C#\'deki kod örneği" gistPath="" %}}
 
```cs
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.html";
    string format = "csv";
    string password = null;
    string outPath = null;
    string storageName = null;
    string destFile = "Book1.csv";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="HTML\'i CSV\'ye dönüştürmek için C# API nasıl kullanılır?" >}}
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
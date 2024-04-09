---
title:  NUMBERS'ı C#'i kullanarak TXT olarak kaydedin
description:  NUMBERS biçimindeki dosyayı TXT biçimindeki dosya olarak kaydetmek için C# için Aspose.Cells Bulut SDK'sını kullanma.
kwords: Excel, Save NUMBERS as TXT, REST, C#
howto: How to save NUMBERS as TXT using Aspose.Cells Cloud C# library.
---
{{< blocks/products/cells/cells-cloud-banner h1="NUMBERS\'ı TXT olarak kaydet" h2="NUMARALARI TXT olarak kaydetmek için C# kitaplığı" p="Net\'te özelleştirilmiş elektronik tablo iş akışları oluşturmak için SaveAs API / Cells Cloud\'u kullanın. Bu, NUMBERS\'ı C#\'i kullanarak çevrimiçi olarak TXT ve diğer belge formatlarında kaydetmek için profesyonel bir çözümdür." urlsection="saveas/numbers-to-txt/" >}}

{{< blocks/products/cells/cells-cloud-section title="NUMBERS dosyasını C#\'e TXT olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
NUMBERS dosyasındaki dosya formatlarını TXT olarak kaydetmek karmaşık bir iştir. NUMBERS'tan TXT'ye tüm format geçişleri, C# SDK'mız tarafından gerçekleştirilir ve kaynak NUMBERS e-tablosunun ana yapısal ve mantıksal içeriği korunur. C# kitaplığımız, NUMARALARI çevrimiçi olarak TXT dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, C# geliştiriciye güçlü işlevsellik ve mükemmel TXT çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="C# REST API\'i kullanarak NUMBERS\'ı TXT olarak kaydetmek için Kod Örneği" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.numbers";
    string newfilename = "Book1SaveAs.txt";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Cells Cloud Net kitaplığını kullanarak NUMBERS\'ı TXT olarak nasıl kaydedeceğinizi öğrenin." >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme detaylarını</li>
<li>C# kütüphanesini kurun ve referansı (kütüphaneyi içe aktarın) projenize ekleyin.</li>
<li>Kaynak dosyayı C#'de açın</li>
<li>Ortaya çıkan akışı almak için `PostWorkbookSaveAs` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>NET Framework 4.5.2 veya daha yenisi</li>
<li>Net Standardı 2.0 veya daha yenisi</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

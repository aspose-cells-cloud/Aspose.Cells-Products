﻿---
title: HTML'i C# için TSV API olarak kaydedin
description:  HTML biçim dosyasını TSV biçim dosyası olarak kaydetmek için C# için Aspose.Cells Cloud SDK'yı kullanma.
url: /tr/net/saveas/html-to-tsv/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="HTML\'i TSV olarak kaydetmek için C# API" h2="HTML\'i TSV olarak kaydetmek için C# kitaplığı" p="Net\'te özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells SaveAs REST API\'i kullanın. Bu, HTML\'i C# kullanarak çevrimiçi olarak TSV ve diğer belge biçimleri olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/html-to-tsv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="HTML dosyasını C#\'de TSV olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
HTML'den dosya formatlarını TSV olarak kaydetmek karmaşık bir iştir. HTML'den TSV biçimine geçişlerin tümü, C# SDK'mız tarafından gerçekleştirilir ve kaynak HTML e-tablosunun ana yapısal ve mantıksal içeriği korunur. C# kitaplığımız, HTML'i çevrimiçi TSV dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Cloud SDK, C# geliştiricilerine güçlü işlevsellik ve mükemmel TSV çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="HTML\'i TSV formatı olarak kaydetmek için REST API\'i kullanan C#\'deki kod örneği" gistPath="" %}}
  
```cs
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-dotnet/
    string name = "Book1.html";
    string newfilename = "Book1SaveAs.tsv";
    string folder = "CellsTests";
    CellsApi cellsApi = new CellsApi(Environment.GetEnvironmentVariable("ProductClientId"), Environment.GetEnvironmentVariable("ProductClientSecret"));
    SaveResponse saveResponse = cellsApi.CellsSaveAsPostDocumentSaveAs(name, null, newfilename, null,null,folder);
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="HTML\'i TSV olarak kaydetmek için C# API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için CellsSaveAsPostDocumentSaveAs yöntemini çağırın</li>
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
﻿---
title:  Go'yu kullanarak XLSX'i CSV olarak kaydedin
description:  XLSX formatındaki dosyayı CSV formatındaki dosya olarak kaydetmek için Go için Aspose.Cells Cloud SDK'yı kullanma.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLSX\'i CSV olarak kaydet" h2="XLSX\'i CSV olarak kaydetmek için kitaplığa gidin" p="Go\'da özelleştirilmiş elektronik tablo iş akışları oluşturmak için SaveAs API / Cells Cloud\'u kullanın. Bu, XLSX\'i Go kullanarak çevrimiçi olarak CSV ve diğer belge formatları olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/xlsx-to-csv/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="XLSX dosyasını Go\'da CSV olarak kaydetme" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını XLSX'ten CSV olarak kaydetmek karmaşık bir iştir. Tüm XLSX'ten CSV formatına geçişler Go SDK'mız tarafından gerçekleştirilir ve kaynak XLSX elektronik tablosunun ana yapısal ve mantıksal içeriği korunur. Go kitaplığımız, XLSX'i çevrimiçi CSV dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, Go geliştiricilerine güçlü işlevsellik ve mükemmel CSV çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="REST API\'i kullanarak XLSX\'i CSV olarak kaydetmek için Kod Örneğine gidin" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.xlsx"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.csv"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını diğer XLSX formatlarındaki CSV olarak kaydetmek için Cells Cloud SDK for Go nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için `PostWorkbookSaveAs` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>go sürümü go1.13.0 veya daha yeni</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

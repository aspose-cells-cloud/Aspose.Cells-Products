﻿---
title:  NUMARALARI Go için EMF API olarak kaydedin
description:  NUMBERS biçim dosyasını EMF biçim dosyası olarak kaydetmek için Aspose.Cells Cloud SDK for Go'yu kullanma.
url: /tr/go/saveas/numbers-to-emf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="SAYILARI EMF olarak kaydetmek için API\'e gidin" h2="SAYILARI EMF olarak kaydetmek için kitaplığa gidin" p="Go\'da özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells SaveAs REST API\'i kullanın. Bu, NUMARALARI EMF olarak ve diğer belge biçimlerini çevrimiçi olarak Go kullanarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/numbers-to-emf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir NUMBERS dosyasını Go\'da EMF olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
NUMBERS'den dosya biçimlerini EMF olarak kaydetmek karmaşık bir iştir. EMF biçimine tüm NUMBERS geçişleri, kaynak NUMBERS e-tablonun ana yapısal ve mantıksal içeriği korunurken Go SDK'mız tarafından gerçekleştirilir. Go kitaplığımız, NUMARALARI çevrimiçi olarak EMF dosyası olarak kaydetmek için profesyonel bir çözümdür. Bu Cloud SDK, Go geliştiricilerine güçlü işlevsellik ve mükemmel EMF çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="SAYILARI EMF biçiminde kaydetmek için REST API kullanan Go\'daki kod örneği" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.numbers"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.emf"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="SAYILARI EMF olarak kaydetmek için Go API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için CellsSaveAsPostDocumentSaveAs yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>sürüm go1.13.0 veya daha yenisine gidin</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
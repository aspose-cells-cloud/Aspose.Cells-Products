﻿---
title:  JPG'yi Go için PDF API olarak kaydedin
description:  JPG formatındaki dosyayı PDF formatındaki dosya olarak kaydetmek için Aspose.Cells Cloud SDK for Go'yu kullanma.
url: /tr/go/saveas/jpg-to-pdf/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="JPG\'yi PDF olarak kaydetmek için API\'e gidin" h2="JPG\'yi PDF olarak kaydetmek için kitaplığa gidin" p="Go\'da özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells SaveAs REST API\'i kullanın. Bu, Go\'yu kullanarak JPG\'yi PDF olarak ve diğer belge formatlarını çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/jpg-to-pdf/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir JPG dosyasını Go\'da PDF olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya biçimlerini JPG'den PDF olarak kaydetmek karmaşık bir iştir. Tüm JPG - PDF biçim geçişleri, kaynak JPG e-tablosunun ana yapısal ve mantıksal içeriği korunurken Go SDK'mız tarafından gerçekleştirilir. Go kitaplığımız, JPG'yi çevrimiçi olarak PDF dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Cloud SDK, Go geliştiricilerine güçlü işlevsellik ve mükemmel PDF çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="JPG\'yi PDF biçiminde kaydetmek için REST API kullanan Go\'daki kod örneği" gistPath="" %}}
  
```go
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-go/
    instance := asposecellscloud.NewCellsApiService(os.Getenv("ProductClientId"), os.Getenv("ProductClientSecret"))
    saveAsOpts := new(asposecellscloud.CellsSaveAsPostDocumentSaveAsOpts)
    saveAsOpts.Name = "Book1.jpg"
    saveAsOpts.Folder = "CellsTests"
    saveAsOpts.Newfilename = "Book1SaveAs.pdf"
    _, _, err1 := instance.CellsSaveAsPostDocumentSaveAs(saveAsOpts)
    if err1 != nil {
	    println(err1)
    }
```
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="JPG\'yi PDF olarak kaydetmek için Go API nasıl kullanılır?" >}}
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
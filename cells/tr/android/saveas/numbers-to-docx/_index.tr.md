﻿---
title:  Android kullanarak NUMBERS'ı DOCX olarak kaydedin
description:  NUMBERS biçimindeki dosyayı DOCX biçimindeki dosya olarak kaydetmek için Android için Aspose.Cells Bulut SDK'sını kullanma.
kwords: Excel, Save NUMBERS as DOCX, REST, Android
howto: How to save NUMBERS as DOCX using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="NUMBERS\'ı DOCX olarak kaydet" h2="NUMBERS\'ı DOCX olarak kaydetmek için Android kitaplığı" p="Android\'de özelleştirilmiş e-tablo iş akışları oluşturmak için SaveAs API / Cells Cloud\'u kullanın. Bu, Android kullanarak NUMBERS\'ı DOCX ve diğer belge formatları olarak çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/numbers-to-docx/" >}}

{{< blocks/products/cells/cells-cloud-section title="Android\'de bir NUMBERS dosyasını DOCX olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
NUMBERS dosyasındaki dosya formatlarını DOCX olarak kaydetmek karmaşık bir iştir. Tüm NUMBERS'tan DOCX formatına geçişler, kaynak NUMBERS e-tablosunun ana yapısal ve mantıksal içeriği korunurken Android SDK'mız tarafından gerçekleştirilir. Android kitaplığımız, NUMBERS'ı çevrimiçi DOCX dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, Android geliştiricilerine güçlü işlevsellik ve mükemmel DOCX çıktısı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="REST API\'i kullanarak NUMBERS\'ı DOCX olarak kaydetmek için Android Kod Örneği" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.numbers";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.docx";
    String folder ="CellsTests";
    try
    {
        CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
        cellsApi.cellsSaveAsPostDocumentSaveAs(name , saveOptions,newfilename,false,false,folder,null,null,null,true);                       
    }
    catch(Exception exception )
    {
        System.out.print(exception);
    }
```
  
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını diğer formatlarda kaydetmek için Android için Cells Cloud SDK nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için `postWorkbookSaveAs` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Android 7 veya daha yenisi</li>
<li>Java(TM) SE Çalışma Zamanı Ortamı</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

﻿---
title:  Android kullanarak CSV'yi XLS olarak kaydedin
description:  CSV formatındaki dosyayı XLS formatındaki dosya olarak kaydetmek için Android için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Save CSV as XLS, REST, Android
howto: How to save CSV as XLS using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="CSV\'yi XLS olarak kaydet" h2="CSV\'yi XLS olarak kaydetmek için Android kütüphanesi" p="Android\'de özelleştirilmiş e-tablo iş akışları oluşturmak için SaveAs API / Cells Cloud\'u kullanın. Bu, Android\'i kullanarak CSV\'yi XLS ve diğer belge formatlarını çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/csv-to-xls/" >}}

{{< blocks/products/cells/cells-cloud-section title="Android\'de bir CSV dosyasını XLS olarak kaydetme" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını CSV'den XLS olarak kaydetmek karmaşık bir iştir. Tüm CSV'den XLS formatına geçişler, kaynak CSV elektronik tablosunun ana yapısal ve mantıksal içeriği korunarak Android SDK'mız tarafından gerçekleştirilir. Android kitaplığımız CSV'yi çevrimiçi XLS dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, Android geliştiricilerine güçlü işlevsellik ve mükemmel XLS çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="REST API kullanarak CSV\'yi XLS olarak kaydetmek için Android Kod Örneği" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
    String name = "Book1.csv";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xls";
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

---
title:  Java'i kullanarak EMF'i XPS olarak kaydedin
description:  Aspose.Cells Cloud SDK for Java'i kullanarak EMF format dosyasını XPS format dosyası olarak kaydedin.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="EMF\'i XPS olarak kaydet" h2="EMF\'i XPS olarak kaydetmek için Java kitaplığı" p="Java\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulut\'un API\'ini Kaydet\'i kullanın. Bu, EMF\'i XPS olarak ve diğer belge formatlarını Java\'i kullanarak çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/emf-to-xps/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="EMF dosyasını Java\'e XPS olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya formatlarını EMF'den XPS olarak kaydetmek karmaşık bir iştir. EMF ile XPS arasındaki tüm format geçişleri, Java SDK'mız tarafından gerçekleştirilir ve kaynak EMF elektronik tablosunun ana yapısal ve mantıksal içeriği korunur. Java kitaplığımız, EMF'i çevrimiçi olarak XPS dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Bulut SDK, Java geliştiricilerine güçlü işlevsellik ve mükemmel XPS çıktı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="Java REST API\'i kullanarak EMF\'i XPS olarak kaydetmek için Kod Örneği" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.emf";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.xps";
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
  
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını diğer formatlarda kaydetmek için Cells Cloud SDK for Java nasıl kullanılır? EMF, XPS olarak" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için `postWorkbookSaveAs` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Maven 2.2.0 veya daha yenisi</li>
<li>Java(TM) SE Çalışma Zamanı Ortamı</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

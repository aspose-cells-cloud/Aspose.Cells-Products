﻿---
title:  XLSX'i TXT olarak kaydet API for Java
description:  XLSX biçim dosyasını TXT biçim dosyası olarak kaydetmek için Aspose.Cells Cloud SDK for Java'i kullanma.
url: /tr/java/saveas/xlsx-to-txt/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLSX\'i TXT olarak kaydetmek için Java API" h2="XLSX\'i TXT olarak kaydetmek için Java kitaplığı" p="Java\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells SaveAs REST API\'i kullanın. Bu, Java\'i kullanarak XLSX\'i TXT ve diğer belge formatlarını çevrimiçi olarak kaydetmek için profesyonel bir çözümdür." urlsection="saveas/xlsx-to-txt/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir XLSX dosyasını Java\'de TXT olarak kaydedin" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/{name}/SaveAs" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PostWorkbookSaveAs" apimethod="POST" %}}
<br/>
Dosya biçimlerini XLSX'ten TXT olarak kaydetmek karmaşık bir iştir. Tüm XLSX'ten TXT formatına geçişler, kaynak XLSX elektronik tablosunun ana yapısal ve mantıksal içeriği korunurken Java SDK'mız tarafından gerçekleştirilir. Java kitaplığımız, XLSX'i çevrimiçi TXT dosyaları olarak kaydetmek için profesyonel bir çözümdür. Bu Cloud SDK, Java geliştiricilerine güçlü işlevsellik ve mükemmel TXT çıkışı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="XLSX\'i TXT formatı olarak kaydetmek için REST API\'i kullanan Java\'deki kod örneği" gistPath="" %}}
  
```java
// For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-java/
    String name = "Book1.xlsx";
    SaveOptions saveOptions = null;
    String newfilename = "Book1_xlsx.txt";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="XLSX\'i TXT olarak kaydetmek için Java API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için cellSaveAsPostDocumentSaveAs yöntemini çağırın</li>
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
﻿---
title:  Android için XLSB'den XLTX'e Dönüştürme API
description:  XLSB biçimli dosyayı XLTX biçimli dosyaya dönüştürmek için Aspose.Cells Cloud SDK for Android'i kullanma.
url: /tr/android/conversion/xlsb-to-xltx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="XLSB\'yi XLTX\'e dönüştürmek için Android API" h2="XLSB\'yi XLTX\'e dönüştürmek için Android kitaplığı" p="Android\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Conversion REST API\'i kullanın. Bu, Android kullanarak çevrimiçi olarak XLSB\'yi XLTX\'e ve diğer belge biçimlerine dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/xlsb-to-xltx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Bir XLSB dosyasını Android\'de XLTX\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını XLSB'den XLTX'e dönüştürmek karmaşık bir iştir. Tüm XLSB'den XLTX'e format geçişleri, kaynak XLSB elektronik tablosunun ana yapısal ve mantıksal içeriği korunurken Android SDK'mız tarafından gerçekleştirilir. Android kitaplığımız, XLSB'yi çevrimiçi olarak XLTX dosyalarına dönüştürmek için profesyonel bir çözümdür. Bu Cloud SDK, Android geliştiricilerine güçlü işlevsellik ve mükemmel XLTX çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="XLSB\'yi XLTX formatına dönüştürmek için REST API kullanan Android\'de kod örneği" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xlsb";
                String format = "xltx";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.xltx";
                try {
                    CellsApi cellsApi = new CellsApi(System.getenv("ProductClientId"), System.getenv("ProductClientSecret"));
                    File response = cellsApi.cellsWorkbookPutConvertWorkbook(new File(name), format, password, outPath, null,null);            
                    if(response.canRead())
                    {
                        if(response.exists()){
                            response.renameTo(new File(destFile));
                        }                
                    }
                }
                catch(Exception exception )
                {
                    System.out.print(exception);
                }
            }
        }
```
 
{{% /blocks/products/cells/cells-cloud-code-div %}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="XLSB\'yi XLTX\'ye dönüştürmek için Java API nasıl kullanılır?" >}}
<li> adresinde bir hesap oluşturun<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> Ücretsiz almak için API kota & yetkilendirme detayları</li>
<li>CellsApi'yi İstemci Kimliği, İstemci Sırrı, Temel URL ve API sürümüyle başlatın</li>
<li>Ortaya çıkan akışı almak için cellsWorkbookPutConvertWorkbook yöntemini çağırın</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}
<br/>
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Android 7 veya daha yenisi</li>
<li>Java(TM) SE Çalışma Zamanı Ortamı</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< /blocks/products/cells/cells-cloud-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}
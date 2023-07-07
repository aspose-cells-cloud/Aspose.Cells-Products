---
title:  Android için TSV'den XLTX'e Dönüştürme API
description:  TSV formatındaki dosyayı XLTX formatındaki dosyaya dönüştürmek için Aspose.Cells Cloud SDK for Android'i kullanma.
url: /tr/android/conversion/tsv-to-xltx/
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/cells/cells-cloud-upper-banner h1="TSV\'yi XLTX\'e dönüştürmek için Android API" h2="TSV\'yi XLTX\'e dönüştürmek için Android kitaplığı" p="Android\'de özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Conversion REST API\'i kullanın. Bu, Android kullanarak çevrimiçi olarak TSV\'yi XLTX\'e ve diğer belge biçimlerine dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/tsv-to-xltx/" >}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/cells/cells-cloud-section isGrey="true" title="Android\'de bir TSV dosyasını XLTX\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını TSV'den XLTX'e dönüştürmek karmaşık bir iştir. Tüm TSV'den XLTX'e format geçişleri, kaynak TSV elektronik tablosunun ana yapısal ve mantıksal içeriği korunurken Android SDK'mız tarafından gerçekleştirilir. Android kitaplığımız, TSV'yi çevrimiçi olarak XLTX dosyalarına dönüştürmek için profesyonel bir çözümdür. Bu Cloud SDK, Android geliştiricilerine güçlü işlevsellik ve mükemmel XLTX çıktısı sağlar.
<br/>
<br/>
{{% blocks/products/cells/cells-cloud-code-div title="TSV\'yi XLTX formatına dönüştürmek için REST API kullanan Android\'de kod örneği" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.tsv";
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
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="TSV\'yi XLTX\'ye dönüştürmek için Java API nasıl kullanılır?" >}}
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

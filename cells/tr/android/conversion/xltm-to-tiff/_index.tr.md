﻿---
title:  Android'i kullanarak XLTM'yi TIFF'e dönüştürün
description:  XLTM biçimindeki bir dosyayı TIFF biçimindeki bir dosyaya dönüştürmek için Android için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Convert XLTM to TIFF, REST, Android
howto: How to convert XLTM to TIFF using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="XLTM\'yi TIFF\'e dönüştür" h2="XLTM\'yi TIFF\'e dönüştürmek için Android kitaplığı" p="Android projelerinde özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulut\'un API Dönüşümünü kullanın. Bu, Android\'i kullanarak XLTM\'yi TIFF\'e ve diğer belge formatlarına çevrimiçi dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/xltm-to-tiff/" >}}

{{< blocks/products/cells/cells-cloud-section title="Android için Cells Cloud SDK\'yı kullanarak XLTM\'yi TIFF\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını XLTM'den TIFF'e dönüştürmek karmaşık bir iş olabilir. Android SDK'mız, kaynak XLTM elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken, tüm XLTM'den TIFF formatına dönüşümleri gerçekleştirir. Android kitaplığımız, XLTM'yi çevrimiçi olarak TIFF dosyalara dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK, Android geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli TIFF çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Cells Cloud SDK\'yı kullanarak XLTM\'yi TIFF\'e dönüştürmek için Android Kod Örneği" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.xltm";
                String format = "tiff";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.tiff";
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
 
{{% /blocks/products/cells/cells-cloud-noreplacecode %}}
<br/>
{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="Excel dosyalarını diğer formatlara dönüştürmek için Android için Cells Cloud SDK nasıl kullanılır?" >}}
<li> Şu adreste bir hesap kaydedin:<a href="https://dashboard.aspose.cloud/">Gösterge Paneli</a> ücretsiz almak için API kota ve yetkilendirme ayrıntılarını</li>
<li>Cells API'i Müşteri Kimliğiniz, Müşteri Sırrınız, Temel URL'niz ve API sürümünüzle başlatın.</li>
<li>Ortaya çıkan akışı almak için `putConvertWorkbook` yöntemini kullanın.</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

{{< blocks/products/cells/cells-cloud-section-list isGrey="true" title="sistem gereksinimleri" >}}
<li>Android 7 veya daha yenisi</li>
<li>Java(TM) SE Çalışma Zamanı Ortamı</li>
{{< /blocks/products/cells/cells-cloud-section-list >}}

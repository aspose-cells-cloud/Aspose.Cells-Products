﻿---
title:  Android'i kullanarak ODS'yi XPS'e dönüştürün
description:  ODS biçimindeki bir dosyayı XPS biçimindeki bir dosyaya dönüştürmek için Android için Aspose.Cells Cloud SDK'yı kullanma.
kwords: Excel, Convert ODS to XPS, REST, Android
howto: How to convert ODS to XPS using Aspose.Cells Cloud Android library.
---
{{< blocks/products/cells/cells-cloud-banner h1="ODS\'yi XPS\'e dönüştür" h2="ODS\'yi XPS\'e dönüştürmek için Android kitaplığı" p="Android projelerinde özelleştirilmiş elektronik tablo iş akışları oluşturmak için Cells Bulut\'un API Dönüşümünü kullanın. Bu, Android kullanarak ODS\'yi çevrimiçi olarak XPS\'e ve diğer belge formatlarına dönüştürmek için profesyonel bir çözümdür." urlsection="conversion/ods-to-xps/" >}}

{{< blocks/products/cells/cells-cloud-section title="Android için Cells Cloud SDK\'yı kullanarak ODS\'yi XPS\'e dönüştürün" >}}
{{% blocks/products/cells/cells-cloud-api-reference apiurl="https://api.aspose.cloud/v3.0/cells/convert" apireferenceurl="https://apireference.aspose.cloud/cells/#/Conversion/PutConvertExcel" apimethod="PUT" %}}
<br/>
Dosya formatlarını ODS'den XPS'e dönüştürmek karmaşık bir iş olabilir. Android SDK'mız, kaynak ODS elektronik tablosunun ana yapısal ve mantıksal içeriğini korurken tüm ODS'den XPS formatına dönüşümleri gerçekleştirir. Android kitaplığımız, ODS'yi çevrimiçi olarak XPS dosyalarına dönüştürmek için profesyonel bir çözüm sunar. Bu Bulut SDK, Android geliştiricilerine güçlü işlevsellik kazandırır ve yüksek kaliteli XPS çıkışı sağlar.

{{< /blocks/products/cells/cells-cloud-section >}}

{{% blocks/products/cells/cells-cloud-noreplacecode title="Cells Cloud SDK\'yı kullanarak ODS\'yi XPS\'e dönüştürmek için Android Kod Örneği" gistPath="" %}}
 
```java
    // For complete examples and data files, please go to https://github.com/aspose-cells-cloud/aspose-cells-cloud-android/
        import java.io.File;
        import com.aspose.cloud.cells.api.*;
        public class Conversion {
            public static void main(String[] args) {
                String name =  "Book1.ods";
                String format = "xps";
                String password = null;
                String outPath = null;
                String destFile = "DestFile.xps";
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
